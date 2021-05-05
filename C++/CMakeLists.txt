#1.cmake verson，指定cmake版本
cmake_minimum_required(VERSION 3.2)

#2.project name，指定项目的名称，一般和项目的文件夹名称对应
PROJECT(Demo)

#3.head file path，头文件目录
# INCLUDE_DIRECTORIES(
#     RootFinder
# )

ADD_EXECUTABLE(${PROJECT_NAME} Demo.cpp RapidTrajectoryGenerator.cpp SingleAxisTrajectory.cpp)

