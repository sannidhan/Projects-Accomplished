# Projects-accomplished-
This repository contains information pertaining to the list of projects accomplished. These projects are basically research projects carried out by me and my team of students and faculties covering the domains like Deep Learning, Internet Of Things, Information Security, Image Processing.


# List Of Projects 
1. [Electricity theft detection](https://github.com/sannidhan/Projects-accomplished-/blob/main/README.md#electricity-theft-detection)
2. [Sketch-to-photo genearation using GAN](https://github.com/sannidhan/Projects-accomplished-/blob/main/README.md#Sketch-to-photo-generation-using-GAN)
3. [Assessment of Image Enhancement Techniques for Photo Sketch Matching](https://github.com/sannidhan/Projects-accomplished-/blob/main/README.md#Assessment-of-Image-Enhancement-Techniques-for-Photo-Sketch-Matching)
4. [A Rapid Automated Process for Organizing Bacterial Cluster Segments Using Deep Neural Networks](https://github.com/sannidhan/Projects-accomplished-/blob/main/README.md#A-Rapid-Automated-Process-for-Organizing-Bacterial-Cluster-Segments-Using-Deep-Neural-Networks)

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
**Features of the application** - Image supported examination procedures are widely considered in the variety of fields. Typically, the image examination involves in the extracting the region of interest or features for the further investigation. In human detection system and also in criminal science, identification of the correct person is essential for the authentication requirements. In these applications, usually, the sketch drawn by an expert or a computer is matched against the digital photographs available in the criminal or the public database. During this examination, essential facial features are extracted from the sketch and digital photography is compared to identify the percentage of fit. The proposed work in this paper aims to examine the existing image enhancement and identification procedures existing in the literature. After creating the essential sketch for a person, a comparative analysis against the digital photo (Gray / RGB scale) of the person is performed, and the image similarity measures, such as PSNR, MSE, and SSIM are computed. In this paper, the benchmark datasets, like CUHK and PRIP-HDC are considered for the examination, and the empirical trial is achieved with the help of Matlab software.

**Technologies Used**
1. MATLAB
2. Image Processing

**Conclusion and Future Scope** - In forensic science, during the composite sketch and photo matching process efficient procedure is to be followed to improve the detection accuracy. The proposed research work aims to compare various enhancement procedures, that can be implemented to pre-process the test pictures to improve the detection accuracy. In this paper, most common pre-processing procedures, such as adapthisteq, histeq, imadjust and unsharp-masking are adopted to enhance the sketch as well as the original photo. During the examination, the public face datasets, such as CUHK and PRIP-HDC are considered for the analysis. All the implementations is accomplished through the standard Matlab tool. The experimental work of this investigation upholds that for both the datasets, the unsharp-masking produces improved detection rate in comparison to the substitute methods.  

**Paper Link** - https://ieeexplore.ieee.org/abstract/document/9007980

A Rapid Automated Process for Organizing Bacterial Cluster Segments Using Deep Neural Networks
-------------------------------------
**Features of the application** - The acknowledgement of the bacterial species is essential since the organic information on microorganisms is critical in medication, veterinary science, organic chemistry, nourishment industry or cultivation. A large portion of the organisms have a positive effect on everyday issues; they can be an explanation of numerous illnesses. Along these lines, automating the procedure of acknowledgement can discover application in restorative counteractive action and treatment sciences. One of the most significant highlights that can be perceived in the pictures is the state of a microscopic organisms cell. In this research article, the indispensable shapes like round and hollow, circular and winding are categorized using deep learning approach. Nevertheless, the procedure of perceiving microbes is dependent on the shape would be a troublesome one because numerous bacteria share primarily the same forms. Secondly, the most separating highlight is the shape and the size of the microscopic organisms. Overall if it was not an automated approach, then it is difficult to classify the bacterial colonies. Experimental outcomes of the proposed methodology are carried out using three different models, namely VGG. Mobile Net and Inception out of which VGG has shown remarkable progress of 99%.

**Technologies Used**
1. CNN
2. Image Processing and Conversion
3. Transfer Learning

**Conclusion and Future Scope** - Bacteria and their species have been in this earth for millions of years. They will also continue living for another million years to come. Humans have found the applications of bacteria very recently and learned to classify them. Unfortunately, the classification methodologies are too primitive and consume too much time and effort. We have proposed an innovative effort to classify species of bacteria using deep learning and compared our results with three standard models of deep learning. It was found out that SVGG proved to be the best model for genera classification. We can further improvise our work by developing a feedback system which can further allow identifying newer species of bacteria by using reinforcement learning. Our idea also can be further used to identify viruses and other single-celled organisms.

**Paper Link** - https://ieeexplore.ieee.org/abstract/document/9214173



