
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

ADD_LIBRARY(tinyxml STATIC EXCLUDE_FROM_ALL
	tinyxml.cpp
	tinyxml.h
	tinyxmlerror.cpp
	tinyxmlparser.cpp
)
