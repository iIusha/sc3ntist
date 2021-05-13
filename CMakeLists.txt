cmake_minimum_required(VERSION 3.10)
project(sc3ntist)
set(CMAKE_CXX_STANDARD 17)
add_executable(sc3ntist src/SCXParser.cpp
        src/parser/CCCharset.cpp
        src/parser/CCDisassembler.cpp
        src/parser/RNECharset.cpp
        src/parser/RNEDisassembler.cpp
        src/parser/SC3Argument.cpp
        src/parser/SC3BaseDisassembler.cpp
        src/parser/SC3CodeBlock.cpp
        src/parser/SC3Expression.cpp
        src/parser/SC3Instruction.cpp
        src/parser/SC3StringDecoder.cpp
        src/parser/SCXFile.cpp
        src/parser/SGHDDisassembler.cpp
        src/parser/SupportedGame.cpp
        src/parser/ZeroDisassembler.cpp)
