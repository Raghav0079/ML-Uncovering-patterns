# Unsupervised-ML: Uncovering Hidden Patterns in YouTube Trending Videos

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
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
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

### Clone the Repository

Open your terminal and run:
```bash
git clone https://github.com/Raghav0079/Unsupervised-ML-.git
cd Unsupervised-ML-
