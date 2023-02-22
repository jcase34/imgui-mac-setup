# imgui-mac-setup

## Steps to a proper install and setup of imGUI for MacOS using GLFW and OpenGL3 within VSCode environment. 

1. brew install glfw 

2. Create imgui folder and copy main .cpp and .h files from imGUI root directory (imgui.cpp, imgui.h, etc)

3. Create backends folder and copy glfw.cpp/.h and opengl3 files from imgui source dir. 

4. Adjust make file to link appropriate paths.

5. Run Make and then demo app

Reference: 
https://www.youtube.com/watch?v=MWtHJTxgozQ