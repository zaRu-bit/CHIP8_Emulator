# CMakeList.txt : CMake project for CHIP8_Emulator, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (CHIP8_Emulator   "Chip8.cpp" "Chip8.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET CHIP8_Emulator PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
