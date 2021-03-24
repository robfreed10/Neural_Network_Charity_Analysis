# Neural_Network_Charity_Analysis
Processing Data for a neural network model

## Overview of Analysis
For this project, I utilized the dataset which contains information from a loan finding application. Using the variables from this dataset, I created a model to predict how the money invested into the charitable organization will be used effectively. The variables used were "EIN" and "NAME", which were identifier columns, "APPLICATION_TYPE", "AFFLICATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATION", "ASK_AMT" & "IS_SUCCESSFUL". In order to successfully complete this project, I had to prepocess the data for my neural network model, as well as complie, train, and evaluate the accuracy of the model and how optimized it was. 

## Results of Analysis
#### Data Preprocessing
- What variable(s) are considered for your model?: The target was considered to be the "IS_SUCCESSFUL" column because the goal was to see how effective the charitable organization was using the funding. 
![Screen Shot 2021-03-24 at 8 13 56 AM](https://user-images.githubusercontent.com/68922663/112308845-f76cd100-8c78-11eb-9ada-4945b0d4fd3e.png)
![Screen Shot 2021-03-24 at 8 14 13 AM](https://user-images.githubusercontent.com/68922663/112308856-f9cf2b00-8c78-11eb-9014-13dcecc0ed1c.png)
![Screen Shot 2021-03-24 at 8 15 18 AM](https://user-images.githubusercontent.com/68922663/112308927-166b6300-8c79-11eb-8b30-5913a22a6b9a.png)

- What variable(s) are considered to be the features for your model?: Variables that were considered to be features included in the model were "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATION" & "ASK_AMT"

- What variable(s) are neither targets nor features, and should be removed from the input data?: I removed the "EIN" and "NAME" column as I found them to be not useful for my model

#### Compile, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?: I selected 100, 80, & 50 from 1 to 3. This was used because the Relu activation was used in the first layer, followed by sigmoid activation for the final two layers. I wanted to prevent overfitting. 
![Screen Shot 2021-03-24 at 8 25 18 AM](https://user-images.githubusercontent.com/68922663/112310051-80383c80-8c7a-11eb-90db-96cc3445aa2b.png)

- Were you able to achieve the target model performance?: I was able to achieve an accuracy of 73.15% 
![Screen Shot 2021-03-24 at 8 27 36 AM](https://user-images.githubusercontent.com/68922663/112310315-d0af9a00-8c7a-11eb-9dd6-ea04dacd3c8f.png)

- What steps did you take to try and increase model performance?: For each optimzation attempt, I edited the number of neurons, the relu and sigmoid layers, and dropped columns that I did not believe were needed for the model. I also used binnings for different variables. 

## Summary of Analysis
To improve the analysis across the different optimazation notebooks, I used bins for different variables and edited the number of hiden layers. To increase the accruacy of this model, changing the number of layers and perhaps using different variables could carry out different results.
