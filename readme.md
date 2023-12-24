# RayTracingOW

Brief raytracing project to learn the basics.


## How to render

In order to render whats inside of main.cc:
1. You need to have g++ and Cmake installed. 
2. Create a build folder at the same level of src.
```shell
//At src level
cmake --build ./build
build/raytracinow > image.ppm
```
3. Then you will have to install a .ppm compatible image viewer. Toyviewer on mac or https://www.cs.rhodes.edu/welshc/COMP141_F16/ppmReader.html online.
