cmake_minimum_required(VERSION 3.10)

project(htmlplus)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)
include_directories(thirdparty/pugixml)

add_executable(htmlplus src/htmlplus.cpp thirdparty/pugixml/pugixml.cpp)


