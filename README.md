## Movie Recommendation System

This repository contains the `MovieRecommendation.ipynb` notebook, which is part of a project by YBI Foundation as part of an Artificial Intelligence and Machine Learning Internship. The notebook demonstrates how to build a recommendation system using collaborative filtering techniques on a movie dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Implementation](#implementation)
- [Results](#results)
- [How to Run](#how-to-run)
- [License](#license)

## Introduction

The purpose of this project is to create a movie recommendation system based on user preferences using collaborative filtering techniques. The model predicts movies that a user might enjoy based on the ratings given by other users with similar tastes.

## Dataset

The dataset used for this project is a publicly available movie ratings dataset. It contains information about:
- **User IDs**
- **Movie IDs**
- **Ratings** (given by users to movies)
- **Timestamps**

The dataset is pre-processed to filter out relevant information for the model.

## Dependencies

To run this notebook, the following Python libraries are required:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `surprise` (for collaborative filtering algorithms)

You can install the required libraries using:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn scikit-surprise
```

## Implementation

The recommendation system in this project is built using the **Surprise** library for collaborative filtering. The key steps in the notebook include:

1. **Loading the Dataset:** The dataset is loaded using `pandas` and prepared for modeling.
2. **Exploratory Data Analysis (EDA):** Visualizations and analysis are performed to understand user behavior and rating patterns.
3. **Model Selection:** The `SVD` (Singular Value Decomposition) model is used from the `surprise` library to perform collaborative filtering.
4. **Model Evaluation:** The model is evaluated using metrics such as **Root Mean Squared Error (RMSE)**.

## Results

The model provides personalized movie recommendations based on the users' past ratings. RMSE is used as a performance metric to evaluate the accuracy of the predictions.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/AnkitaSyam/Artificial-Intelligence-and-Machine-Learning-Internship.git
   ```

2. Navigate to the folder:

   ```bash
   cd Artificial-Intelligence-and-Machine-Learning-Internship
   ```

3. Open the `MovieRecommendation.ipynb` notebook in Jupyter or VSCode and run the cells to see the implementation and results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Thanks to YBI Foundation for the dataset.
