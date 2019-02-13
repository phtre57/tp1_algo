cmake_minimum_required(VERSION 3.13)
project(question4)

set(CMAKE_CXX_STANDARD 14)

add_executable(question4 arbre.h utilitaire.h arbre_etudiant.cpp arbre.cpp utilitaire.cpp test_arbre.cpp)