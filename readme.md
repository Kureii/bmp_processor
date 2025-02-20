# BMP Image Processor

Simple BMP file processor implementing custom loader and saver. Built as an experiment with inverse onion architecture (GUI & IO as core).

## Technologies

- C++23 with modules
- CMake build system
- SDL for GUI and rendering
- GCC 13.3.0

## Features

- Loading and saving BMP files
- Display of BMP file metadata (header)
- Basic image transformations:
- Color inversion
- Horizontal/vertical flip
- 90-degree rotation
- Live preview of changes

## Inverse Onion Architecture

The project uses experimental "inverse onion architecture" approach where GUI and IO operations form the core of the system. This unconventional approach was chosen to verify its sustainability and practicality in a real application.


## Build Requirements

- CMake 3.20+
- C++20 compatible compiler
- SDL2 library
- Git (for cloning)

## Installation

```bash
git clone [repository-url]
cd bmp-processor
mkdir build && cd build
cmake ..
cmake --build .