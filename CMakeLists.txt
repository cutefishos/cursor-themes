cmake_minimum_required(VERSION 3.5)
project(cutefish-cursor)

install(DIRECTORY cutefish-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/usr/share/themes)
install(DIRECTORY cutefish-light DESTINATION ${CMAKE_INSTALL_PREFIX}/usr/share/themes)
