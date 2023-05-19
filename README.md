# Ramain Delivery Analysis(1,2,3)
Ramain_deryvery1.ipynb
Ramain_deryvery2.ipynb
Ramain_deryvery3.ipynb

Welcome to my repository
thank you so much for visiting

## Sample Reports from Output Ramain_delivery3

### for Headquarters 
![Screenshot 2023-05-19 115957](https://github.com/taka7peace/intern_project_Eng/assets/114953599/c937033d-20c7-485c-b5a7-d70bf3f8d780)

### for Maebashi Store = *前橋店
![Screenshot 2023-05-19 120421](https://github.com/taka7peace/intern_project_Eng/assets/114953599/5411791f-d441-431d-954c-e583189c8ad2)

### Prediction Results 
![Screenshot 2023-05-19 120205](https://github.com/taka7peace/intern_project_Eng/assets/114953599/735c13c0-40f8-4744-800d-1f989bb5310f)


### heat map
![Screenshot 2023-05-19 122302](https://github.com/taka7peace/intern_project_Eng/assets/114953599/1345934b-9e5d-4b89-9154-14fb9e6a335b)

### Accuracy Trends
![Screenshot 2023-05-19 122321](https://github.com/taka7peace/intern_project_Eng/assets/114953599/16850002-2f68-4947-bd5e-f27bf2356dd9)

### Dash Board
![Screenshot 2023-05-19 122138](https://github.com/taka7peace/intern_project_Eng/assets/114953599/eacad753-a32b-4ebc-9c2f-11d8777937a8)

![Screenshot 2023-05-19 122203](https://github.com/taka7peace/intern_project_Eng/assets/114953599/77da914d-e8fd-49e7-aacd-3d0ffe8dd52e)


### Result for importance 
![Screenshot 2023-05-19 122557](https://github.com/taka7peace/intern_project_Eng/assets/114953599/12b84b8c-8c0b-4ccf-8214-32da8b52c807)

### Result for prediction 
![Screenshot 2023-05-19 122625](https://github.com/taka7peace/intern_project_Eng/assets/114953599/93fde1bf-e81d-4df4-8214-3aeb4e240586)


### Mid Review(part 1,2)
The rate of improvement has varied from store to store, and I feel that simply reporting the results of the previous month's time to serve Ramen is insufficient information. Therefore, they would like to help store staff by using machine learning to make predictions. I have found that the shorter the time to serve ramen, the lower the cancellation rate tends to be. 
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
