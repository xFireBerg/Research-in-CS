# Research in Computer Science (CS)
**The papers in this repository are summaries of the published papers I studied for my Research in CS course in the Fall Term of 2019-2020.
The subject matter of all the papers is roughly about using Computer Vision techniques to detect and classify road signs with different approaches.
It would probably be apt to provide links to the original papers here with the respective abstracts.**

### Paper 1 [**Detection of Occluded Road Signs on Autonomous Driving Vehicles**](https://ieeexplore.ieee.org/document/8784797)  
**Abstract:** *Autonomous driving vehicle relies heavily on its perception system to sense surrounding environments and make driving decisions. One important task on autonomous driving vehicles is to correctly recognize different traffic signs. However, the traffic signs in the wild can be in various conditions, e.g., occluded, deteriorated, or vandalized, and not all of them are recognizable. In this work, we propose a novel system that leverages the perception system on autonomous vehicle to identify occluded road signs in real time. Based on transfer learning, we propose the occluded sign classification network (OSCN) that is able to achieve a precision of 96.34% on a real-world dataset.*  
[Summary](../master/Paper1.pdf)    

---

### Paper 2 [**Road Sign Recognition System for Autonomous Vehicle using Raspberry Pi**](https://ieeexplore.ieee.org/document/8728463)  
**Abstract:** *Road sign recognition is one of the important tasks of intelligent transportation systems (ITS). The project aims at implementation of road sign detection and control of an autonomous vehicle using Haar Cascade Classifier algorithm. In this proposed work, the system automatically detects the road signs, controls the vehicle and command certain actions. The system consists of Raspberry Pi 3 processor and web camera which automatically captures the video data and converts them into number of frames which are processed by the proposed algorithm in OpenCV to detect the road sign and control the vehicle. Based on the detected sign, the vehicle is controlled by two DC motors interfaced with Raspberry Pi. The experimental results for Peak Signal to Noise Ratio (PSNR) and Minimum Mean Square Error indicate the proposed system gives more accurate results with higher PSNR value compared to Hough Transformation. The performance metrics of the algorithm implemented in ARM processor is much better compared to the results obtained using MATLAB software.*  
[Summary](../master/Paper2.pdf)

---

### Paper 3 [**From Synthetic Images Towards Detectors of Real Objects: A Case Study on Road Sign Detection**](https://www.researchgate.net/publication/333417591_From_Synthetic_Images_Towards_Detectors_of_Real_Objects_A_Case_Study_on_Road_Sign_Detection)  
**Abstract:** *Large amounts of suitably marked images are required to feed a learning algorithm when building a detector. The process of collecting images and then marking locations of target objects in them is arduous. One could potentially speed up this process if real images for a given application were replaced by images generated synthetically, and coordinates of targets were simply imposed, rather then discovered manually. Despite the appeal of such an automatization, questions arise regarding the usefulness of systems built this way in real operating conditions. In particular, the obvious violation of i.i.d. principle might result in higher error rates at the testing stage.*  
[Summary](../master/Paper3.pdf)

---

### Paper 4 [**Small Traffic Sign Detection and Recognition in High-Resolution Images**](https://www.researchgate.net/publication/333863107_Small_Traffic_Sign_Detection_and_Recognition_in_High-Resolution_Images)  
**Abstract:** *Traffic sign detection and recognition is a research hotspot in the computer vision and intelligent transportation systems fields. It plays an important role in driver-assistance systems and driverless operation. Detecting signs, especially small ones, remains challenging under a variety of road traffic conditions. In this manuscript, we propose an end-to-end deep learning model for detecting and recognizing traffic signs in high-resolution images. The model consists of basic feature extraction and multi-task learning. In the first part, a network with fewer parameters is proposed, and an effective feature fusion strategy is adopted to gain a more distinct representation. In the second part, multi-task learning is conducted on different hierarchical layers by considering the difference between the detection and classification tasks. The detection results on two newly published traffic sign benchmarks (Tsinghua-Tencent 100K and CTSD) demonstrate the robustness and superiority of our model.*  
[Summary](../master/Paper4.pdf)

---

### Paper 5 [**Traffic sign detection method based on Faster R-CNN**](https://www.researchgate.net/publication/331901926_Traffic_sign_detection_method_based_on_Faster_R-CNN)  
**Abstract:** *Traffic sign detection is the pivotal technology of the traffic sign recognition system. In this article, a traffic sign detection method comes up based on Faster R-CNN deep learning framework. In this method, a convolution neural network is devoted to extract traffic sign image features automatically, and the extracted convolution feature map is sent into a Region Proposal Network (RPN) for foreground objects filtration and regression of bounding boxes. Then the proposed regions are mapped to the feature map, and the fixed-size proposal boxes via Region of Interest pooling layer (RoI). After that, we use the classification network to perform specific classification tasks and further compute the bounding box regression. The experiments performs on the German Traffic Sign Detection Benchmark (GTSDB) and the experimental results show that the method has effectiveness and robustness to different light, block, and motion.*  
[Summary](../master/Paper5.pdf)
