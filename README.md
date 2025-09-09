# KoboldLabs Engine
<img width="930" height="540" alt="image" src="https://github.com/user-attachments/assets/c255b3f2-8d9b-489f-88b6-bf780ceea290" />

[VIDEO SHOWCASE](https://www.youtube.com/embed/NRvo9QyOdjM?si=NG948dFNPzobmVjQ)

[SOFTBODY + THREADING VIDEO SHOWCASE](https://www.youtube.com/watch?v=FvAc_5-wjVY)

[ITCH.IO](https://vasuka.itch.io/koboldlabs-engine)

An OpenGL-based 3D game engine featuring a custom physics system, an object-action architecture, and Lua scripting. Developed as a final project for my studies at **Fanshawe College**.
![Kobold_Labs_Game_Engine_Showcase (2)](https://github.com/user-attachments/assets/e8237784-b8bf-4447-a40f-391c71958262)


-----

## About The Project

KoboldLabs Engine is a 3D game engine built from the ground up in C++ and OpenGL. It was developed to demonstrate a comprehensive understanding of modern engine architecture, rendering techniques, and physics simulation.

The project's core is its **Object-Action architecture**, a flexible system similar to component-based designs that allows for rapid development and extension. It's built to be robust, easy to use, and a powerful tool for creating interactive 3D experiences.
<img width="1920" height="973" alt="image" src="https://github.com/user-attachments/assets/88344031-0817-4624-afb4-a78774e32b76" />

![PBR WORKING!!!](https://github.com/user-attachments/assets/18bc0667-276f-403c-be01-bc513e0cc015)

![Grass Shells Move indep long small](https://github.com/user-attachments/assets/097aa5e0-fdbe-42a4-813a-a61c9ecb9ad8)

-----

## Core Features

<img width="794" height="421" alt="image" src="https://github.com/user-attachments/assets/419eb9c1-e965-48cf-971f-b1602156e78c" />

### Rendering Engine

  * **Physically-Based Rendering (PBR)**: Implements an industry-standard PBR shading model for realistic materials, supporting ambient occlusion, roughness, metalness, and normal maps.
  * **Shell Texturing**: An efficient technique for rendering dense, dynamic grass with layered shells, creating depth and motion with minimal performance overhead.
    ![Kobold_Labs_Game_Engine_Showcase](https://github.com/user-attachments/assets/a6b042a1-1815-41e7-b71a-197c62c2d670)

  * **GPU-Instanced Particles**: A high-performance particle system that updates the GPU buffer directly, allowing for thousands of dynamic particles with different behaviors and settings.
![Kobold_Labs_Game_Engine_Showcase](https://github.com/user-attachments/assets/9ac91d60-6860-4c07-b26a-61ee23154808)
![Kobold_Labs_Game_Engine_Showcase (1)](https://github.com/user-attachments/assets/f2ba1a12-365a-4134-ae5a-a381a14fe9af)

### Physics System

  * **Hybrid Collision Detection**: A custom physics engine that uses **AABB** for efficient broad-phase filtering and precise **mesh-based collision** for narrow-phase resolution. This optimizes performance while ensuring accurate physical interactions.
  * **Deformable Soft-Body Physics**: A custom soft-body simulation using Verlet integration. It supports real-time interaction between soft bodies and rigid colliders, enabling realistic elasticity and deformation.
![Kobold_Labs_Game_Engine_Showcase (4)](https://github.com/user-attachments/assets/cec395d1-2fef-437a-9980-20b80eed8486)

### Architecture & Scripting

  * **Object-Component Architecture**: A robust, easy-to-use system inspired by industry standards, facilitating rapid development and feature extension.
  * **Lua Scripting**: Integrated **Lua** for scripting game logic and keyframe animations, allowing for quick iteration without needing to recompile the C++ source.
  * **FMOD Audio Integration**: Leverages the powerful **FMOD** library for advanced audio processing, sound effects, and spatial sound.
  * **Custom Scene Management**: Features a custom save/load system using a lightweight, human-readable `.txt` format for streamlined scene data management.


-----

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

  * **Visual Studio 2019** or newer
  * **FMOD Core API**: Ensure the FMOD library is installed and linked correctly.


##  Built With

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
