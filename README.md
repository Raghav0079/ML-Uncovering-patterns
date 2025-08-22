# ML: Uncovering Hidden Patterns in YouTube Trending Videos

**Unsupervised-ML** is a data science project that dives deep into unsupervised machine learning techniques—specifically clustering—using real-world YouTube video data. This project walks you through the entire machine learning workflow, from cleaning and preprocessing raw data to applying K-Means clustering, and finally visualizing insights that reveal hidden patterns in media content.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Key Objectives](#key-objectives)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Contributors](#contributors)
- [License](#license)

---

## Overview

This project leverages trending YouTube video data from Great Britain to demonstrate how unsupervised learning, particularly the K-Means clustering algorithm, can be employed to uncover hidden patterns. Whether you're a beginner eager to explore data preprocessing or someone looking to deepen your knowledge of clustering techniques, this repository offers a comprehensive, reproducible pipeline that bridges theoretical concepts with practical implementations.

---

## Dataset Description

The project utilizes the following datasets:

- **`GBvideos.csv`**  
  Contains raw data on trending YouTube videos in Great Britain. Details include video ID, title, channel, category, publish time, view count, likes, dislikes, and comments.
  
- **`compressed_data.csv.gz`**  
  A compressed (and potentially preprocessed) version of the dataset. This file is optimized for performance and storage, ensuring smoother exploration and analysis on systems with limited resources.

These datasets enable thorough exploration into content trends, channel performance, and audience engagement dynamics.

---

## Key Objectives

- **Data Cleaning & Preprocessing:**  
  Transform raw YouTube data into a format suitable for analysis by handling missing values, parsing dates, encoding categorical features, and normalizing numerical variables.

- **Clustering with K-Means:**  
  Apply the K-Means algorithm to group similar videos. Explore methods to determine the optimal number of clusters (e.g., Elbow Method, Silhouette Score).

- **Data Exploration & Visualization:**  
  Generate dynamic visualizations—including scatter plots, PCA or t-SNE projections—to reveal the distribution of clusters and extract actionable insights.

- **Educational Resource:**  
  Serve as a learning platform that illustrates the complete workflow for unsupervised ML projects using Python, making it ideal for students and professionals alike.

---

## Installation

### Prerequisites

Make sure you have [Python 3.x](https://www.python.org/downloads/) installed on your system. It is also recommended to use a virtual environment.

## Usage
The core analysis is provided in the Jupyter Notebook unsupervised ml.ipynb. Follow these steps:
- Launch Jupyter Notebook:
jupyter notebook
- Open unsupervised ml.ipynb in your browser.
- Follow the inline instructions, where you'll learn how the dataset is preprocessed, clustered, and visualized.
Tip: Experiment with different numbers of clusters or visualization techniques (e.g., PCA, t-SNE, interactive plots using Plotly) to further explore the data.

## Project Structure

Unsupervised-ML-/
│
├── GBvideos.csv                # Raw dataset: YouTube trending videos in Great Britain
├── compressed_data.csv.gz      # Compressed/preprocessed dataset for optimized handling
├── unsupervised ml.ipynb       # Jupyter Notebook containing the full analysis workflow
├── requirements.txt            # List of Python dependencies
└── README.md                   # Project documentation

## Features

- Comprehensive Data Cleaning:
Detailed preprocessing steps to ensure high-quality input for clustering.
- Robust Clustering:
Implementation of K-Means along with techniques for optimal cluster identification (Elbow Method, Silhouette Analysis).
- Advanced Visualization:
Visual insights using various plots and the potential for interactive exploration, which may include dimensionality reduction techniques like PCA and t-SNE.
- Reproducible Pipeline:
Easy-to-follow code and documentation, making it simple for others to reproduce and extend the analysis.

## Dependencies
The project relies on the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter
These are listed in the requirements.txt for easy installation.

## Configuration
Any project-specific configurations (e.g., file paths, analysis parameters) are defined within the notebook. For extended use, consider adding a configuration file or environment variables to manage these settings more robustly.

## Documentation
All major steps and concepts are documented within unsupervised ml.ipynb using inline markdown cells. The notebook covers:
- Data exploration and preprocessing techniques
- Detailed code for clustering analysis
- Visualization and performance diagnostics
- Commentary on insights and further exploratory ideas
This thorough documentation ensures that readers can understand each step of the workflow and its purpose

## Contributors
- Raghav: Primary architect of the project, responsible for guiding the overall design and implementation.
- Additional contributors and community members are welcome to propose enhancements, report bugs, or suggest features.
Feel free to submit Pull Requests or open an Issue on GitHub.

## License
This project is licensed under the MIT License. See the LICENSE file for details
