![Uber and Lyft Dataset Boston MA](https://github.com/DarlyP/Uber-and-Lyft-Dataset-Boston-MA/blob/main/Notebook/UberLyft.jpeg)

# Optimized Taxi Fare Prediction with Linear Regression

---

## Tools

[<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />](https://pandas.pydata.org/) [<img src="https://img.shields.io/badge/Seaborn-388E3C?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn" />](https://seaborn.pydata.org/) [<img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib" />](https://matplotlib.org/) [<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy" />](https://www.scipy.org/) [<img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="Numpy" />](https://numpy.org/) [<img src="https://img.shields.io/badge/Scikit%20learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />](https://scikit-learn.org/)


---

## Data Source

Kaggle: [Uber and Lyft Dataset Boston, MA](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma).

---

## Introduction

As a taxi service provider like Lyft or Uber, understanding the factors that influence service pricing is crucial for enhancing pricing strategies and market competitiveness. By utilizing Linear Regression analysis on a dataset from Kaggle, the company can identify how specific parameters such as booking time, pickup location, and traffic conditions affect taxi fares. These insights enable the company to optimize pricing, devise effective promotional strategies, improve service quality, provide accurate fare estimates to customers, and manage taxi fleets more efficiently.

---

## Conclusion

The conclusion obtained from this data analysis is as follows:

- A linear regression model was successfully formed using a pipeline with the "fit intercept" hyperparameter. The optimal parameter found was when "fit intercept" was set to "False".

- The RMSE (Root Mean Squared Error) produced by the model was low, around 3, while an R² value of 89.5% was achieved. Similar values were found in both the training and test data, indicating no overfitting.

- The QQ plot visualization indicated that the data is not normally distributed, evidenced by the curve deviating upwards.

- The Durbin-Watson statistic obtained was close to 2, indicating no autocorrelation.

- Homoscedasticity visualization showed heteroskedasticity in the modeled data.

- From a business standpoint, concluding that weather does not significantly affect the taxi fares of Uber and Lyft means the company can focus on more impactful pricing factors such as distance, pickup location, destination, vehicle type, and service name. This enables the company to optimize pricing strategies based on more accurate data analysis of these factors. By considering these parameters, the company can take more precise actions to attract customers with competitive pricing and enhance customer satisfaction by offering services aligned with their preferences.

---

**Disclaimer**: 
- This notebook is created solely for learning and exploration purposes. There is no intention to offend or harm any party. All content and analysis presented are based on publicly available data online. I undertake this process to enhance my understanding of data analysis techniques and methodologies and hone my skills in implementing relevant algorithms and models within the context of data science learning. In conducting this analysis, I strive to maintain objectivity and professionalism in interpreting the existing data. Any conclusions or recommendations provided result from personal analysis and are not intended as professional advice in any specific capacity. I hope the information obtained from this notebook can be useful to anyone reading it to learn and develop data analysis skills.
- This notebook is written in Indonesian.
