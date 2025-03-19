cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "./src/BMI085.cpp" 
                      INCLUDE_DIRS "./src"
                      REQUIRES arduino-esp32
                      )
project(BMI085)
