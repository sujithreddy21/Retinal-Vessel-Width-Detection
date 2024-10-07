
# Retinal Vessel Analysis Project

## Project Overview
This project focuses on analyzing retinal vessels using image processing techniques. It involves the segmentation, extraction, and analysis of retinal vasculature to evaluate vessel morphology, width, and structural characteristics. The study aims to provide insights into retinal vessel patterns, contributing to potential clinical applications and further research.

## Methodology

### 1. Dataset
The dataset consists of ground-truth segmented retinal images. These images include both normal and pathological retinal conditions, ensuring comprehensive analysis. The precise segmentation of retinal vessels ensures that the analysis is focused on vascular structures. Ground-truth images serve as benchmarks for validation.

### 2. Pre-processing
#### 2.1 Segmented Retinal Image
The input dataset contains segmented retinal images, where retinal vessels are isolated from surrounding structures. These serve as the foundation for further analysis.

![image](https://github.com/user-attachments/assets/e387b685-3fb3-4714-9332-b4e62774f6b6)


#### 2.2 Centerline Pixel Extraction
The next step involves extracting centerline pixels from the retinal images, identifying the central axis of the vessels, providing a clear and accurate representation of the vasculature.

![image](https://github.com/user-attachments/assets/8b75f0ea-d28a-4d08-a868-eb23c7718eae)


#### 2.3 Superimposing Retinal Vessel with Centerline
The centerline is superimposed onto the original fundus image, providing a visual overlay to clearly represent the identified retinal vessels.

![image](https://github.com/user-attachments/assets/43114958-d7bd-40a0-880e-828678a1eafa)


#### 2.4 Selection of Region of Interest (ROI)
A specific portion of the centerline images is selected for further analysis, focusing on the critical regions relevant to the exploration of vessel width.

![image](https://github.com/user-attachments/assets/0306ab84-0efd-4a0a-b0ab-d20856d69702)


#### 2.5 Junction Points Identification
Junction points, where vessels intersect, are identified and marked on the skeletonized retinal images. These intersections provide insights into the vascular network.

![image](https://github.com/user-attachments/assets/3a265796-5eee-476d-a725-8c270b3eb0d6)


#### 2.6 Highlighting Major Vessel and Small Vessel Filtering
Small vessels are filtered out, and only major vessels are highlighted in the analysis, improving accuracy for subsequent exploration.

![image](https://github.com/user-attachments/assets/392ffbd5-7ed1-4e6d-af46-c7d465bc0261)


#### 2.7 Longest Connected Component Extraction
The largest connected vessel in the segmented image is isolated, representing the most prominent structure for detailed analysis.

![image](https://github.com/user-attachments/assets/aab28468-ee0f-4470-9ede-815a1c5fd66c)


#### 2.8 Startpoint and Endpoint Localization
The starting and ending points of the skeletonized vessel are marked to visualize the orientation of the vessels.

![image](https://github.com/user-attachments/assets/ab361fd5-37cf-4249-a9de-2b6aa5dae6fc)


#### 2.9 Perpendicular Line Detection
Perpendicular lines are drawn at intervals along the vessel structure, providing reference points for detailed structural examination.

![image](https://github.com/user-attachments/assets/cf6849e7-cdbc-430f-82b2-0511718ea017)


#### 2.10 Intensity Profiles
Intensity profiles are generated along the vessel line to understand variations in pixel intensities, offering insights into structural features of the retinal vessels.

![image](https://github.com/user-attachments/assets/82c538bd-3e39-46c9-b29a-4752ee0ae221)


#### 2.11 Intersection of Perpendicular Lines with Vessel Edges
The intersections between perpendicular lines and vessel edges are analyzed, marking regions of potential structural significance within the retinal vessel network.

![image](https://github.com/user-attachments/assets/64e572cb-d525-4965-bc7d-2a379b30b194)


## Results
The project's primary results involve the calculation of vessel widths using Euclidean distance analysis. The distances between perpendicular line intersections with retinal vessel edges serve as a direct measure of vessel width. The mean Euclidean distance offers a quantitative measure of average vessel width, and these results are visualized for interpretability. The analysis contributes to a detailed understanding of retinal vessel dimensions, forming a foundation for clinical applications and further research in retinal image processing.


![image](https://github.com/user-attachments/assets/e8d2a648-ef2c-4c67-a4cf-ce4b1bd691f4)


## Conclusion
This project offers a comprehensive analysis of retinal vessel structures, focusing on quantifying vessel widths and exploring vascular morphology. The methodologies and results serve as a critical resource for advancing retinal image processing techniques and clinical research.
