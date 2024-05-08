cmake_minimum_required(VERSION "3.25.1")

project("CXX-Hello")

add_executable("${PROJECT_NAME}" "main.cpp")  

install(TARGETS "${PROJECT_NAME}" DESTINATION bin)  #${CMAKE_INSTALL_PREFIX}/bin
install(FILES "MAIN.cpp" DESTINATION src)            #${CMAKE_INSTALL_PREFIX}/src

