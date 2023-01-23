# Domain Randomization for Visual sim-to-real Object Pose Estimation 

The project develops a synthetic dataset using Domain Randomization (DR) technique for industrial parts used in diesel engine assembly. Modificiations are done in the physical dynamics in the form of textures, colours, background and lighting. 

The work has been completed as part of Masters Thesis in Robotics and Artificial Intelligence at Tampere University (2022). 

## Requirements

The work has been implmeneted using:

* Ubuntu 20.04 and ROS Noetic
* Blender 3.1.0
* Ignition Gazebo 6 (Fortress version)
* Python 3.8
* Detectron2 v0.6 (CUDA 10.2)

## Model files

The model files for the objects can be accessed from the Google Drive: \
https://drive.google.com/drive/folders/1LwW7lkFrzrbW3L-idtGfOjQ4Fy4-pFRA?usp=share_link

## Model weights and output files
The model weights are based on COCO baselines and can be accessed from: \  
https://drive.google.com/drive/folders/183EaLuIK6e_3CLihyE5DaHDeGd0sRItd?usp=sharing

The output files can be accessed from: \
https://drive.google.com/drive/folders/12ARCajxJ98ygafsnn0XrxmsUtummIpau?usp=sharing

## Original Dataset

The original CAD files for the common rail and fuel lines.
![Dataset 1](https://user-images.githubusercontent.com/84769093/166892994-880265d4-52c2-42a7-832d-5f8b2f543033.png)

## Metallic Textures

Metallic textures applied using PBR method in Blender and exported to Gazebo for final dataset.

![image_0000246](https://user-images.githubusercontent.com/84769093/190931445-f0aa959b-f47e-4245-ac57-070ca17cefa7.png)

![image_0000206](https://user-images.githubusercontent.com/84769093/190931454-a3ac267f-6de8-4fef-9de7-f2bab9577280.png)

## Random Textures and Colours
A set of random textures and colours were also applied on the objects. 

![Dataset 3](https://user-images.githubusercontent.com/84769093/174090219-ac120f86-bab4-40bf-80bf-1d52f7ac8e1b.png)

![Dataset 4](https://user-images.githubusercontent.com/84769093/174090307-e3e6e12b-c18f-4751-a9eb-af043a281522.png)

![fuel_lava](https://user-images.githubusercontent.com/84769093/171748532-fef1bb2f-74aa-4b52-89aa-bc1d16989582.png)

![Screenshot from 2022-06-02 17-25-04](https://user-images.githubusercontent.com/84769093/171748639-dc8e1eb2-d605-4393-9032-f31bdcd206cd.png)

![Coloured objects](https://user-images.githubusercontent.com/84769093/213942527-c69e0935-3f1b-4c1c-8b11-bc079f1d35a1.png)


## Lighting conditions
![Dataset 3](https://user-images.githubusercontent.com/84769093/166893185-87f25729-63c4-4bd4-986a-742190e75297.png)

