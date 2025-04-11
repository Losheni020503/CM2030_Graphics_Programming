# 🎮 Interactive 3D Object Renderer – OpenGL Graphics Project

This project is an **interactive 3D rendering tool** developed using **OpenGL**. It allows users to visualize and manipulate 3D models in real time using keyboard and mouse input. The renderer supports advanced techniques like **Phong shading**, **texture mapping**, and interactive **camera control** for a visually immersive experience.

---

## ✨ Features

### 🌀 3D Rendering Capabilities
- Load and display 3D object models (e.g., `.obj`)
- Rotate, zoom, and pan models interactively
- Multiple camera modes (e.g., perspective & orthographic)

### 💡 Lighting & Shading
- Implemented **Phong shading** (ambient, diffuse, specular)
- Dynamic light source manipulation
- Surface normals and lighting reflection support

### 🖼️ Texture Mapping
- Applied **2D image textures** to 3D models
- Supports various image formats (e.g., PNG, BMP)
- Realistic surface appearance via texture coordinates

### 🧭 User Interaction
- Real-time control via keyboard/mouse
- GUI toggle for wireframe/solid mode
- Reset and model swap functionality

---

## 🧰 Tech Stack

| Component       | Tool/Library               |
|------------------|----------------------------|
| Language         | C++                        |
| Graphics API     | OpenGL (GLUT/GLFW/GLM)     |
| Shading Language | GLSL                       |
| Texture Loading  | SOIL / stb_image           |
| Interface        | GLUT/GLFW-based callbacks  |
| Platform         | Cross-platform (Linux, Windows, Mac) |

---

## 🧪 How to Run

### 🖥️ Requirements
- OpenGL 3.3+
- GLEW / GLAD
- GLFW / GLUT
- CMake / Make (for build)

### 🧱 Build & Run (Unix-like OS)

```bash
# Clone the repo
git clone https://github.com/yourusername/3d-object-renderer.git
cd 3d-object-renderer

# Build using CMake
mkdir build && cd build
cmake ..
make
```
## Run the executable
./3d_renderer
On Windows, open the project using Visual Studio with CMake support or use Code::Blocks configured with OpenGL libraries.

## 🧠 Learning Outcomes
Understood the rendering pipeline and programmable shaders

Implemented lighting models in GLSL

Gained experience with texture coordinate mapping and file parsing

Applied linear algebra concepts in 3D transformations

## 🔮 Future Improvements
Add normal/bump mapping for enhanced surface realism

Load animated .fbx or skeletal models

Integrate ImGui for better interface controls

VR/AR compatibility via OpenXR

## 👤 Author
- Losheni Meenakshi Sundaram
- Student at University of London , Singapore Institute of Management
- 📫 Email: losheni.ms@gmail.com

## 📄 License
This project is for academic and learning purposes only. Open to personal experimentation and modification.
