
# Big Data Analytics of Movie Ratings Using PySpark 🎬📊

## Overview 📖

This project leverages **PySpark** to analyze the **MovieLens dataset**, extracting valuable insights on movie ratings, popularity, and variability. The dataset consists of **ratings** and **tags** applied to movies, allowing us to explore key features such as the most popular movies, top-rated movies, movies with high rating deviation, and much more.

### Key Features 🌟
- **Most Popular Movies**: Movies ranked by the number of ratings 🎥
- **Top-Rated Movies**: Movies ranked by average rating ⭐
- **Marmite Movies**: Movies with high variability in ratings (extreme opinions) 🤔
- **Rating Deviation**: How much ratings deviate from the average (highlighting polarized opinions) 🔍
  
---

### Tools Used 🛠️
- **PySpark**: For big data processing and analysis 🚀
- **Gradio**: For creating an interactive web interface to explore the results 🌐
---



### 📊 **Dataset Overview**
This dataset 📅 **MovieLens** contains data on movie ratings 🌟 and free-text tags 🏷️ collected from the MovieLens recommendation service. It includes:

- **100,836 ratings** across **9,742 movies**
- **3,683 tag applications** from **610 users**
- Data collected from **March 29, 1996 - September 24, 2018**

The data is provided in these files: 
- `links.csv`
- `movies.csv`
- `ratings.csv`
- `tags.csv`

Visit the MovieLens site for more: [MovieLens](http://movielens.org) 🎥


## Installation 💻

To run this project, you'll need to install the following dependencies:

```bash
pip install pyspark py4j
pip install findspark
pip install gradio
```

## Setup and Execution 🚀

1. **Initialize Spark Session**: Create a Spark session using PySpark for distributed data processing.

2. **Load Data**: The dataset includes `ratings.csv` and `movies.csv`, which are loaded into PySpark DataFrames.

3. **Data Analysis**: Perform analysis using PySpark's `DataFrame` API to derive insights such as:
   - Most popular movies based on the number of ratings.
   - Top-rated movies based on average rating.
   - Movies with the highest standard deviation in ratings (Marmite movies).
   - Rating deviation from a neutral rating (average).

4. **Gradio Interface**: Use Gradio to create a user interface that displays data insights interactively.


## Functions 🤖

- **Show Most Popular Movies**: Displays the movies with the highest number of ratings.
- **Show Top Rated Movies**: Displays the movies with the highest average rating.
- **Show Marmite Movies**: Displays movies with the most significant variation in ratings.
- **Show Rating Deviation**: Displays movies with the most significant deviation from the neutral rating (3 stars).


## Example Data Insights 📊

1. **Most Popular Movies**: Based on the number of ratings.
2. **Top-Rated Movies**: Based on the average rating.
3. **Marmite Movies**: Movies with highly polarized opinions (high standard deviation).
4. **Rating Deviation**: Movies with ratings that differ most from the neutral rating of 3 stars.


## Interactive Web Interface 🌍

The app provides an easy-to-use **Gradio** interface with tabs for:
- **Project Overview**: Detailed information about the project and key features.
- **Data Insights**: Buttons to explore different insights about the movies.

### 💻 Gradio Interface


![Image](https://github.com/user-attachments/assets/0759bb83-6f77-4234-bb3c-e90866ab133f)

![Image](https://github.com/user-attachments/assets/cd81985e-5c6d-48cc-858b-d6f3b3ea2c78)

![Image](https://github.com/user-attachments/assets/d19470de-0eb0-46f3-a3f0-60d1c4393d10)


## Example of Data Output 📝

The following data is displayed when users click the corresponding buttons:

- **Most Popular Movies**: Top 10 movies by number of ratings.
- **Top Rated Movies**: Top 10 movies by average rating.
- **Marmite Movies**: Top 10 movies with the highest rating standard deviation.
- **Rating Deviation**: Movies with the highest deviation from a rating of 3.

## Conclusion 🎉

This project demonstrates how big data processing with PySpark can provide deep insights into large-scale datasets. The integration of Gradio allows for an interactive and user-friendly way to explore and visualize the results.


---

🔗 **Acknowledgments**
- **MovieLens Dataset**: [GroupLens](https://grouplens.org/datasets/)


---



---

### 🔗 **Citation**
If you use this dataset, please cite the paper:

> Harper, F. M., & Konstan, J. A. (2015). *The MovieLens Datasets: History and Context*. ACM Transactions on Interactive Intelligent Systems (TiiS), 5(4), 19:1–19:19. [DOI](https://doi.org/10.1145/2827872)

---

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).




