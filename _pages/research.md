---
#layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


<!-- ## *Learning from Multi-modality Data* -->

## *Detection and diagnosis of breast cancer in mammography*

> Identifying malignant masses in mammography images before a biopsy remains a challenging task for radiologists. In particular, our study sample intentionally excluded lesions with clear and distinct features that are easily identifiable by radiologists and have already been used as a basis for determining suspicious cases.We aim to establish a framework based on this study that can be used to explore additional clinical biomarkers and risk assessment criteria, helping radiologists identify suspicious lesions and improve the current diagnosis of breast cancer in mammography.
> ### *Relevant Publications:*
> * <a href="https://arxiv.org/abs/2408.03761" target="_blank">Performance Assessment of Malignant Masses Detection from Diagnostic Mammography</a> [ISBI'24]

![Words](https://github.com/guanghao-sun/guanghao-sun.github.io/raw/master/images/pipeline_v3.png)

## *Quadrotor UAV*

> Experimental validation of a quadrotor drone. This design mainly consists of modules for flight control, MPU attitude control, power supply, motor drive, altitude measurement, barometric pressure measurement, GPS positioning, and remote sensing control. The core of the flight control system uses the STM32F411CE6 microcontroller. The power supply module employs the ME6211C33 and MP9943 for stable voltage regulation. Altitude measurement and orientation sensing are achieved using the BMP280 barometer and HMC5883L three-axis electronic compass. The AT7456E chip is used for analog video transmission for ground monitoring. The drone uses a PID algorithm to adjust its flight attitude for greater stability, and image information processing is carried out through binarization. The drone's stability was tested successfully, achieving precise control over its movements, including takeoff, hovering, and landing.

![Words](https://github.com/guanghao-sun/guanghao-sun.github.io/raw/master/images/Drone_main.png)

## *Tillering Recognition of Wheat Based on Adaptive Linear Spanning Network*

> Wheat is a major staple crop in China, accounting for 19-27% of the country's cultivated land area and is widely distributed across the nation. The yield of wheat is closely related to the number of spikes per unit area, which is determined by the effective tiller number during the wheat jointing stage. To achieve automation and intelligentization in wheat breeding technology and address the challenge of accurately calculating wheat tiller numbers, this study employs image analysis and processing through machine vision and neural networks to achieve automated counting of wheat tillers. The paper uses a convex hull algorithm based on the cosine theorem and convex defect detection to identify wheat tiller angles, thereby obtaining an accurate count of wheat tillers. Given the complexity of the field environment and the significant noise in the collected images, a skeletonization method based on a linear span network and a skeleton network refinement algorithm are applied for noise reduction, enabling skeleton detection and background segmentation of the collected wheat images and constructing a corresponding skeleton model that aligns with wheat morphology. Subsequently, convex hull algorithms and convex defect detection are used for tiller angle detection, yielding precise data. This proposed detection method significantly reduces the workload and difficulty of manual measurements and provides an efficient, accurate, and scientific data processing method for advancing wheat breeding technology.

![Words](https://github.com/guanghao-sun/guanghao-sun.github.io/raw/master/images/wheat.gif)

## *Non-contact object shape and size measurement*

> As the name suggests, non-contact measurement involves measuring without direct contact between the measuring device and the object being measured. Instead, specific measurements are obtained through other means, offering distinct advantages for certain special conditions. This method effectively combines image acquisition technology with microcontroller-based image processing. An imaging system captures the image of the object being measured, which is then transmitted to the microcontroller. The microcontroller processes and pre-processes the image, performs fitting calculations, and ultimately provides the measurement data. 
> The system is composed of four major modules: a main control module, a distance measurement module, an information acquisition module, and a motion module. The STM32F03ZET6 microcontroller is used as the main control chip. Information and data are collected through the coordination of a camera and a gimbal. The system utilizes the LAB color space and color difference calculation methods to identify the color of the object. It recognizes stereoscopic images based on pixel point collection, multi-module matching, and feature point detection. Finally, the STM32F03ZET6 microcontroller performs analysis and calculations to achieve non-contact measurement of object dimensions.

![Words](https://github.com/guanghao-sun/guanghao-sun.github.io/raw/master/images/non_contact.png)