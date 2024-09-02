# Car Crash Data Project

This repository contains the code and data analysis for car crash data from Montgomery county, Maryland. This project aims to analyze traffic accidents to identify patterns and potential safety improvements. The project uses Python, Jupyter Notebooks, and various data science libraries to process and visualize car crash data.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The Car Crash Data Project was developed to explore traffic accident data, identify trends, and create visualizations that could inform road safety policies. The project utilizes public datasets, processes them using Python, and generates insights through statistical analysis and data visualization.

## Features

- **Data Cleaning**: Pre-process raw car crash data, handle missing values, and format the data for analysis.
- **Exploratory Data Analysis (EDA)**: Generate descriptive statistics and visualizations to understand the distribution and characteristics of the data.
- **Geospatial Analysis**: Analyze the geographical distribution of traffic accidents.
- **Time Series Analysis**: Explore trends over time, such as the frequency of accidents by day, month, and year.
- **Accident Severity Analysis**: Examine factors contributing to the severity of accidents.
- **Modeling**: Implement predictive models to assess the likelihood of severe accidents based on various factors.

## Installation

To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lsteppe/Car-Crash-Data-Project.git
   cd Car-Crash-Data-Project
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows: `env\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Open the `Car_Crash_Data_Analysis.ipynb` notebook to start exploring the data.

**You will need to download the excel sheet in the repository to run the code. This data has been cleaned from the original data. If you use the original Montgomery crash data from the link below, the code will not run properly.

## Usage

After installation, you can use the Jupyter Notebook to explore the data, run the analyses, and generate visualizations. The notebook is organized into sections, each focusing on different aspects of the data analysis.

- **Data Cleaning:** The first step involves loading and cleaning the dataset.
- **Exploratory Data Analysis:** Gain insights into the data through visualizations and summary statistics.
- **Geospatial and Time Series Analysis:** Explore the geographical and temporal dimensions of the data.
- **Accident Severity Analysis:** Delve deeper into the factors influencing accident severity.

## Data Sources

The project uses publicly available car crash data from the following sources:

- [National Highway Traffic Safety Administration (NHTSA)](https://www.nhtsa.gov/)
- [Kaggle Datasets](https://www.kaggle.com/)

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request. For major changes, please discuss them in an issue first.

### How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Feel free to customize the sections according to the specific details of your project.
