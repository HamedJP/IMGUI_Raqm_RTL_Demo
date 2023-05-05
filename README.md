Dear ImGui RTL Demo
====
The original ImGui (https://github.com/ocornut/imgui) does not support RTL text, like arabic and hebrew.
This is a demo app that uses ImGui_Raqm (https://github.com/HamedJP/imgui_Raqm) which is fork of original Dear ImGui.
ImGui_Raqm is not ready yet. so there are still lots of bugs

Building
--------
depends on the following libraries:
* [Raqm][1]
* [GLFW][2]

To install dependencies on Ubuntu and wsl:

    sudo apt-get install libfreetype6-dev libharfbuzz-dev libfribidi-dev meson gtk-doc-tools libglfw3-dev

To install dependencies on windows:

    vcpkg install libraqm

To run this demo in linux:

    make && ./helloRaqm.out

[1]: https://github.com/HOST-Oman/libraqm
[2]: https://github.com/glfw/glfw