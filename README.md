# Restaurant Recommendation System

This repository contains a set of code files for building a **Restaurant Recommendation System** using multiple techniques, including **Content-Based Filtering**, **Collaborative Filtering**, and **Hybrid Models**. The system provides personalized restaurant recommendations based on user preferences and historical data.

## Repository Structure

1. **Code Files:**
   - `1_RecomSystem_knowledge_based.py`: Implements knowledge-based recommendation logic.
   - `2_RecomSystem_Content_User_Entry.py`: Allows user input for content-based recommendations.
   - `2_RecomSystem_Restaurant_Content.py`: Implements content-based filtering using restaurant features.
   - `3_Matrix_Multiplication.ipynb`: Jupyter notebook for matrix multiplication operations.
   - `3_RecomSystem_Matrix_Multiplication.py`: Python script for matrix multiplication.
   - `4_Hybrid_Recommendation_model.ipynb`: Jupyter notebook for building a hybrid recommendation model.
   - `4_RecomSystem_Hybrid.py`: Python script for hybrid recommendation logic.
   - `5_Collaborative_Filtering.ipynb`: Jupyter notebook for collaborative filtering model.
   - `5_RecomSystem_Collaborative.py`: Python script for collaborative filtering model.
   
2. **Data Files:**
   - `BangaloreZomatoData.csv`: Raw data for restaurants in Bangalore.
   - `BangaloreZomatoData_with_rest_id.csv`: Processed data with restaurant IDs.
   - `UserOrdersData.csv`: Data for user orders and ratings.
   - `USER AND RESTRAUNT.xlsx`: Additional data for user and restaurant interactions.

3. **README.md**: This file.

## Features

- **Content-Based Filtering**: Recommends restaurants based on their features like cuisines and what they are known for.
- **Collaborative Filtering**: Uses user-item interactions to recommend restaurants based on user ratings.
- **Hybrid Model**: Combines both content-based and collaborative filtering techniques for better recommendations.

## Technologies Used

- **Python**: Programming language used for the implementation.
- **Pandas**: For data manipulation and processing.
- **Scikit-learn**: For machine learning models like cosine similarity and SVD.
- **Surprise**: For collaborative filtering using the SVD algorithm.
- **Tkinter**: For building the graphical user interface (GUI).
- **Jupyter Notebooks**: For matrix multiplication and hybrid recommendation model development.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/prateekmaj21/Restaurant-Recommendation-System.git
