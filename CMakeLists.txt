
cmake_minimum_required(VERSION 2.6)

# include_directories(${GTEST_INCLUDE_DIRS})

# linking
add_executable(bin_cpp_project1 src/file_main.cpp)
target_link_libraries(bin_cpp_project1 pthread)
