# Eid in Makkah – 2D OpenGL Graphics Scene

Computer Graphics (CS2206) project – Umm Al-Qura University, College of Computing.
An animated 2D story built with **C++ / OpenGL (GLUT)** showing how a family prepares for and celebrates Eid in Makkah, in four scenes with dialogue, textures and animation.

▶ Demo video: [`demo.mp4`](demo.mp4)

## Scenes

| Scene | Description |
|---|---|
| 1 | Room with a wardrobe, vanity table and a moving clock, with dialogue |
| 2 | Preparing for prayer: prayer mat, door and bookshelf textures, background people |
| 3 | Outdoor scene: sun, trees, street lines, background people and a basket of dates |
| 4 | Final scene about the meaning of Eid in Makkah, with a moving sun |

## Controls

| Input | Action |
|---|---|
| Left mouse click | Next scene (1 → 2 → 3 → 4 → 1) |
| `A` / `a` | Move the mother character left |
| `D` / `d` | Move the mother character right |
| `M` / `m` | Make the character jump |

## Build & Run (Windows, Visual Studio)

1. Create a new **Empty Project** in Visual Studio.
2. Install OpenGL/GLUT through NuGet: `Install-Package nupengl.core` (Package Manager Console).
3. Add `main.cpp` to the project.
4. Keep the `photos/` folder next to the executable (texture paths in the code are relative: `photos/xxx.bmp`).
5. Run with **Local Windows Debugger**.

## Files

- `main.cpp` – full source code
- `photos/` – `.bmp` textures (prayer mat, wooden door, shelf, wardrobe, etc.)
- `demo.mp4` – recorded demo

## Tech

C++, OpenGL, freeglut, BMP texture loading, timer-based animation.

## References

1. Toal, R. OpenGL examples. Loyola Marymount University. https://cs.lmu.edu/~ray/notes/openglexamples/
2. The freeglut Programming Consortium. API documentation. https://freeglut.sourceforge.net/docs/api.php
3. Suraj Sharma (2018). OpenGL / C++ 3D Tutorial 22 – Texture class [Video]. YouTube. https://www.youtube.com/watch?v=4tdy1izUv_Y
