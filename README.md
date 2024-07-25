
# Restaurant Recommendation System

## Project Overview

This project aims to develop a recommendation system for restaurants using collaborative filtering, content-based filtering, and hybrid methods. The system leverages user reviews and ratings to suggest restaurants that users might enjoy.

## Contents

- `Restaurant reccomendation.ipynb`: The main Jupyter Notebook containing code for data loading, preprocessing, model building, and evaluation.
- `data/`: Directory containing the dataset(s) used in the project.
- `models/`: Directory for storing trained models and related files.
- `README.md`: This file, providing an overview of the project and instructions for usage.

## Requirements

- Python 3.7 or higher
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `scikit-learn`, `surprise`, `matplotlib`, `seaborn`, `nltk`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/username/restaurant-recommendation-system.git
    cd restaurant-recommendation-system
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset and place it in the `data/` directory.

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Restaurant reccomendation.ipynb
    ```

2. Run the cells sequentially to:
    - Load and preprocess the data
    - Build and train recommendation models
    - Evaluate model performance
    - Generate restaurant recommendations

## Dataset
The dataset is from https://www.yelp.com/dataset

## Models

This project explores different recommendation algorithms, including:
- **Collaborative Filtering**: Utilizing user-item interaction matrices to recommend restaurants based on similar users or items.
- **Content-Based Filtering**: Recommending restaurants based on the similarity of restaurant attributes.
- **Hybrid Methods**: Combining collaborative and content-based approaches to improve recommendation accuracy.

## Evaluation

The models are evaluated using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). The notebook includes visualizations to compare model performance.

## Results

The best-performing model combines collaborative filtering and content-based filtering to provide accurate and personalized restaurant recommendations.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

