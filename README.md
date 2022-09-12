# JSE

The repository hosts a project for implementing a machine learning model to track and predict ticker stock prices on the JSE. The project is divided into 3 broad stages as follows: 

1. Generating the JSE stock dataset

The first stage is the generation of a dataset consisting of JSE ticker information. This includes web scrapping for ticker trading information from various available public resources. This also includes deploying an implementation for ongoing updating of the ticker information database. 

2. The second stage is building a ML model for predicting stock price movements, possibly using some RNN implementation like LSTM. 

3. The third and last stage will be deployment of the project. Quite likely as a web based app which will constantly monitor model predictions against actual JSE ticker perfomance to inform on-going model maintenance.
