# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Bautista, Dean Mark |23-00220 |MEXE - 4101 |
| Cabarles, Raiza |23-03208 |MEXE - 4101|

## Notebook links

| Chapter | Bautista | Cabarles |
|---|---|---|
| Ch1_2_3 | [link](https://colab.research.google.com/drive/1vTxQ3mTRYj8_vbkw2uqNUkl3kbT8B1dh?usp=sharing) | [link](https://colab.research.google.com/drive/1MXKMnu7U2UvbmXNReL0AQjupQ0p0UE4W?usp=drive_link) |
| Ch4 | [link](https://colab.research.google.com/drive/1td99YSsrNoDY3OZ846CPKaBt4XIqmH3g?usp=sharing) | [link](https://colab.research.google.com/drive/1BPajlaUcjI7kkmZ27e96ekNp3ySjxa3X?usp=drive_link) |
| Ch5 | [link](https://colab.research.google.com/drive/1LQq5r3I-pKf8-Z8NNL5xUIKm_sp4TZ-Y?usp=sharing) | [link](https://colab.research.google.com/drive/1QZVrv11rslOo6vnnKJTiPdTu20AGbg6A?usp=drive_link) |
| Ch6 |[link](https://colab.research.google.com/drive/1Lo7Ca8oh0aqnkYJFCjLnsiw8YXZCZRj1?usp=sharing)| [link](https://colab.research.google.com/drive/138I4inQ0aj5VA4MIL5OTrgCkaW0dpd9d?usp=drive_link) |
| Ch7 |[link](https://colab.research.google.com/drive/1fSIh3h3j6CeN99fV9rTexhoZfiSMfddm?usp=sharing)  | [link](https://colab.research.google.com/drive/1B_Nn_o_Srm6XA0SJFQxO7qksorAnYmTV?usp=drive_link) |
| Ch8 |[link](https://colab.research.google.com/drive/1kfhmxilOhtU9aHXUt3EvFVLP0dqFqB8X?usp=sharing)  | [link](https://colab.research.google.com/drive/1K7Ho1ti5E3zVOPnKaWkGmsQf5gudWgeM?usp=drive_link) |
| Ch9 |[link](https://colab.research.google.com/drive/1JE5toYzEgvWKwrfRHnRWZEfX6g5h_Vnt?usp=sharing) | [link](https://colab.research.google.com/drive/1nHh3tOEboOGJTN6_jYoC3Jy_TWVbyHSE?usp=drive_link) |


## What we learned

>### Chapter 1, 2 and 3

<p align="justify">
Chapter 1 taught us about the core of data preprocessing in which the raw data undergoes  preparatory stages before Machine Learning. We learned the different common issues of raw data which have corresponding preprocessing techniques for handling them. Most importantly, this part showed us why it's important for the raw data to undergo this process. Since a model depends on data it learns from an organized, cleaned and simplified dataset will result in improved data quality as well as higher accuracy. For Chapter 2, we were able to explore the different features of the dataset using code commands, where we observed the difference of the categorical and numerical columns. It also allowed us to view the statistical summary and the brief overview of the dataset which made us realize that exploring and understanding the data first is essential for spotting possible problems. On the other hand, Chapter 3 taught us a different approach in cleaning the data from the datasets. We realized that we can locate columns with missing values and then decide how to treat them accordingly, such as imputation, deletion or prediction. Generally, Chapter 1 -3 taught us the different stages of data preprocessing from introducing why raw data needs to be prepared, to exploring the dataset, to handling missing values which is the foundation of Machine Learning.

</p>

---


>### Chapter 4

<p align="justify">
For this chapter, We learned that feature engineering is transforming raw data into useful features wherein we combine variables to assess their relationships and patterns. It introduced us to new insights about “Binning”, which converts numerical data into categorical data, “Interaction Feature”, which combines two variables to make a new feature, and “Polynomial Feature” for non-linear relationships. We also learned about categorical variable encoding, specifically the application distinction between One-hot encoding (assigns 1 = true, 0 = false) and ordinal encoding (data with natural order that prioritize ranking). This chapter allowed us to examine and assess the dataset in each variable for its relationship, in order for us to uncover patterns as it enables us to observe how one variable affects the other. Overall, this discussion taught us the significance of simplifying our dataset categorically and numerically for useful features which needed to be prioritized. 
</p>

---


>### Chapter 5

<p align="justify">
In this section, it discusses the function of Data Scaling for standardizing the scale of the dataset in a comparable range for fair comparison. It highlighted the function of StandardScaler and MinMaxScaler which implies that StandardScaler reduces the mean to zero while scaling the unit variance to 1. Alternatively, MinMaxScaler is used to adjust the scale [0 to 1] boundary . This chapter taught us on how to handle data with large discrepancies depending on what the model needed. The most notable we learned was how these two approaches (normalization, standardization) rescales the given dataset into a narrowed value in comparison to the raw dataset. We also realized that data scaling is not always necessary and depends on the context of the algorithm in accordance with the essential features of the model.
</p>

---


>### Chapter 6

<p align="justify">
From this chapter, we understood that outliers are unusual data values that are very different from most of the other data, and they can have a noticeable effect on the results of an analysis. We learned how the Z-score and IQR methods can be used to identify these unusual values and determine whether a value is considered an outlier. We also learned that not every outlier should automatically be removed because it may contain useful or important information about the data. For example, one extreme value, such as 100 when most of the values are only around 10–20, can greatly change the overall results and may even lead to a different interpretation of the data. This helped us understand why it is important to examine unusual values carefully and consider the reason behind them before deciding whether they should be removed or kept. This notebook showed us that properly handling outliers can help make data analysis more accurate and meaningful.
</p>

---


>### Chapter 7

<p align="justify">
For chapter 7, it made us realize why choosing the right features is important when working with data. We learned that not every piece of information in a dataset is useful for making predictions, and keeping unnecessary features can affect the performance and accuracy of a model. The discussion about correlation also helped us understand how variables can have relationships with each other and why these relationships can be considered when selecting features. What stood out to us was that there are different ways to decide which features should be kept, such as filter, wrapper, and embedded methods. Each method has its own way of identifying the features that are most useful for the model. This made us realize that feature selection is not simply about removing unnecessary columns, but about carefully choosing the information that can contribute to better results. This taught us that proper feature selection can make a model more efficient, easier to understand, and potentially more accurate.

</p>

---


>### Chapter 8

<p align="justify">
Going through this chapter made us understand that preparing data before using it in a machine learning model involves several steps that need to be done in the right order. We learned how a preprocessing pipeline can put tasks such as filling in missing values, scaling data, and preparing features together instead of doing each step separately. This showed us how having an organized process can make data preparation more consistent and help avoid mistakes that could affect the results of a model. We also learned that the same pipeline can be reused when working with new data, allowing the new data to go through the same preparation steps as the original data. This is useful because it saves time, keeps the process organized, and makes sure that the data is prepared in a similar way each time. Through this chapter, we understood that proper data preprocessing is an important part of building a reliable machine learning model.
</p>

---


>### Chapter 9

<p align="justify">
For this last chapter, it helped us understand how the different data preprocessing steps can be applied to an actual dataset instead of just looking at them individually. We learned that data needs to be cleaned, transformed, and organized before it can be properly used for analysis or machine learning. The Titanic example made it easier for us to see how different types of data, such as numerical and categorical values, can require different ways of handling them. We also learned that raw data can be transformed into a format that is easier to understand and work with. For example, turning ages into different life stages showed us how numerical data can be grouped into categories that make it easier to interpret and analyze. We also understood that preprocessing is not always a one-time step because the results can still be checked and adjusted when something needs to be improved. Lastly, using visual representations of the data helped us see comparisons and patterns more clearly than looking at values that are simply presented in a table.
</p>


## Errors we found

>### Error: Chapter 6

```python
# find outliers
outliers = data[np.abs(z_scores) > 3]
print("Outliers: ", outliers)

Outliers:  []
```

<p align="justify">
The code has an error because it uses a z-score threshold of 3, which is too high for a dataset of only 8 values. With so few values, the largest possible z-score is about 2.65, so no value can ever pass the <code>&gt; 3</code> test. The outlier <code>100</code> has a z-score of 2.615, which falls below the threshold, so <code>outliers</code> comes back as an empty list even though 100 is clearly an outlier.
</p>

### Correct Code

```python
# find outliers
outliers = data[np.abs(z_scores) > 2]
print("Outliers: ", outliers)

Outliers:  [100]
```

>### Error: Chapter 7

```python
# create the RFE object and compute a cross-validated score.
selector = RFECV(estimator, step=1, cv=5)
print(selector)
```

<p align="justify">
<code>cv=5</code> is an error only because the dataset is too small. RFECV splits <code>df_2</code> into 5 folds and refits the SVR on every fold at each feature-elimination step, so with few rows each fold has too little data to train and score on reliably, and the run fails or gives unstable results. Using <code>cv=3</code> makes the folds bigger, which fixes it.
</p>

### Correct Code

```python
# create the RFE object and compute a cross-validated score.
selector = RFECV(estimator, step=1, cv=3)
print(selector)
```

>### Error: Chapter 9

```python
# Before discretization
plt.hist(data['Age'].dropna(), alpha=0.5, label='Before discretization')

# After discretization
plt.hist(titanic_preprocessed[:,2], alpha=0.5, label='After discretization')
plt.legend()
plt.show()
```

<p align="justify">
The "before" plot is wrong because <code>data['Age']</code> has already been discretized earlier in the notebook, so the histogram's x-axis shows the categories Adult, Elderly and Child instead of numeric ages. That means it plots the same discretized data as the "after" plot, which makes the comparison meaningless. The fix is to plot column 0 of <code>titanic_preprocessed</code>, which still holds the raw ages, as "Before discretization".
</p>

### Correct Code

```python
# Before discretization
plt.hist(titanic_preprocessed[:,0], alpha=0.5, label='Before discretization')

# After discretization
plt.hist(data['Age'].dropna(), alpha=0.5, label='After discretization')
plt.legend()
plt.show()
```


## Note on AI tools
<blockquote>
<p align="justify">
An AI tool was used in two parts of this work. The first was in Chapter 2, specifically in Step 3. At that part, there was some difficulty understanding what the instruction meant by uploading the CSV file into the Google Colab environment. When the code `df = pd.read_csv('/content/vgsales.csv')` was first run, a "File not found" error appeared because the CSV file was not properly uploaded to the Colab environment. An AI tool was then used to understand how to upload the file correctly. With its guidance, the CSV file was successfully uploaded into Google Colab, and the code ran without the error.

The AI tool was also used to correct the error codes found in the notebook. It helped explain why each error occurred and how to fix it, and these corrections are documented in the "Errors we found" section. The AI tool was only used for these specific technical problems, while the rest of the work was completed by following the provided notebook instructions.
</p>
</blockquote>

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly. 

VanderPlas, J. Python Data Science Handbook.

FERRIS, J. (2025). How to correctly use RFECV for feature selection in a Scikit-learn pipeline with a simple decision tree? Kaggle.[Kaggle discussion page](https://www.kaggle.com/discussions/questions-and-answers/573340)

GeeksforGeeks (2025) Using ColumnTransformer in SciKitLearn for data preprocessing. https://www.geeksforgeeks.org/machine-learning/using-columntransformer-in-scikit-learn-for-data-preprocessing/#what-is-columntransformer.

GeeksforGeeks. (2023, January 21). Recursive feature elimination with cross-validation in scikit learn. https://www.geeksforgeeks.org/machine-learning/recursive-feature-elimination-with-cross-validation-in-scikit-learn/
Jesse, I. (2025, March). *Exploring data frames*. Medium. https://medium.com/@i-jesse/exploring-data-frames-f10218a5d3bd

StandardScaler, MinMaxScaler, and RobustScaler: A comprehensive guide to feature scaling in machine learning (2026). https://www.codestudy.net/blog/standardscaler-minmaxscaler-and-robustscaler-techniques-ml/.

