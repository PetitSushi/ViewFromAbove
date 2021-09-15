# A View From Above: Predicting car park occupancy rates from satellite images with a deep learning model

This repository gathers parts of a my work towards my MSc Research Project and Dissertation. It includes:
 - The satellite images I have collected from Google Earth
 - The JavaScript code used to access the satellite imagery on Google Earth Engine
 - The notebook which applies a deep learning algorithm, YOLOv4, for vehicle detection, and produces the results for my dissertation. It constitutes the main component of the methodological contribution I propose as part of this research project. 

Supervisor: Dr. Justin Van Dijk, University College London

In partnership with: Sainsbury's Ltd

Abstract: Satellite imagery’s resolution has increased so much in the last couple of decades that it has become a new data source for the extraction of small-scale objects, such as vehicles. Only a few studies have focused on vehicle detection using high-resolution satellite images. However, the application of this technology could be useful for traffic flow management, parking capacity monitoring, and in transport planning within the wider and rising smart cities and smart mobilities agenda. 
The study’s main objective is to devise a method, and specifically build an analytical tool, that enables the extraction of vehicle features from satellite images and estimates car parks’ occupancy rates. It seeks to contribute to the understanding of supermarket car parks’ occupancy rates, in order to generate market insight for the retail sector. This paper describes a complete processing and analytical pipeline in which raw satellite images are collected, transformed, and finally analysed for vehicle presence by means of a pre-trained deep learning algorithm, YOLOv4, that detects and localises the target features. A car park image base library was built collecting 110 high-resolution satellite images at 19 Sainsbury’s store locations from Google Earth, as a test site for the proposed approach. Strategies to enhance the model’s performance were explored. The vehicle detection results were then used to estimate each car park’s level of occupancy. Experimental results indicate that the methodology is theoretically sound, but the model’s performance on the input data is ambivalent. The number of detections made by the model explains 10.8% of vehicles observed in the car parks. The study’s findings highlight the high potential and the complexities of using satellite imagery to extract small-scale features in set locations. The evaluation includes an in-depth reflection on the possible explanations for these results and suggests ways to mitigate them, providing a fertile ground for further research. Future studies could acquire images at a format that better suits the model or of a higher resolution, attempt to re-train the model, or implement a variety of image transformation and detection validation techniques.

Keywords: Satellite Imagery; Deep Learning; Artificial Intelligence; YOLO; Vehicle Detection; Parking Space Analysis.
