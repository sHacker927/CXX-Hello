cmake_minimum_required(VERSION "3.25.1")

project("CXX Hello")

PROJECT_NAME

add_executable("${PROJECT_NAME}" "main.cpp")  

install(TARGETS "${PROJECT_NAME}" DESTINTATION bin)  #${CMAKE_INSTALL_PREFIX}/bin
install(FILES "MAIN.cpp" DESTINATION src)            #${CMAKE_INSTALL_PREFIX}/src

