cmake_minimum_required(VERSION 2.8.9)
project(CTestTestMemcheckDummyValgrindPrePost)
include(CTest)

add_test (RunCMake "${CMAKE_COMMAND}")
