# Story
## Plot summary
-   Case introduction
-   Data introduction
-   EDA
-   Modelling
-   Conclusion

## Story content
Imagine you and your friend have applied for a life insurance plan separately. 30 days later of the application, you received a reply from the insurance company. "I am sorry that we are unable to cover you at the proposed rate," the agent said, "because your reported risk is high." The agent then recommended a life insurance plan with a higher premium rate for you without explaining the reasons for you having such a risk. 

You and your friend shared a common medical report, a common employment information, etc. So, how come your originally discussed coverage was denied and your friend's was accepted? You found this situation unacceptable because you waited a **whole 30 days**, which is a very tedious and long period of time.

Suddenly, you discovered that there was a Kaggle competition called "Prudential Life Insurance Assessment". Today, still being frustrated and angry, you are unable to focus on anything else but to dig patterns in the data set given in the Kaggle competition so as to calm yourself down. You aim at developing something that predicts applicants's risk based on their inforamtion, gives applications interpretable rejection reasons if necessary, and shortens the time of risk assessment.  

First of all, it is good for you to start with a very fundamental but important question. What is your primary goal in this project? Is predicting someone's risk based on his/her information your primary goal? You should agree that this primary goal does not suffice because you were angry that you could not know the exact reasons of getting a high risk. So, a more reasonable primary goal will be: predicting someone's risk based on his/her information with interpretable reasons. Throughout the data mining process, you should be able to give interpretable reasons that why someone has a higher risk level but someone does not.

The primary goal seems okay to you. Then, it may be reasonable for you to start looking at the data. There are two data sets: training data and testing data. What immediately comes to your mind is that you should pick the training data for further study because the risk level of each applicant is unknown in the testing data. How many samples and variables are there in the training data? There are 59381 samples and 127 variables in which one variable is the response, or namely the risk level. You believe it is better to separate the response variable and the other 126 variables by calling the the response variables as 'the response' and the other 126 variables as 'the variables' for simplicity. 

Not all variables are common in nature. Some variables such as 'product_info_2' are not numbers. Although some variables are numbers, they may either be discrete or continuous. Besides, some variables are describing the medical information of the applicants and some are not. It is good to distinguish the nature of different variables before proceeding to a more in-depth data analysis.

The second question that comes next is how you are going to achieve the primary goal. You may consider looking at how the distribution of variables varies across all the risk levels, or looking at how the distribution of risk levels varies across the levels in some categorical variables.