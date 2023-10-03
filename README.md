# WBSFLIX Movie Recommender Systems

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Data](#data)
4. [Technologies Used](#technologies-used)
5. [Methodologies](#methodologies)
6. [How to Run the Project](#how-to-run-the-project)
7. [Results](#results)
8. [Future Work](#future-work)
9. [License](#license)

## Introduction

WBSFLIX is a renowned DVD store situated in a quaint town near Berlin. As the digital era beckons, WBSFLIX is transitioning to an online platform. With this shift, there's a pressing need for an automated yet personalized movie recommendation engine. This repository is dedicated to the development of diverse movie recommender algorithms tailored for the WBSFLIX online platform.

## Project Overview

The core objective of this endeavor is the development of a suite of recommender algorithms, providing WBSFLIX customers with pertinent movie suggestions. The recommendation strategies span from rudimentary popularity-based algorithms to sophisticated collaborative filtering techniques.

## Data

The dataset at hand offers insights into movies, user ratings, and an assortment of other pertinent attributes. A comprehensive breakdown of the data schema and the encompassed features can be found in the dedicated `Data` folder.

## Technologies Used

- **Python**: The backbone of the project.
- **Pandas**: For efficient data manipulation.
- **Scikit-Learn**: Employed for various machine learning tasks.
- **Surprise Library**: A specialized library for building and analyzing recommender systems.
- **Streamlit**: For creating an interactive web application for the recommenders.

## Methodologies

The project boasts an array of recommender system methodologies, which include:

1. **Popularity-Based Recommender**: A system that proposes movies based on a weighted rating formula, targeting the most popular choices.
2. **Content-Based Recommender**: Delving into movie attributes like genres, this recommends movies with similar content.
3. **Collaborative Filtering**: This advanced method, facilitated by the Surprise library, hinges on the SVD (Singular Value Decomposition) technique to offer collaborative recommendations.
4. **Hybrid Systems**: An amalgamation of the aforementioned methods, aiming to provide a more comprehensive recommendation framework.

## How to Run the Project

1. Initiate by cloning this repository to your local machine.
2. Proceed to install the necessary software packages.
3. Launch the Streamlit application using the following command: `streamlit run app.py`.

For an in-depth guide, please refer to the `Installation` section.

## Results

The performance and efficiency of the recommender systems have been meticulously assessed using key metrics such as RMSE (Root Mean Square Error), Precision@k, and Recall@k. Preliminary results underscore the effectiveness and precision of the developed algorithms.

## Future Work

- Enriching the recommendation engine by integrating additional attributes like movie tags and timestamps.
- Introducing real-time user feedback mechanisms for perpetual model refinement.
- Exploring the potential of neural network-based recommender systems.

## License

This endeavor is protected under the MIT License. For a detailed understanding, kindly consult the `LICENSE.md` file.
