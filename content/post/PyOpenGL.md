---
title: "OpenGL in Python with PyOpenGL"
date: 2020-08-19T19:11:00+05:30
Description: ""
Tags: []
Categories: [Tech,OpenGL,Installation]
DisableComments: false
---

## Installation for Ubuntu based OS

## Requirements

* Python 3
* python3-pip

## Open the terminal
## Update the system

    sudo apt-get update

## For PyOpenGL packages

    pip3 install PyOpenGL PyOpenGL_accelerate

## For freeglut

    sudo apt-get install libglu1-mesa-dev freeglut3-dev mesa-common-dev

## To check the installation
* Open a new python file
* Enter the code

        from OpenGL.GL import *
        from OpenGL.GLU import *
        from OpenGL.GLUT import *
        print('package Import Successful') 
        # If you see this printed to the console then installation was successful

## For sample programs

### Refer [kiranmurali93/pyopengl_lab](https://github.com/kiranmurali93/pyopengl_lab)

