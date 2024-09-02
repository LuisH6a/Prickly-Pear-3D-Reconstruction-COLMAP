# 3D Reconstruction of a Prickly Pear Using Structure from Motion with COLMAP

Prickle pear production in Mexico yields an annual
performance of 400 tons. However, current production practices
require significant manual effort and time, highlighting the need
for innovation in line with the new technological paradigm.
Generating 3D models of prickle pear could facilitate future
projects such as analysis, robotic simulations, machine design
or data acquisition. Thus, this repository has 
a group of 3D prickle pear models  un mesh format using the COLMAP software
with structure from motion techniques. All the elements used during the 3D reconstruction pipeline are explained in the next figure.


![Imagen2](https://github.com/user-attachments/assets/f328d085-4efd-416c-8256-f432beb7d312)
> Fig. 1. 3D Reconstruction Pipeline

## Study cases

In this repository, the final results of two case studies are included. 
Both cases contain files in STL and OBJ formats so they can be used at 
the discretion of the interested party. The file name indicates the basic 
characteristics of the created model, which correspond to the number of 
images used and the quality employed. The quality equivalence is described 
in the following table.

#### Image quality 
                    
Quality       | Pixels
------------- | -------------
low           | 1000x748
medium        | 1600x1197 
high          | 2400x1795 


The used setup consists of a base, a reference angle sheet, a camera support,
a white background, and a rigid wire. The system was designed to ensure that the
sample could only present one point of support, thereby allowing it to obtain the
maximum amount of information from it. Two case studies with different conditions 
are presented, the main difference being the position of the camera for image acquisition. 
The first case study corresponds to a first test with minimal control of the variables
of the image acquisition environment. The conditions of each case are described below.

#### Case 1 Parameters
- Xiaomi M2003J15SC camera, the F point, exposure time, ISO and focal length are variables.
- Camera in vertical position fixed at variable distacnce from the camera's axis of rotation.
- Constant lighting and background with minimal noise.
- Photographs taken on the side of the sample and with a small angle of inclination.

![obj1](https://github.com/user-attachments/assets/f52dc176-c54d-4be6-a710-8cec9be7223e)
> Fig. 2. Clean 3D prickle pear models in OBJ format, case 1

![stl1](https://github.com/user-attachments/assets/fad0077a-b78f-4139-91f1-0ec8a746c631)
> Fig. 3. Clean 3D prickle pear models in STL format, case 1




#### Case 2 Parameters
- Xiaomi M2003J15SC camera, F point f/1.8, exposure time 1/15s, ISO-160 speed, focal length 5mm, without flash.
- Camera in vertical position fixed at 175mm from the camera's axis of rotation.
- Constant lighting and background with minimal noise.
- Photographs taken only on the side of the sample.
- The sample rotates at a maximum angle of 90° for the set of 4 images and at a 
minimum angle of 5.625° for the set of 64 images, in order to make use of a single database 
of photographs taken of the sample.


![obj2](https://github.com/user-attachments/assets/62637175-7a74-46c7-ada1-2961f3b3b2c3)
> Fig. 4. Clean 3D prickle pear models in OBJ format, case 2

![stl2](https://github.com/user-attachments/assets/854f77e7-cbec-461e-8e80-1b27785944a8)
> Fig. 5. Clean 3D prickle pear models in STL format, case 2
