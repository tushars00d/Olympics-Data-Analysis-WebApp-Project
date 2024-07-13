# Olympics Data Analysis WebApp

## Overview
This project aims to analyze data from previous editions of the Olympics to gain valuable insights and provide hands-on experience in data analysis. It was created as a learning project inspired by a tutorial video from the YouTube channel CampusX. The video teaches how to use a Kaggle dataset of Olympics data to create a web app using Streamlit, which allows for interactive data exploration and analysis.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)
- [Contributing](#contributing)
- [License](#license)

## Features
- Fetch and display medal tallies for different countries and years.
- Visualize data trends over time.
- Identify the most successful athletes and countries.
- Analyze the distribution of athletes' height and weight across different sports.
- Compare the participation of men and women over the years.
- Interactive plots and visualizations for a comprehensive understanding of the data.

## Dataset
The dataset used for this project is sourced from Kaggle. It contains detailed information about Olympic athletes, their performance, and the events they participated in.

- [Olympics Dataset on Kaggle](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)

## Installation
To get started with the project, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/olympics-data-analysis-webapp.git
    cd olympics-data-analysis-webapp
    ```

2. **Create a virtual environment:**
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Download the dataset:**
    Download the dataset from Kaggle and place it in the project directory.

## Usage
To run the Streamlit web app:

1. **Activate the virtual environment (if not already activated):**
    ```sh
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

2. **Run the Streamlit app:**
    ```sh
    streamlit run app.py
    ```

3. **Open your web browser and go to:**
    ```
    http://localhost:8501
    ```

## Project Structure
olympics-data-analysis-webapp/
│
├── app.py # Main script to run the Streamlit app
├── helper.py # Helper functions for data processing and visualization
├── requirements.txt # List of required Python packages
├── README.md # Project documentation
└── your_data.csv # Downloaded dataset from Kaggle


## Acknowledgements
I would like to thank the CampusX YouTube channel for their amazing tutorial video. The clear and detailed explanation helped me understand the concepts of data science and data analysis in more depth.

- [CampusX YouTube Channel](https://www.youtube.com/channel/UC9Qpi6jke6lTtQ6SIdrDApA)

