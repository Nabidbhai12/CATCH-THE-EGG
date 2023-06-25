cmake_minimum_required(VERSION 3.23)
project(1905013)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(OpenGL)
include_directories(OpenGL/include)

add_executable(1905013
        OpenGL/include/GL.H
        OpenGL/include/GLAux.h
        OpenGL/include/GLU.H
        OpenGL/include/glui.h
        OpenGL/include/glut.h
        Eggmaintain.h
        GL.H
        GLAux.h
        GLU.H
        glui.h
        glut.h
        header1.h
        header2.h
        iGraphics.h
        initialization.h
        maingame.cpp
        menu.h
        menus.h
        savegame.h
        scorestuff.h)
