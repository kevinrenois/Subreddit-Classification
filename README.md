# Project 3 - Web APIs and NLP - Reddit

#### Kevin Renois DSI-R-824


---
## Problem Statement 

My challenge for this projet was to create a model that could successfully distinguish between raw text coming from two very different Reddit pages. The pages I choose to run my experiment on were **r/RoastMe** and **r/ToastMe**. The goal of my model was to be able to take in any text and determine whether it would belong in the RoastMe or ToastMe subreddit pages.


## Executive Summary

r/RoastMe is a page on which users will submit images of themselves and ask commenters to poke fun at them and make jabs at their appearance. Despite the fact that this is a very unusual concept, it seems as though users on the page have a good time which is great for the purposes of my project as there is no shortage of colorful language on this page. r/ToastMe is the exact opposite. Users on this page will submit photos or text asking other commenters to say something kind or uplifting.

I trained and tested several different models during my work, but ended up receiving my best performace metrics from Logistic Regression model using TF-IDF Vectorization with a training accuracy score of 87% and a testing accuracy of 84%.



## Conclusion

I was able to create a successful model using the TF-IDF Vectorization and Logistic Regression, but would like to continue fine-tuning the model to increase it's predict power even more. I think my next steps will be to import even more data - up to twice as much more, and to take more steps with my preprocessing including stemming or lemmatizing the text before training the model.


