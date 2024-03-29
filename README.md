# WEEE-Disassembly-Screw-Dataset
<!-- ## Paper Title: **Vision-Enhanced System for Human-Robot Disassembly Factory Cells: Introducing A New Screw Dataset**

## Conference: **2022 4th International Conference on Robotics and Computer Vision (ICRCV 2022)**
 -->
<!-- #### General: -->
<!-- The proposed screw dataset contains 945 images and over 4,000 annotated screw instances suitable for three separate computer vision tasks, namely *instance segmentation*, *object detection*, and *semantic segmentation! -->

The introduced screw dataset comprises a wide variety of
device types, including damaged and deformable devices, as
would be expected in a realistic disassembly scenario. Data
were recorded under various lighting conditions, rotations,
and device movements were employed. Recordings were made
using a multi-camera configuration to obtain more informative
views. Images captured from a close distance with a camera
mounted on a screwdriver and a hand-held camera from
various angles. Additionally, images from a greater distance
were captured using cameras in fixed positions at a maximum
distance of 90 cm.

**The screw dataset consists of 945 high definition 1280x720
images, 4, 414 screw instances and 4.7 screws per image.** Blur estimation was employed to exclude
blurry frames from the annotation process. **The dataset includes annotated data in COCO format for three different computer vision tasks: instance segmentation, object
recognition, and semantic segmentation.** From these images, 52.7% were recorded in a laboratory
environment and 47.3% recorded in WEEE recycling plants.
In the training, validation, and test sets, there are 765, 90 and
90 fully annotated frames, respectively


#### **Dataset Statistics:**

- 945 images 

- Total Screw instances 4414

- Avg = 5 Screws/image

- Min screws/image = 1 | Max screws/image = 16

![3](https://user-images.githubusercontent.com/56552010/185942935-6936e4a6-6440-4abd-8e87-51afef52451f.png)


- Annotations for 3 Computer Vision Tasks : Object detection(COCO format), Instance segmentation(COCO format), Semantic segmentation

- Dataset Split --> 0.8/0.1/0.1 --> 765/90/90

- High Definition (HD) Images 1280x720 --> 720P-HD

- Damaged devices, Deformable devices, Big variability between devices

- Multiple-camera setup resulted in more informative views, recordings from near and far distances and with different angle shots, cameras in fixed positions, different lighting conditions, rotations and movement of devices, camera mount on the Screwdriver, Hand-held camera. 


- Three different types of WEEE devices : PC Towers, Microwave Ovens, Flat Panel Displays [35% - 330 images/ 41% - 387 images/ 24% - 228 images]
<!-- 
![1](https://user-images.githubusercontent.com/56552010/185942472-5889dfe8-ace4-4a58-8540-2df4bf427028.png) -->

![4](https://user-images.githubusercontent.com/56552010/185942950-d76e3e3d-9b6a-49ef-bd4d-d6600e12ae2e.png)

- Industrial Environment images : 390 --> 41.3% Laboratory Environment : 555 --> 58.7%

<!-- ![2](https://user-images.githubusercontent.com/56552010/185942492-d8d18322-569d-40ca-a058-7284aec49b51.png) -->

![5](https://user-images.githubusercontent.com/56552010/185942962-88461723-acf0-48b5-8365-b33f5200ae42.png)


<br />

#### *Examples from the dataset:*

![new1a(2)](https://user-images.githubusercontent.com/56552010/185946991-8a428885-651b-4eef-a8e1-d1ec108e4629.png)
Figure 1: Screw examples for different WEEE devices.

![image11a(1a)(2)](https://user-images.githubusercontent.com/56552010/185946985-86622ce3-fa8d-4cc3-9760-170f7da0ed01.png)
Figure 2: Screw annotations for Semantic Segmentation, Object Detection and Instance Segmentation respectively.

<!-- #### The dataset may be abbreviated as **WDSD**: (W)EEE (D)isassembly (S)crew (D)ataset ! -->

<br />

#### The dataset might be referred to as **WDSD**: (W)EEE (D)isassembly (S)crew (D)ataset !


#### **WDSD Dataset** can be downloaded through this link: 
https://vcl.iti.gr/dataset/weee-disassembly-screw-dataset/
<!-- (After the conference September 25-27 2022, the URL will be made available.) -->
 <!-- https://drive.google.com/drive/folders/1B8KB3p5568DMT5Uh91zOj3JInj8Q5RiH?usp=sharing  -->

#### Key Publication:
Georgios Kalitsios, Lazaros Lazaridis, Athanasios Psaltis, Apostolos Axenopoulos, Petros Daras, "Vision-Enhanced System for Human-Robot Disassembly Factory Cells: Introducing A New Screw Dataset", 2022 4th International Conference on Robotics and Computer Vision (ICRCV 2022).
 <!-- #### **WDSD Dataset** can be downloaded through this link:
(After the conference September 25-27 2022, the URL will be made available.)  -->
