Project 0 Getting Started
====================

**University of Pennsylvania, CIS 565: GPU Programming and Architecture, Project 0**

* DI LU
  * LinkedIn: https://www.linkedin.com/in/di-lu-0503251a2/
* Tested on: Windows 11, i7-12700H @ 2.30GHz 32GB, NVIDIA GeForce RTX 3050 Ti

Project 0 Results
====================
### 1. Modify the CUDA Project and Take a Screenshot
![](images/DiResult2.png)
### 2. NVIDIA NSight System Analysis
![](images/NSight.png)
### 3. Nsight Debugging
![](images/warp2.png)
### 4. WebGL Results
![](images/webgl.png)
### 5. DirectX
Unmodified Triangle with DXR
![](images/tri.png)
Modified triangle with DXR
![](images/triSolid.png)

Project 0 Comments
=====================
On windows 11 I experienced an issue where switching to NVIDIA GPU will cause the Direct X triangle application to hit an unhandled exception error. Chang Liu scouted these helpful links for WAR:
https://stackoverflow.com/questions/69805245/directx-12-application-is-crashing-in-windows-11
https://github.com/walbourn/directx-vs-templates/commit/2b34dcf9ac764153699058cdc9d4dbc4e837224c
