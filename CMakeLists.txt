cmake_minimum_required(VERSION 3.23)
project(Animals)

set(CMAKE_CXX_STANDARD 17)

add_executable(Animals main.cpp Animal.cpp Animal.h Vertebrates.cpp Vertebrates.h Ivertebrates.cpp Ivertebrates.h Mammals.cpp Mammals.h Marine.cpp Marine.h Poultry.cpp Poultry.h Dolphin.cpp Dolphin.h Insects.cpp Insects.h Araneae.cpp Araneae.h Beetle.cpp Beetle.h Penguin.cpp Penguin.h Cat.cpp Cat.h)
