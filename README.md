# Real Time Face Filtering

Computer Vision & Pattern Recognition class project @ Koc University  

In this project, we create a real-time video filter that uses face detection, face
alignment algorithms, head pose estimation and 3D image rendering with high accuracy.
Face detection and face alignment algorithms outputs are used to determine the rotational and translational transform of head pose. We use the cascaded regression model.

[Watch Demo](https://drive.google.com/file/d/0Bx95ytMi2G46Tk9mdDVhelNwRUE/view?usp=sharing)  
[Read Project Report](https://goo.gl/pe8qvE)

Root Unity Project is the ‘COMP408/‘ folder.  
### Building Instructions
In the Source Folder run these commands:  

Create build folder  
$ mkdir build  

Enter in to build folder  
$ cd build

Enable SSE4 for speed  
$ cmake .. -DUSE_SSE4_INSTRUCTIONS=ON  

Enable AVX for speed  
$ cmake .. -DUSE_AVX_INSTRUCTIONS=ON  

Build executables  
$ cmake --build . --config Release  

### Running
In the Source Folder run these commands:  

Open unity app:  
$ open ./Demo.app/  

Wait and run project  
$ ./build/project

