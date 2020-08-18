# chip8 Emulator for the N64
Generates a ROM built with CMake

Note: this is currently WiP for Windows 10 based dev environments.

# this example requires libdragon specific changes that can be found in https://github.com/n64-tools branch develop

Requires:
* https://cmake.org/download/ to be installed
* VSCode with `CMake`, `CMake Tools` and `C/C++` extensions

* Run `UpdateToolchain.ps1` to download and install the required toolchain and libdragon files to the projects toolchain directory
* Adjust cmake-variants.json for your paths
* Adjust .vscode/settings.json for your paths

In vscode hit F7 to build the ROM
