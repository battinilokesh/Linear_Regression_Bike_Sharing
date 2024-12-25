# Bike Sharing Assignment
> This case study focuses on analyzing bike-sharing data to understand demand patterns and provide actionable insights for business decision-making.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Background**  
    The Bike Sharing Case Study analyzes data from BoomBikes, a U.S.-based bike-sharing provider, to assess demand patterns and forecast future bike usage. The study aims to help BoomBikes understand demand dynamics and optimize its business strategies for the post-pandemic market.

- **Business Problem**  
    - Identifying the key factors influencing bike-sharing demand.
    - Predicting future demand to help BoomBikes plan and adjust operations.
    - Enhancing business strategies to meet customer expectations and stand out in a competitive market.
  
- **Dataset**  
    The analysis uses a dataset with information on daily bike rentals. The dataset includes variables such as weather conditions, season, holidays, working hours, temperature, humidity, and wind speed, which influence bike-sharing demand. The dataset is used to explore patterns in bike usage and predict demand based on these variables.

 **Problem Statement:**
A bike-sharing system provides bikes for short-term use, either for a fee or free. Users can borrow bikes from computer-controlled docks by entering payment information, and return them to any dock within the same system.

BoomBikes, a US bike-sharing provider, has faced significant revenue declines due to the COVID-19 pandemic. Struggling to sustain in the current market, they plan to implement a strategic business plan to boost revenue post-lockdown.

BoomBikes aims to gauge the demand for shared bikes post-quarantine to better cater to consumer needs, differentiate from competitors, and achieve profitability.

They have hired a consulting firm to identify the factors influencing bike demand in the American market, focusing on significant variables and their impact on demand. The firm has collected extensive data on daily bike demands based on meteorological surveys and consumer behavior.

**Objective of the company:**
The company aim to assess the demand for shared bicycles post-quarantine. This strategy will help them align with consumer needs, differentiate from competitors, and achieve profitability.

The instructions provided are:

**Model Construction:**

In the provided dataset, you will observe three columns: 'casual', 'registered', and 'cnt'. The 'casual' variable denotes the number of casual users who have made a rental. Conversely, the 'registered' variable indicates the total number of registered users who have made a booking on a given day.

Finally, the 'cnt' variable represents the total number of bike rentals, encompassing both casual and registered users. The model should be constructed with 'cnt' as the target variable.

**Model Evaluation:**

Upon completing model construction and residual analysis, and after making predictions on the test set, ensure you use the following lines of code to compute the R-squared score on the test set:

**from sklearn.metrics import r2_score**

**r2_score(y_test, y_pred)**

Here, y_test is the test dataset for the target variable, and y_pred contains the predicted values of the target variable on the test set. Do not overlook this step, as the R-squared score on the test set carries some marks. The variable names within the r2_score function may vary based on your chosen variable names.

## Technologies Used
- **Python (Version 3.x)**: Programming and data analysis.
- **Pandas (Version 1.4.0)**: Data manipulation and analysis.
- **NumPy (Version 1.22.0)**: Numerical computations.
- **Matplotlib (Version 3.5.0) and Seaborn (Version 0.11.2)**: Data visualization.
- **Jupyter Notebook**: Interactive environment for running the analysis.
- **Scikit-learn**: Machine learning model development.

## Conclusions
- **Weather Conditions**: The demand for bike-sharing is highly influenced by weather conditions, with higher usage during pleasant weather.
- **Seasonal Demand**: The demand for bikes peaks during spring and summer months, while it declines in winter.
- **Temperature and Humidity**: Higher temperatures generally increase bike rentals, while high humidity can reduce demand.
- **Working Hours**: Bike usage is higher during working hours, suggesting that commuting plays a major role in demand.
- **Yearly Trends**: Demand for bike-sharing services is increasing year over year, as indicated by the 'yr' variable, making it a valuable predictor.
- cnt=0.1484+0.2342×year−0.0547×holiday+0.0474×workingday+0.4789×temp−0.1492×windspeed+0.0894×sep+0.0585×sat−0.2904×Light_snowrain−0.0809×Misty−0.0543×spring+0.0625×summer+0.0968×winter

## Acknowledgements
I would like to express my sincere gratitude to the online learning platform and resources that greatly facilitated the analysis and project development. Their tools and data resources were invaluable in completing this study.

A special thanks to IIITB for the comprehensive course that provided the foundational knowledge and skills necessary to conduct this case study. The curriculum and mentorship were instrumental in shaping the insights and outcomes of this project.

Thanks,  
- Prof. Akash Akash 
- Prof. Amit Pandey 

## Contact
Created by Battini Lokesh.  
Please feel free to contact me!
