add_library(calculate
src/addition.cpp
src/multiplication.cpp)

target_include_directories(calculate PUBLIC include)