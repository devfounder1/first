cmake_minimum_required (VERSION 3.5)
project (NEW EIGEN)

find_package (Eigen 5.0.0 REQUIRED NO_MODULE)

add_executable (example src\test.cpp)
target_link_libraries (example Eigen3::Eigen)