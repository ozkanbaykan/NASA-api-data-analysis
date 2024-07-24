# Creating and Analyzing a Custom Dataset Using NASA's Open APIs
In this project, we will create a dataset using NASA's public API, specifically the Asteroids - NeoWs API. Following the dataset creation, we will perform data cleaning and transformation, as well as conduct data analysis to derive insights and explore various attributes of the asteroids.

## Table of Contents

1. Project Objectives
2. Tools and Libraries Used
3. Guiding Questions
4. Results
5. Data Source
6. Project Owner

## Project Objectives

The main objectives of this project are:

- **Dataset Creation:** Fetch and compile asteroid data from NASA's Asteroids - NeoWs API using the GET method.

- **Data Cleaning and Transformation:** Convert variables to appropriate formats, remove decimal places, handle missing values, and create new variables like momentum and average estimated values.

- **Data Analysis:** Explore correlations and trends by addressing guiding questions on hazard potential, momentum, brightness, asteroid distributions, and miss distances.

## Tools and Libraries Used

In this project, the following tools and libraries were used:

- Pandas
- Datetime
- Requests
- Matplotlib
- Scipy
- Sklearn

## Guiding Questions

The guiding questions of the project are:

**1.** Is there a correlation between the risk of impact with Earth and whether an asteroid is classified as potentially hazardous?

**2.** Is there a correlation between momentum and whether an asteroid is classified as potentially hazardous?

**3.** Is there a correlation between the brightness and the speed of the asteroids?

**4.** How many hazardous asteroids are there within the selected dates, and what are their characteristics?

**5.** Which day has the highest number of asteroids, and how many are there on that day?

**6.** What are the average miss distances of the asteroids?

## Results

1. **Dataset Overview:**
   
    - Compiled a dataset from NASA's Asteroids - NeoWs API, covering various asteroid attributes.

2. **Data Cleaning and Transformation:**
   
    - Converted variables to proper formats and addressed missing values.
    - Created new variables, such as momentum and average estimated values.
      
3. **Correlation Analysis:**

    - **Hazard Potential and Risk of Impact:** Found a weak correlation.
    - **Momentum and Hazard Classification:** Moderate positive correlation observed.
    - **Brightness vs. Velocity:** Positive correlation found, indicating that faster asteroids tend to be brighter.

4. **Distribution and Trends:**

    - **Hazardous Asteroids:** Identified and characterized hazardous asteroids.
    - **Daily Counts:** Determined the day with the highest number of asteroids.
    - **Miss Distances:** Analyzed average miss distances of asteroids.

## Data Source

The dataset was obtained from [NASA Asteroids - NeoWs API](https://api.nasa.gov/).

## Project Owner

This project was created by [Özkan Yiğit Baykan](https://github.com/ozkanbaykan) on GitHub.
