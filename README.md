# -Greenhouse-Plant-Growth-Analysis-Using-Machine-Learning
The Greenhouse Plant Growth Analysis Using Machine Learning is one of the project that i have done in my masters period.

 # Project Overview

This project applies Data Science and Machine Learning techniques to analyze plant growth metrics collected from a controlled greenhouse environment. The objective is to uncover hidden relationships between plant growth parameters and identify natural groupings of plants without predefined labels.

Using Exploratory Data Analysis (EDA), Correlation Analysis, Principal Component Analysis (PCA), and K-Means Clustering, the project demonstrates how unsupervised learning can support decision-making in precision agriculture and greenhouse crop management.

# Problem Statement

Greenhouse environments generate large amounts of plant growth data, including measurements such as:
* Average Canopy Height per Plant (ACHP)
* Plant Height Ratio (PHR)
* Root Fresh Weight (RFW)
* Additional growth-related indicators
Traditional statistical methods often fail to capture complex relationships between these variables. This project leverages machine learning techniques to discover patterns, correlations, and plant groupings that may improve agricultural decision-making.

 # Objectives
=> Analyze greenhouse plant growth metrics.
=>Identify relationships among growth parameters.
=> Discover key features influencing plant performance.
=> Classify plants into natural groups using clustering.
=> Visualize high-dimensional plant data using PCA.

# Dataset
Dataset: Greenhouse Plant Growth Metrics
The dataset contains structured numerical measurements collected from plants grown in controlled greenhouse conditions.

# Features
=>ACHP (Average Canopy Height per Plant)
=>PHR (Plant Height Ratio)
=>RFW (Root Fresh Weight)
=>Additional growth indicators
The dataset does not contain target labels, making it suitable for unsupervised machine learning.

# Technologies Used
* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Methodology

### 1. Data Cleaning & Preprocessing

* Missing value inspection
* Data quality verification
* Feature selection

### 2. Exploratory Data Analysis (EDA)

* Statistical summaries
* Histograms
* Boxplots
* Distribution analysis

### 3. Correlation Analysis

* Pearson correlation matrix
* Correlation heatmap visualization
* Identification of highly related features

### 4. Feature Scaling

* StandardScaler normalization
* Preparation for clustering and PCA

### 5. K-Means Clustering

* Unsupervised grouping of plants
* Identification of similar growth profiles

### 6. Principal Component Analysis (PCA)

* Dimensionality reduction
* Visualization of cluster separation
* Interpretation of plant growth patterns


## Key Findings

### Strong Feature Relationships

Correlation analysis revealed significant relationships between plant growth metrics, particularly between ACHP and PHR.

### Plant Group Identification

K-Means clustering successfully grouped plants with similar growth characteristics despite the absence of predefined labels.

### Dimensionality Reduction Insights

PCA provided clear visualization of plant clusters and helped identify underlying growth behavior patterns.

### Agricultural Impact

The findings demonstrate how machine learning can assist in:

* Precision agriculture
* Crop monitoring
* Growth pattern analysis
* Early-stage anomaly detection
* Greenhouse optimization


## Results

| Analysis            | Outcome                             |
| ------------------- | ----------------------------------- |
| Data Overview       | Verified data quality and readiness |
| Correlation Heatmap | Identified feature relationships    |
| Feature Scaling     | Prepared data for ML algorithms     |
| K-Means Clustering  | Grouped similar plant profiles      |
| PCA                 | Visualized growth pattern clusters  |



## Future Enhancements

* Incorporate environmental variables such as temperature and humidity.
* Apply supervised learning models when labeled data becomes available.
* Develop predictive models for plant growth forecasting.
* Integrate real-time greenhouse sensor data.



## Author

**Mahalakshmi Chaluvadhi**

Master of Science – Information Quality
University of Arkansas at Little Rock

