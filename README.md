# Deep Learning Model and Knowledge Graph for Re-Identification of Graphic Assets in Videos

## Overview

This repository contains the final reports, code, and Jupyter notebook used for the project "Deep Learning and Knowledge Graph for Re-Identification (ReId) of Graphic Assets in Videos," developed as part of the 2023/2024 Pi² project at ESILV.

The goal of this project is to compare traditional deep learning methods with a novel approach combining computer vision techniques and graph theory (Knowledge Graph, Graph Embedding, Graph Mining) for detecting and re-identifying individuals across images captured by one or more cameras. This task involves tracking people using features such as appearance, body shape, position, and clothing across multiple frames in video sequences.

## Team Information

Team Number: 283
Project Partner: Pierre Lefebvre, Nicolas Travers, Ahmed Azough
Team Members:
- Joalie Cornelie
- Louis-Melchior Giraud
- Louis Martyr
- Raphaël Michon
- Emrys Meziani
- Malo Leroy
  
# Project Structure

The project was conducted in several key stages:

1. Literature Review: A comprehensive study of the state-of-the-art in ReId, with a focus on existing models, datasets, and evaluation metrics.
2. Dataset Preparation: The selection, cleaning, and preprocessing of surveillance datasets (CAMPUS, PRW) to prepare for model training.
3. Model Training: Developing and training the ReId model using TensorFlow, following initial experiments with PyTorch. The model achieved an accuracy of 0.92 on test datasets.
4. Tracker Development: Extending the ReId model to integrate into a person tracking system using learned weights to detect and re-identify individuals in real-time video feeds.
   
# Repository Contents

- Reports: Documentation outlining the project milestones, literature review, dataset analysis, and final results.
- Notebook: The final Jupyter notebook used for model training and experimentation.
- Scripts: Python scripts used for data preprocessing, training the model, and testing the results.

# How to Use

1. Clone the repository:
```
git clone https://github.com/your-username/reid-graphic-assets.git
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Run the Jupyter notebook for model training and analysis.

# Results

- The final model achieved a high accuracy of 0.92, with successful re-identification across challenging conditions.
- The person tracker system was developed as an extension, using the model weights for real-time applications.
Future Work

# The project can be further improved by:

- Expanding the dataset to include more diverse surveillance footage.
- Optimizing the tracking system for more efficient real-time performance.
- Incorporating additional graph-based techniques to enhance re-identification accuracy.

# License

This project is licensed under the MIT License - see the LICENSE file for details.
