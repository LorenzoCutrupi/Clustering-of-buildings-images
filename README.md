# CLUSTERING OF BUILDINGS IMAGES WITH ML TECHNIQUES

This project focuses on clustering buildings in images using machine learning techniques. The main objective is to group similar buildings together based on their visual characteristics. The pipeline consists of several steps, including preprocessing, object detection, feature extraction, and clustering.

## Project Overview
The project aims to automate the process of clustering buildings in images. By applying machine learning algorithms, we can analyze the visual features of buildings and group them based on their similarities. This can be useful for various applications, such as urban planning, real estate analysis, or city development.

The project pipeline consists of the following steps:

1. **Preprocessing:**
   - **Description:** The images are preprocessed to enhance their quality and reduce noise. This may involve resizing, normalizing, and enhancing the images to improve the accuracy of subsequent steps.

1. **Object Detection:**
   - **Description:** In this phase, the main building(s) in the images are detected. The output of this phase is a bounding box or a mask that represents the detected building(s).

1. **Feature Extraction:**
   - **Description:** After the buildings have been identified, meaningful features are extracted from them. This can be done using CNNs or autoencoders. CNNs capture high-level features from the building images, while autoencoders compress and decompress the images, extracting relevant features in the process. The choice of model and architecture depends on the project requirements and dataset.

1. **Clustering:**
   - **Description:** The extracted features are used to group similar buildings together through clustering algorithms. Common clustering algorithms, such as HDBScan and hierarchical clustering are applied to identify patterns and similarities in the features. Buildings are then assigned to different clusters based on these similarities.
