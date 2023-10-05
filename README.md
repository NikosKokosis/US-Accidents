# Comprehensive Analysis of US Road Accidents(2016-2023): EDA, Clustering, Prediction of Severity Assessment

## Sections
- **[Project Overview](#project-overview)**
- **[Data Source](#data-source)**
- **[Project Structure](#project-structure)**
- **[Project Notebooks](#project-notebooks)**
- **[Findings](#findings)**
- **[Dependencies](#dependencies)**
- **[Usage](#usage)**

## Project Overview

In this project, I conducted a comprehensive analysis of US road accidents using the Kaggle dataset "US_Accidents_March23." The primary objective was to gain valuable insights into accident patterns and factors influencing their severity, duration, and distance. The project involved three main stages: data exploration and preprocessing, clustering analysis based on weather conditions, and accident severity prediction using K-Means, Density-Based Spatial Clustering of Applications with Noise (DBSCAN), and Artificial Neural Networks (ANNs).

## Data Source

- **Dataset**: [US_Accidents_March23](https://www.kaggle.com/sobhanmoosavi/us-accidents)

## Project Structure

The project is organized into the following sections:

- **Exploratory Data Analysis (EDA)**: In this section, I performed an in-depth analysis of various aspects related to accidents, including severity classification, accident duration, cities where accidents occurred, and temperature variances.

- **Clustering Analysis**: This section involves data cleaning and preparing the data, followed by applying clustering techniques (K-Means and DBSCAN) to group accidents based on weather conditions.

- **Accident Severity Prediction**: Using Artificial Neural Networks (ANNs), I developed a predictive model to classify accident severity. This involves preprocessing the data, training the model, and evaluating its performance.

## Project Notebooks

- [Exploratory Data Analysis (EDA)](Code/US-Accidents_EDA.ipynb)
- [Clustering Analysis](Code/US-Accidents_Clustering.ipynb)
- [Accident Severity Prediction](Code/US-Accidents_Classification.ipynb)

## Findings

The project yielded valuable insights into US road accidents, including patterns related to accident severity, duration, geographical distribution, and temperature variances. The accident severity prediction model provides a practical tool for assessing the severity of accidents based on various factors, contributing to improved road safety measures.

## Dependencies

This project uses the following Python libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow (for ANN)

## Usage

To explore the project, you can start with the provided Jupyter notebooks in the `Code` directory. Follow the notebooks in the given order for a step-by-step understanding of the analysis.