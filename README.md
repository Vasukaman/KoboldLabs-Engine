# 🐺 KoboldLabs Engine

An OpenGL-based 3D game engine featuring a custom physics system, an object-action architecture, and Lua scripting. Developed as a final project for my studies at **Fanshawe College**.

-----

## About The Project

KoboldLabs Engine is a 3D game engine built from the ground up in C++ and OpenGL. It was developed to demonstrate a comprehensive understanding of modern engine architecture, rendering techniques, and physics simulation.

The project's core is its **Object-Action architecture**, a flexible system similar to component-based designs that allows for rapid development and extension. It's built to be robust, easy to use, and a powerful tool for creating interactive 3D experiences.

-----

## ✨ Core Features

### Rendering Engine

  * **Physically-Based Rendering (PBR)**: Implements an industry-standard PBR shading model for realistic materials, supporting ambient occlusion, roughness, metalness, and normal maps.
  * **Shell Texturing**: An efficient technique for rendering dense, dynamic grass with layered shells, creating depth and motion with minimal performance overhead.
  * **GPU-Instanced Particles**: A high-performance particle system that updates the GPU buffer directly, allowing for thousands of dynamic particles with different behaviors and settings.

### Physics System

  * **Hybrid Collision Detection**: A custom physics engine that uses **AABB** for efficient broad-phase filtering and precise **mesh-based collision** for narrow-phase resolution. This optimizes performance while ensuring accurate physical interactions.
  * **Deformable Soft-Body Physics**: A custom soft-body simulation using Verlet integration. It supports real-time interaction between soft bodies and rigid colliders, enabling realistic elasticity and deformation.

### Architecture & Scripting

  * **🧩 Object-Action Architecture**: A robust, easy-to-use system inspired by industry standards, facilitating rapid development and feature extension.
  * **Lua Scripting**: Integrated **Lua** for scripting game logic and keyframe animations, allowing for quick iteration without needing to recompile the C++ source.
  * **🎧 FMOD Audio Integration**: Leverages the powerful **FMOD** library for advanced audio processing, sound effects, and spatial sound.
  * **Custom Scene Management**: Features a custom save/load system using a lightweight, human-readable `.txt` format for streamlined scene data management.

-----

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

  * **Visual Studio 2019** or newer
  * **FMOD Core API**: Ensure the FMOD library is installed and linked correctly.

### Installation & Building

1.  Clone the repository:
    ```sh
    git clone https://github.com/Vasukaman/KoboldLabs-Engine.git
    ```
2.  Open the `KoboldLabs-Engine.sln` file in Visual Studio.
3.  Set the build configuration to **Release** and the platform to **x64**.
4.  Build the solution (F7 or `Build > Build Solution`). The executable will be generated in the `x64/Release` folder.

-----

## 🛠️ Built With

  * **C++**: Core engine language
  * **OpenGL**: Graphics rendering API
  * **GLAD**: OpenGL Loading Library
  * **GLFW**: Windowing and input management
  * **Assimp**: 3D model and asset loading
  * **Lua**: Scripting language for game logic
  * **FMOD**: Audio engine for sound processing

-----

## Acknowledgments

  * A special thanks to the professors and curriculum at **Fanshawe College** for providing the foundational knowledge required for this project.
  * HUGE THANKS to Acerola for making the best videos about GPU programming!
