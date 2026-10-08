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
| Ch6 | [link](https://colab.research.google.com/drive/1Lo7Ca8oh0aqnkYJFCjLnsiw8YXZCZRj1?usp=sharing) | [link](https://colab.research.google.com/drive/138I4inQ0aj5VA4MIL5OTrgCkaW0dpd9d?usp=drive_link) |
| Ch7 | [link](https://colab.research.google.com/drive/1fSIh3h3j6CeN99fV9rTexhoZfiSMfddm?usp=sharing) | [link](https://colab.research.google.com/drive/1B_Nn_o_Srm6XA0SJFQxO7qksorAnYmTV?usp=drive_link) |
| Ch8 | [link](https://colab.research.google.com/drive/1kfhmxilOhtU9aHXUt3EvFVLP0dqFqB8X?usp=sharing) | [link](https://colab.research.google.com/drive/1K7Ho1ti5E3zVOPnKaWkGmsQf5gudWgeM?usp=drive_link) |
| Ch9 | [link](https://colab.research.google.com/drive/1JE5toYzEgvWKwrfRHnRWZEfX6g5h_Vnt?usp=sharing) | [link](https://colab.research.google.com/drive/1nHh3tOEboOGJTN6_jYoC3Jy_TWVbyHSE?usp=drive_link) |


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
From this chapter, I understood that outliers are unusual data values that are very different from most of the other data, and they can have a noticeable effect on the results of an analysis. I understood how the Z-score and IQR methods can be used to identify these unusual values and that not every outlier should automatically be removed because it may still contain useful information. It showed how one extreme value, such as 100 when most of the values are only around 10–20, can change the overall data and possibly lead to a different interpretation. This made me see why it is important to look at unusual values carefully before deciding what to do with them.
</p>

---


>### Chapter 7

<p align="justify">
This chapter helped me understand why choosing the right features is important when working with data. I understood that not every piece of information in a dataset is useful for making predictions, and keeping unnecessary features can affect the performance of a model. The discussion about correlation also helped me understand how variables can have relationships with each other and why these relationships can be considered when selecting features. What stood out to me was that there are different ways to decide which features should be kept, such as filter, wrapper, and embedded methods. It made me realize that feature selection is not simply about removing columns, but about choosing the information that is actually useful for the model.
</p>

---


>### Chapter 8

<p align="justify">
Going through this chapter made me understand that preparing data before using it in a machine learning model involves several steps that need to be done in the right order. I understood how a preprocessing pipeline can put tasks such as filling in missing values and scaling data together instead of doing each step separately. This also showed me how having an organized process can make the preparation of data more consistent and help avoid mistakes. What I found interesting was that the same pipeline can be reused when working with new data, so the new data can go through the same preparation steps as the original data. I found this useful because it makes the whole process easier to manage and more consistent.
</p>

---


>### Chapter 9

<p align="justify">
For this last chapter, it helped me understand how the different data preprocessing steps can be applied to an actual dataset instead of just looking at them individually. I learned that data needs to be cleaned, transformed, and organized before it can be properly used for analysis or machine learning. The Titanic example made it easier to see how different types of data, such as numerical and categorical values, can require different ways of handling them. What I found interesting was turning ages into different life stages because it showed me that raw numerical data can be grouped into categories that make it easier to interpret. I also understood that preprocessing is not always just a one-time step, since the results can still be checked and adjusted when something needs to be improved. Lastly, visual representation of the data gave a clearer comparison than those that are simply tabulated. 
</p>


## Errors we found

<blockquote>
<p align="justify">
<b>We did not find any errors</b> in the original notebooks while checking and running the codes. We copied the codes from the notebooks and ran them in Google Colab to see if they would work properly. After executing each code, the outputs and results were consistent with the reference provided in the notebooks. We also checked the different steps to make sure that the codes were producing the expected results. Since everything ran successfully and matched the reference results, we did not find any mistakes that needed to be corrected or changed.
</p>
</blockquote>

## Note on AI tools
<blockquote>
<p align="justify">
An AI tool was used once while working on <b>Chapter 2</b>, specifically in <b>Step 3</b>. At that part, there was some difficulty understanding what the instruction meant by uploading the <b>CSV file into the Google Colab environment</b>. When the code <code>df = pd.read_csv('/content/vgsales.csv')</code> was first run, a <b>“File not found”</b> error appeared because the CSV file was not properly uploaded to the Colab environment. 
  
An AI tool was then used to understand how to upload the file correctly. With its guidance, the CSV file was successfully uploaded into Google Colab, and the code ran without the error. The AI tool was only used to understand and solve this specific technical problem, while the rest of the work was completed by following the provided notebook instructions.
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

