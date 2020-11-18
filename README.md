# Projects-accomplished-
This repository contains information pertaining to the list of projects accomplished. These projects are basically research projects carried out by me and my team of students and faculties covering the domains like Deep Learning, Internet Of Things, Information Security, Image Processing.


# List Of Projects 
1. [Electricity theft detection](https://github.com/sannidhan/Projects-accomplished-/blob/main/README.md#electricity-theft-detection)
2. [Sketch-to-photo genearation using GAN](https://github.com/sannidhan/Projects-accomplished-/blob/main/README.md#Sketch-to-photo-generation-using-GAN)
3. [Assessment of Image Enhancement Techniques for Photo Sketch Matching](https://github.com/sannidhan/Projects-accomplished-/blob/main/README.md#Assessment-of-Image-Enhancement-Techniques-for-Photo-Sketch-Matching)

Electricity theft detection
-------------------------------------
**Features of the application** - For the past few years we have been facing a great electricity crisis since the demand of electricity is more than the production. Hence it is very important to manage electricity efficiently. In this regard one of the major challenges in electricity management is misuse of the power consumption due to electricity theft in public area. In this paper we propose a technique that detects the electricity theft by remotely monitoring the electricity meter readings to see whether it is within the specified threshold value and thus minimizing the misuse of electric power consumption in public areas. It also aims in the reduction of manual workload by tracking the data automatically. The paper mainly focuses on the implementation of the concept using Internet of Things (IoT) as the underlying framework to achieve real time monitoring through Raspberry pi board.

**Technologies Used**
1. Python
2. IoT
3. MQTT

**Conclusion and Future Scope** - Our system can be used to monitor power consumption in  public  places  using  an  IoT  board  (raspberry  pi)  as  the underlying  framework  which  acts  as  an  interface  between  the energy meter and the remotely placed system.  Collection of data from the energy meter in the form of pulses and sent to GPIO pin of raspberry pi which is processed continuously by the system and the  processed  data  is  stored  in  the  database  for  the  later inspections. Calculation of threshold value based on test cases and if the meter reading value exceeds the threshold value it shows variation in graph and also sends notification to the concerned authority. This system also reduces lot of work load of power station officials. As  a  future  work,  following  features  can  be incorporated to the implemented system: 1. wireless connection could be established between the energy meter and Raspberry Pi. 2. A remote monitoring of the switch could be implemented so that  the  required  appliances  could  be  controlled  at  the  station when there is a threat of theft. 3. The system could be made still better by generating an automated electricity bill. 4. This system can also be made to promote a prepaid electricity system based on  the  continuous  power  monitoring.  5.  The  system  could  be made to work offline through some better implications.  

**Paper Link** - https://ieeexplore.ieee.org/abstract/document/8455088/


Sketch-to-photo generation using GAN
--------------------------------------
**Features of the application** - 
1. Generated photo from a sketch, using a combination of CNN and cGAN.
2. Implemented a dual application of deep learning to generate sketches and photos.
3. Quality of sketch is an important factor in generating a photo of better quality.
4. Sketches generated through CNN attained more similarity index value.

One of the most significant and widely used methods for identifying a culprit in the field of forensic science is generating a sketch of the suspect from descriptions given by an eyewitness to the crime. However, there is a high level of uncertainty in recognizing an individual solely from a sketch. Recognition of sketches based on photos of an individual is non-trivial, as there are differences between the domain features of a sketch and a photo. To streamline this process, this article presents a methodology for generating a colored photo from a sketch, which can then be used for identification using a variety of classification techniques. Implementation of the proposed method involves a trained Convolution Neural Network for sketch generation paired with a conditional Generative Adversarial Network's pix2pix model for color photo generation. Experimental results of the work are validated using standard datasets, and the proposed model achieved a minimum average rate of 65% similarity index value on all employed datasets with a training efficiency of more than 98% in every epoch level.

**Technologies Used**
1. Pyhton
2. Keras
3. Generative Adversarial Networks (GAN)
4. Convolutional Neural Networks (CNN)

**Conclusion and Future Scope** - In this study, we attained our original objective of generating a colored photo image from a sketch input, using a combination of the CNN and cGAN pix2pix models. Significantly, this technique improves the accuracy of generated sketches and color photos. Through this we have further validated the dual application of deep learning to generate both sketches and photo images. Comparing the maximum average rate of similarity index value of 65% vs 61.5%. This confirms that sketches generated through CNN plays an important role in generating photos of better quality. This depicts the accuracy and loss percentage of training cGAN for up to 400 epochs, and the achieved results confirm that we have achieved a minimum accuracy of 97.85% and a maximum loss of 2.15% for 400 epochs on all the trained datasets. Our work was implemented and evaluated in Python, and open source programming language. One potential drawback of the proposal is that training of viewed sketches requires the application of image pre-processors.

**Paper Link** - https://www.sciencedirect.com/science/article/pii/S0167865519302831

Assessment of Image Enhancement Techniques for Photo Sketch Matching
-------------------------------------

