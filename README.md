# RayTracing

Based on @GLADWalnut[https://github.com/chikvi/GLADWalnut].
frame rendering time: 9-10 ms

## Installation Guide
# Windows
1. Clone the repo. Update the submodules.
2. run scripts/Scripts.bat to generate .sln project

# Linux
1. git clone --recursive https://github.com/chikvi/RayTracing
2. cd RayTracing
3. mkdir build && cd build
4. cmake -DCMAKE_BUILD_TYPE=(Debug/Release) ..
5. make
6. cd Raytracing
7. ./raytracing_app
