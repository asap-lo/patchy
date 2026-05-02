cmake_minimum_required(VERSION 3.23)

project(Patchy)

include(cmake/CPM.cmake)

CPMAddPackage(
    URI "gh:juce-framework/JUCE#8.0.12"
)