# Ramen Delivery Analysis(1,2,3)

thank you for visiting

Ramain_delivery1.ipynb : Preparation for Analysis, Visualize and analyze data, Build a visualization mechanism,Build a reporting system

Ramain_delivery2.ipynb : Build an analysis system, Processing data for machine learning, Build a machine learning model

Ramain_delivery3.ipynb : Predicting New Data with the Machine Learning Model, Create a small-scale machine learning system, Create a dashboard for a machine learning system


## Sample Reports from Output Ramain_delivery3

### for Headquarters 
![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/18eb9bd2-c0e4-43da-8f99-5a92ff560c5d)



### for Maebashi Store = *前橋店
![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/1eedca62-cb0d-4ec4-9fa5-4e7210e6639d)

### Prediction Results 
![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/b765e7e4-1e92-457d-8bb4-da442a0b4d18)


### heat map
![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/99376908-e2bb-4be9-84b1-3f8eff6e14af)

### Accuracy Trends
![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/c2552b08-2abe-40a7-ba66-2955065eabb7)

### Dash Board
![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/b1dcfdf7-049e-43c4-8120-2b12c88b269f)

![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/d184a41f-42c2-4fc2-ba90-6212fd5624b8)


### Result for importance 
![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/4892ce2c-48d6-4561-8fed-24c56ffeea1e)

### Result for prediction 
![image](https://github.com/taka7peace/Ramain_derivery_analysis/assets/114953599/7096992f-ec4b-42ff-adfd-143c0bd5345e)


### Mid Review(part 1,2)
The rate of improvement has varied from store to store, and I feel that simply reporting the results of the previous month's time to serve Ramen is insufficient information. Therefore, I would like to help store staff by using machine learning to make predictions. I have found that the shorter the time to serve ramen, the lower the cancellation rate tends to be. 
I set the task of shortening the time until the ramen is served. Some stores review their workflow and fix the waste until the ramen is served. I believe that such efforts can be improved by sharing self-help efforts by stores company-wide and by reviewing common flows at headquarters.
In addition, at one store, the store manager reviews the data and reassigns people so that the supply-demand balance is achieved. 

A good store manager will look at past sales and order numbers and think about when the number of orders will increase next month. Based on that projection, he or she skillfully adjusts the shifts of part-time workers to improve ramen serving times while lowering costs. While the ability to draw one's own insights from past data and make predictions like this is a strong part of the human condition, only a limited number of people can do it, and the accuracy of such predictions varies from person to person. 
The reporting measures in the first part of the report will separate the stores that can utilize the data from those that cannot. Therefore, the model is a supervised learning binary classification model to predict whether the number of orders will increase or decrease in the next month based on data up to the previous month. I believe that creating two models, one for weekdays and one for holidays, will support the consideration of measures to reduce the time required to serve ramen.

### Review(Part 3)
To better analyze and evaluate from multiple perspectives, I am developing a simplified model-building system. This system will not only create and assess models but also incorporate a data analysis system, strengthening its capacity to handle updated data inputs.

Upon completion of the machine learning model building process, I move to the next critical stage: forecasting with new data. For this, I will use the March 2020 order data. Like any other step in this process, forecasting with new data requires proper data processing. I aim to establish an integrated workflow, from data processing to forecasting, which can effectively handle and adapt to newly updated data.

This holistic process of data science, starting from data processing and culminating in new data forecasting and reporting, has been successfully implemented. While this achievement is satisfying, I recognize that it is the beginning of a continuous journey. I have yet to accumulate substantial data, and it's essential to remember that data accumulation will occur with each update, providing opportunities to reassess our model and validate new data forecasts.

Thus, my plan is to make the most of this functionality to accumulate data during monthly updates. This, in turn, will facilitate building a monthly model based on the progressively accumulating data.

An interesting trend has been observed in our model's accuracy evaluation results. There was a slight increase in accuracy from April to June, followed by a decrease in July. The decrease in July might be attributable to the implementation of certain measures in June, potentially indicating a shift in trend.

This has made it clear that accumulating data and leveraging it effectively offers various insights. It also exposed a significant shortfall in our model's performance in July: its ability to handle time-series data. To mitigate this, it might be beneficial to enhance the model's capacity to manage time-dependent data.

Furthermore, the division of training and test data currently lacks a time series perspective, with data being randomly split instead of being stratified by time. To increase the model's resilience, it would be advantageous to instigate a mechanism for continuous validation. This would involve rapidly cycling through the Plan, Do, Check, Act (PDCA) process, enabling faster iterative improvements to the model based on immediate feedback.
