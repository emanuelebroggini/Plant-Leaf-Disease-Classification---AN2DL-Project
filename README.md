# Plant-Leaf-Disease-Classification---AN2DL-Project
This repository presents a deep learning project focused on classifying plant leaves as either healthy or unhealthy from a dataset of 5200 images. Each image has dimensions of 96x96x3 (height, width, color channels). It's the first of two projects regarding the course of Artificial Neural Networks and Deep Learning, Politecnico di Milano, 2023/2024. 

**Project Overview**


Plant diseases pose a significant threat to agriculture and food security. Early and accurate detection of these diseases can enable timely interventions, minimizing crop loss and supporting sustainable farming practices. This project explores various deep learning approaches to automate the identification of diseased plants, offering a scalable solution to a critical problem.

While we aimed for higher performance, this repository documents our journey, highlighting several promising models and the methodologies employed. It serves as a comprehensive overview of the different architectural considerations and experimental steps taken to tackle this classification challenge.

**Dataset**


The dataset consists of 5200 images of plant leaves, categorized into two classes:

- Healthy

- Unhealthy

All images are standardized to a resolution of 96x96 pixels with three color channels (RGB).

**Models and Approaches Explored**


We investigated various neural network architectures and techniques, including but not limited to:

- Convolutional Neural Networks (CNNs): Custom-built CNNs designed for image feature extraction.

- Transfer Learning: Leveraging pre-trained models on large datasets (e.g., ImageNet) to benefit from their learned features, even though we did not achieve the desired results, the approach was valid and explored.

- Data Augmentation: Techniques to artificially expand the dataset and improve model generalization.
