cmake_minimum_required(VERSION 3.6)
project(the_cpp_language_tutorial)


set(CMAKE_CXX_STANDARD 14)
include_directories("/Users/guoy28/Downloads/seqan-library-2.3.2/include")

set(SOURCE_FILES
        declaration_example.cpp
        dynamic_memory.cpp
        function.cpp
        overloading.cpp
        pass_by_ref.cpp
        pointer.cpp
        myString.cpp
        myStringstream.cpp
        array.cpp array.h
        hello.cpp main.cpp main.h hello.h array.h declaration_example.h.h dynamic_memory.h function.h function_pointer.h overloading.h pass_by_ref.h pointer.h myString.h myStringstream.h FirstClass.cpp FirstClass.h OperatorOverloading.cpp OperatorOverloading.h ThisUsage.cpp ThisUsage.h ClassStaticVariable.cpp ClassStaticVariable.h FriendExample.cpp FriendExample.h FriendClassExample.cpp FriendClassExample.h InheritanceExample.cpp InheritanceExample.h AbstractBaseClassExample.cpp AbstractBaseClassExample.h TemplateExample.cpp TemplateExample.h vectorExample.cpp vectorExample.h templateSpecialization.cpp templateSpecialization.h stdException.cpp stdException.h seqan_fa.cpp seqan_fa.h Casting.cpp Casting.h)

add_executable(the_cpp_language_tutorial ${SOURCE_FILES})