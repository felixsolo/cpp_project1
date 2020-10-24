
cmake_minimum_required(VERSION 2.6)

# include_directories(${GTEST_INCLUDE_DIRS})

# linking
add_executable(myCppProjectBin src/file_main.cpp)
target_link_libraries(myCppProjectBin pthread)
