# MPM Simulation & Voxels Rendering

![gpgpu free fall](images/gpgpu_free_fall_01250_1200x800.png)

This is the final project for the course, *General-Purpose GPU Programming* @ NTU CSIE.

We model and simulate fluid-like materials, such as snow and sand, using material point method. MPM is implemented in C++ & CUDA. And OpenGL is used for real-time result viewing. Besides, for high quality rendering, we use NVIDIA GVDB + OptiX Ray Tracing Engine.

### Overview

![Material point method overview](images/mpm_overview.png)

The material point method (MPM) is a numerical technique used to simulate the behavior of solids, liquids, gases, and any other continuum material. In the MPM, a continuum body is described by a number of small Lagrangian elements referred to as 'material points'. These material points are surrounded by a background mesh/grid that is used only to calculate gradient terms such as the deformation gradient. For more information, please go to [Material point method - Wikipedia](https://en.wikipedia.org/wiki/Material_point_method)

### Implementations

For more details about implementation, please go to our [Project Page](https://windqaq.github.io/MPM/)

### Dependencies

##### Required

- CUDA
- [OpenGL](https://learnopengl.com/)
- [GLFW](http://www.glfw.org/)
- [OpenGL Mathematics (GLM)](https://glm.g-truc.net/0.9.9/index.html)

The following libraries has been put into this repository,

- [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page)
- [svd3](https://github.com/ericjang/svd3)
- [stb_image](https://github.com/nothings/stb)
- [glad](https://github.com/Dav1dde/glad)

##### Optional

For high quality rendering as screenshots,

- [GVDB-Voxels](https://github.com/NVIDIA/gvdb-voxels)
- [NVIDIA OptiX](https://developer.nvidia.com/optix)

To generate videos from saved rendered frames,

- [FFmpeg](https://www.ffmpeg.org)

### How to Build

### How to Run

### Screenshots

##### Letters falling scene

![gpgpu free fall crashed completely](images/gpgpu_free_fall_04000_800x600.png)

##### Two snow balls crashed each other

![two snow balls crashed each other](images/two_snow_balls.png)

### References

##### Papers

- [Multi-species simulation of porous sand and water mixtures](https://www.math.ucla.edu/~jteran/papers/PGKFTJM17.pdf)
- [A material point method for snow simulation](https://www.math.ucla.edu/~jteran/papers/SSCTS13.pdf)

##### Other Implementations

- [Azmisov - snow](https://github.com/Azmisov/snow)
- [JAGJ10 - Snow](https://github.com/JAGJ10/Snow)
- [utilForever - SnowSimulation](https://github.com/utilForever/SnowSimulation)

### Contact

Issues and pull requests are welcomed! Feel free to contact project owner [Tzu-Wei Sung](mailto:windqaq@gmail.com), or contributors [Yist Lin](mailto:yishen992@gmail.com) and [Rikiu Chen](mailto:jcly.rikiu@gmail.com).
