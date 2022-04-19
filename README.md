# EDA-on-Facebook-Dataset
![](https://github.com/TithiHunka/EDA-on-Facebook-Dataset/blob/main/Images/download.png)
## 1. Introduction
Facebook became the largest social networking site in the world. There are billions of active users, and about half of it use every day.
Facebook generates Tb's of data everyday through numerous users as the site has many components, like Customer information,Timeline contents ,Friends ,Chat data, Status, News Feed, Reactions, Comments and many more .
This case study demonstrates that our proposed decisions and insights are capable of providing a good strategy for business widening using generated sample of data.

## 2. Problem Statement
* This era has been under the influence of Social Media for the past few years.

* With the rise in the popularity of the Facebook application, it is very necessary to stay updated and they are trying really hard.

* Every user uses application in different ways. Let's say sending friend requests, sending likes, comments etc.

* This case study considers Sample Facebook data to study and analyze these differences, find hidden patterns and usage behavior of users and use this pattern for improving their application and the user experience.

* To Study the reason of decreasing Facebook Users day by day.

* To Study the reason of less logins from web.

## 3. Inserting and Importing Liberaries

`!pip install -q datascience`

`!pip install -q pandas-profiling`

`import pandas as pd` 

`from pandas_profiling import ProfileReport` 

`import numpy as np`                                                  

`import matplotlib.pyplot as plt`     

`import seaborn as sns`           

`%matplotlib inline`

`import scipy as sp`          

## 4. Data Acquisition & Discription
|Id|Feature|Description|
|:--|:--|:--|
|01| userid                 | A numeric value uniquely identifying the user.|
|02| age                    | Age of the user in years.|
|03| dob_day                | Day part of the user's date of birth.|
|04| dob_year               | Year part of the user's date of birth.| 
|05| dob_month              | Month part of the user's date of birth.|
|06| gender                 | Gender of the user.| 
|07| tenure                 | Number of days since the user has been on FB.|
|08| friend_count           | Number of friends the user has.|
|09| friendships_initiated  | Number of friendships initiated by the user.|
|10| likes                  | Total number of posts liked by the user.|
|11| likes_received         | Total Number of likes received by user's posts.|
|12| mobile_likes           | Number of posts liked by the user through mobile app.|
|13| mobile_likes_received  | Number of likes received by user through mobile app.|
|14| www_likes              | Number of posts liked by the user through web.|
|15| www_likes_received     | Number of likes received by user  through web.| 

## 5. EDA
### 5.1)plotting number of users at different tenure groups
![image](https://user-images.githubusercontent.com/97185610/163922424-27e13e10-e526-4b2c-ba3d-b40d353037b1.png)
### 5.2)plotting of number of days spent in facebook by different age groups
![image](https://user-images.githubusercontent.com/97185610/163922855-b0684040-f134-43ab-ada8-88c5dc275d01.png)
### 5.3)Number of users (Male and female ratio)
![image](https://user-images.githubusercontent.com/97185610/163923564-ab6d96cb-7b57-4692-b407-65486e9806b1.png)
### 5.4)Averge friends_count according to gender
![image](https://user-images.githubusercontent.com/97185610/163923658-ba13e314-8837-4fd0-bf9b-421cc8e39ae6.png)
### 5.5)Averge friendships_initiated according to gender
![image](https://user-images.githubusercontent.com/97185610/163923700-71e04823-4c0e-44b7-b877-ef95cd41cf5d.png)
### 5.6)Maximum Number of users of particular age group
![image](https://user-images.githubusercontent.com/97185610/163923773-27643936-b8b7-4bd3-b707-186fb8d969aa.png)
### 5.7)To analyse the friend_count in reference to age groups
![image](https://user-images.githubusercontent.com/97185610/163923895-0db82ff3-7ad5-4e4e-a59d-421c2a6377ac.png)
### 5.8)Which age group initiates friendship more
![image](https://user-images.githubusercontent.com/97185610/163924057-4205a05d-bbd1-4305-b60f-caf624ed82ae.png)
### 5.9)Most active age_group
![image](https://user-images.githubusercontent.com/97185610/163924089-6936348f-d993-45fa-aa46-a86d2aa3c6d4.png)
### 5.10)Mobile likes received Vs WWW likes received(Male and  Female)
![image](https://user-images.githubusercontent.com/97185610/163924268-d2af335a-6cdd-4764-bd87-9179650f5b34.png)
### 5.11)Mobile likes Vs WWW likes(Male and  Female)
![image](https://user-images.githubusercontent.com/97185610/163924340-24efc236-c8aa-4a79-876f-c067e9e43ae0.png)
### 5.12) Most Active users(Males or Females)
![image](https://user-images.githubusercontent.com/97185610/163924518-59b3f7da-0f7c-46db-8cb7-fee205b6a28a.png)
### 5.13) Top 10 users getting highest likes received
![image](https://user-images.githubusercontent.com/97185610/163924711-a272ee3e-9340-48e8-af2e-b874963de07e.png)
### 5.14) Top 10 users having highest Tenure
![image](https://user-images.githubusercontent.com/97185610/163924783-f0542636-5b97-45c7-bcb1-c14c2d6af5f4.png)
### 5.15) Top 10 users who initiated Maximum Friendships
![image](https://user-images.githubusercontent.com/97185610/163924852-c0da0b71-038b-4d08-8947-3ad518d76421.png)

Summarization
-------------
## 1)Conclusion:
1)Maximum users tenure is less than 1 year.

2)Most of the new users joined in 1 year period.

3)Average tenure(days) of all the age groups is different and heighest for age group 20-30.

4)Male and female Users ratio is approximatly 40:60.

5)Friend count for Female is higher than male average friends count.

6)Friendship initiated by Males are higher than Females.

7)Maximum users are of age group 21-30(28.9%) followed by age group 10-20(25.0%)

8)Friends count of age group 10-20 is highest followed by age group 21-30 .

9)Average Friendship initiated by age group 10-20 is highest followed by age group 21-30.

10)Most active age group is below 40.

11)mobile is the preferred choice for uses to use facebook then web.

12)Mobile likes and www likes received by female users is more than males.

13)Mobile Application of facebook is more demanding across all age groups and every gender.

14)Females are more active Users than males.

15)passive Users are 1.7%

16)Most active people on facebook are of age <40 and then interest gradually decreases.


## 2)Actionable Insights
* As we can see Facebook is doing Great Job.
But we can target Age Group below 40 for more usage and also focus Middle aged people as they are less active.
* Focus on males and Launch more services and programs for Females.
* Design more attractive and interactive mobile application and and inhance web based services.

