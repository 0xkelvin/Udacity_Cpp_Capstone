# Udacity_Cpp_Capstone

Continue Updating ....

- System Architect: 
<img width="387" alt="image" src="https://user-images.githubusercontent.com/56182747/134177137-5c6e30a2-ccd6-463b-86aa-25b3abc8a4e8.png">
add current state, using the virtual CAN to simulate the CAN msg. Radars and Speaker are disable. 



- Requirements:
CMake >= 3.10
Qt 5
OpenCV >= 4.0.1
C++ 17 compiler
CUDA 10.x
TensorRT 5.1.5-1+cuda10.1, or - TensorRT 6.0.1.8+10.2. This project should work with TensorRT 5 and TensorRT 6. TensorRT 7 is not supported for now.

- Compile: 

cd <project directory>
 
mkdir build

cd build
  
cmake -DCUDA_INCLUDE_DIRS=/usr/local/cuda-10.2/include ..
  
make
  
- Setup virtual CAN (run once) : 
sudo bash setup_vcan.sh
  
- Run : 
 
cd build/bin
 
./OpenADAS
  
  
Video demo : https://www.youtube.com/watch?v=bziyGNgPx0o
 

TBD for ARAS version with system as below : 
<img width="955" alt="image" src="https://user-images.githubusercontent.com/56182747/134179487-70444f04-d2e4-4c23-bc45-20e619ba2607.png">

