# Introducation

The implementation of pbr based on OpenGL

# Feature

- image-based lighting
- gui based on imgui

# Dependence

- OpenGL
- glfw
- glew
- glm
- stb_image
- imgui

# Build

```zsh
brew install glfw glew glm
mkdir build
cd build
cmake ..
make
cd ..
```

# Run
```c++
cd ./bin
./graphics
```
The *option* key can be used to hide or show the mouse, *WASD* can move the camera position when the mouse is hidden, the mouse controls the camera orientation, and UI Settings can be made when the mouse is displayed.

# Result
![](./img/res.png)
![](./img/res1.png)
