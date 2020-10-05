# SageMaker Deployment Project

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. 

![img](https://github.com/DanielWeller/Creating-a-Sentiment-Analysis-Web-App/blob/main/Web%20App%20Diagram.svg)

## Project Overview
In this project, I used SageMaker to construct a complete project from end to end. The goal of this project is to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to my deployed model which will predict the sentiment of the entered review.

![img](https://github.com/DanielWeller/Creating-a-Sentiment-Analysis-Web-App/blob/main/love.png)


## Libraries

The list below represents main libraries and its objects
for the project.
- [Amazon SageMaker](https://ap-northeast-2.console.aws.amazon.com/sagemaker/home?region=ap-northeast-2#/landing) (Build, train, and deploy a model)
- [PyTorch](https://pytorch.org) (LSTM classifier)
