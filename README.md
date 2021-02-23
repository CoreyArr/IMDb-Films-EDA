

# *IMDb Films Exploratory Data Analysis EDA*

### Co-Contributors
<a href = "https://github.com/AlignedMind/DataScience-Portfolio" >Jeremy Cruzado</a>

## Project Goals 

- Explore data set to discover trends, anomalies, and correlations to rates.
- Clean and optimize data set for visualizations.
- Create clear and insightful visualizations to describe and showcase findings.



## Table of Contents

<details>
    <summary>Open</summary>

        1. File Descriptions
        2. Technologies Used
        3. Executive Summary

</details>

## File Descriptions

<details>
    <summary>Open</summary>

- IMDb movies.csv
- IMDb names.csv
- IMDb ratings.csv
- Movies EDA.ipynb: Jupyter Notebook on data analysis

</details>

## Technologies Utilized

<details>
    <summary>Open</summary>

        1. Python3
        2. Pandas
        3. Matplotlib
        4. Seaborn
        5. Numpy
</details>

 ## Executive Summary


<details>
    <summary>Open</summary>
    <h3>Data Cleaning</h3>
    <h4>Primary Goal</h4>
    <p>The goals I set out for in this project was to collaborate with data scientist, Jeremy Cruzado on a portfolio piece that showcases a range of our knowledge and ability. Furthermore I set out to create value for those who are interested in a wide range of film, genres and directors. </p>
  

### Library Imports
<details>
    <summary>Part 1</summary>
    <h3>Importing required libraries and loading into dataframe</h3>
    <p>The required libraries included the utilization of primarily pandas, numpy, matplotlibi, and seaborn. The inclusion of sklearn was for preprocessing.</p>

</details>

<details>
    <summary>Part 2</summary>
    <h3>Early EDA</h3>
    <p>This portion focused primarily on understanding the dataframe. These findings were as follows:
    <h5>Shape</h5>
<p>The data frame consists of 70 columns and 85854 rows.</p>


</details>
<details>
    <summary>Part 3</summary>
    <h3>Data Visualizations</h3>
    <h5>Heatmap: Rating, Year, Duration </h5>
<img src="https://github.com/CoreyArr/IMDb-Films-EDA/blob/main/Images/Rating,%20Year,%20DurationHeatmap.png?raw=true" alt="Heatmap: Rating, Year, Duration">
   ---
    <h5>Bar Plot: Ratings by Genre</h5>
<img src="https://raw.githubusercontent.com/CoreyArr/IMDb-Films-EDA/main/Images/Genre%20by%20Rating.png" alt="Bar Plot: Ratings by Genre">
    ---
    <h5>xBar Plot: Genre Production Frequency</h5>
<img src="https://github.com/CoreyArr/Medical-Insurance-Project/blob/main/Images/HistAge.png?raw=true" alt="Bar Plot: Genre Production Frequency">
   ---
    <h5>Bar Plot:Genre by Votes</h5>
<img src="https://github.com/CoreyArr/IMDb-Films-EDA/blob/main/Images/Genre%20by%20Votes.png?raw=true" alt="Bar Plot:Genre by Votes">
    ---
    <h5>Bar Plot: Genre by Gender</h5>
<img src="https://github.com/CoreyArr/IMDb-Films-EDA/blob/main/Images/Genre%20Votes%20by%20Gender.png?raw=true" alt="Bar Plot: Genre by Gender">
</p>
    ---

</details>

<details>
    <summary>Part 4</summary>
    <h3>Summarizing Findings</h3>
    <h4>Who voted and why?</h4>
    <p>
        Since majority the majority of votes came from males, our data reflects that males vote on films more than females. What interesting is that the Drama and Comedy genres are the leading two genres in terms of pure ratings and production frequency. However, films that consist of the Action, Adventure, and Sci-Fi genres are dominant when comparing the votes.</p>
    <div>
    </div>
</details>
    <details>
    <summary>Part 5</summary>
    <h3>Closing Thoughts</h3>
    <p> The leniency of the rating system may have changes over the course of time. I observed that movies receiving ratings of 10 has become much more common and frequent through the years. This can also mean that films are simply getting better over time.
    </p>
</details>
