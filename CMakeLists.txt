cmake_minimum_required(VERSION 3.22.2)

project(my_figures_project)

set(SOURCES
    main.cpp
    figure.cpp
    triangle.cpp
    rectangular_triangle.cpp
    isosceles_triangle.cpp
    equilateral_triangle.cpp
    quadrangle.cpp
    rectangle.cpp
    square.cpp
    parallelogram.cpp
    rhomb.cpp
)

set(HEADERS
    figure.h
    triangle.h
    rectangular_triangle.h
    isosceles_triangle.h
    equilateral_triangle.h
    quadrangle.h
    rectangle.h
    square.h
    parallelogram.h
    rhomb.h
)

add_executable(${PROJECT_NAME} ${SOURCES} ${HEADERS})