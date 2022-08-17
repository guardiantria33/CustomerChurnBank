# What is Customer Churn?
![What-is-Customer-Churn-1 (1)](https://user-images.githubusercontent.com/102755372/185093374-c105d172-fb8d-4aae-8023-12771c0a1773.jpg)

Customer churn refers to the natural business cycle of losing and acquiring customers. Every company — no matter the quality of its products or customer service — experiences churn. Generally speaking, the less churn you have, the more customers you keep.
# Why Customer Churn?
Understanding your customer churn is essential to evaluating the effectiveness of your marketing efforts and the overall satisfaction of your customers. It’s also easier and cheaper to keep customers you already have versus acquiring new ones. Due to the popularity of subscription business models, it’s critical for many businesses to understand where, how, and why their customers may be churning.
# How to Mitigate or Reduce Customer Churn?
1. Target the right audience
2. Offer incentives
3. Analyze why churn occurs
4. Know Your Customer
5. Pay attention to complaints

# Objective
1. Predicting customer churn with 2 models : Random Forest and KNN
2. Find the important feature that can reduce or mitigate customer churn
3. Give recommendation action to Bank

# About The Data Set
The data used in this repository is an Credit Card Customer dataset available through this [Link](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers?datasetId=982921&sortBy=voteCount)

# The Best Model : Random Forest VS KNN
![RF VS KNN](https://user-images.githubusercontent.com/102755372/185092396-9245288e-6c10-491e-a406-0dcd03d9e465.png)

# Conffusion Matrix
![conffusion matrix](https://user-images.githubusercontent.com/102755372/185092818-5fc75e60-b06d-4806-85c7-49c318f7e3e3.jpg)

# Feature Importance
![feature importance](https://user-images.githubusercontent.com/102755372/185093002-43724476-7b7e-494f-8f4a-3fe2dc48f665.jpg)

# Recommendations
1. Total_Trans_Amount
* if Total_Trans_Amount is larger, this will increase the bill and interest on credit card payments (if the customer cannot pay on time) this can result in the customer running away from his responsibilty, although there are risks if the customer does not fulfill his responsibilty such as a blacklist. The thing that can be done by the bank is to provide a credit card payment relief program if the customer has entered the fail to pay category, so this will benefit both parties.
* Banks can provide credit card promos if customers make large transactions, such as cash back, discount, earn points to be exchanged for hotel stays or flights or changing customer category to privilage or priority customer if they have big amount.
2. Total_Revolving_Balance
* Revolving balance is called by If you don’t pay the balance on your revolving credit account in full every month, the unpaid portion carries over to the next month. To prevent swelling of revolving credit card balances for customers which will later have an impact on customers leaving is to improve the system on Know Your Customer investigations, Conducting due diligence, Setting accurate credit limits and Using a reputable credit reference agency for more in-depth due diligence can give you invaluable insight and alert you to any potential red flags.
3. Total_Relantionship_Count
* change or add credit card products according to customer needs, such as if the customer is married, the bank provides health or education insurance benefits according to the credit card limit given or the number of transactions made. or for people who like to travel, banks can make special credit cards for people who have a hobby of traveling with the benefit of collecting points from each traveling transaction. points that have been collected can be exchanged for hotel accommodation or airline tickets. so that if customers have credit cards according to their respective profiles this can reduce the customer churn rate
