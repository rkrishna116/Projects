## Data Science Portfolio 

This portfolio consists of several notebooks and projects illustrating the work I have done during my studies (MSc Data Science & Entrepreneurship). It should be noted that some notebooks were not part of my master which I created merely to educate myself. 


###  [NLP: Analyzing WhatsApp Messages](https://github.com/MaartenGr/soan/blob/master/soan.ipynb)
* Analyses done on whatsapp messages between me and my fianciee to surprise her with on our wedding
* Methods:
  * Sentiment Analysis
  * Unique words (using TF-IDF)
  * Topic Modeling
  * Wordclouds, etc.
  
<img src="https://github.com/MaartenGr/soan/blob/master/reddit.png" width="70%"/>

[Repository](https://github.com/MaartenGr/soan) | [Github](https://github.com/MaartenGr/soan/blob/master/soan.ipynb) | [nbviewer](http://nbviewer.jupyter.org/github/MaartenGr/soan/blob/master/soan.ipynb)

---

###  [Optimizing Emté Routes](https://github.com/MaartenGr/Projects/blob/master/Notebooks/RouteOptimization.ipynb)
* Project for the course Business Analytics in the master
* Optimization of managers visiting a set of cities
* Total of 133 cities, max distance 400km with time and capacity constraints
* Thus, a vehicle routing problem
* Methods:
  * Integer Linear Programming
  * Tabu Search
  * Simmulated Annealing
  * Ant Colony Optimization
  * Python

![alt text](https://media.giphy.com/media/FDHO8sbi4hl8qsABDv/giphy.gif)

[Github](https://github.com/MaartenGr/Projects/blob/master/Notebooks/RouteOptimization.ipynb) | [nbviewer](http://nbviewer.jupyter.org/github/MaartenGr/Projects/blob/master/Notebooks/RouteOptimization.ipynb)


---
###  [Predicting and Optimizing Auction Prices](https://github.com/MaartenGr/Projects/blob/master/Notebooks/AuctionAnalysis.ipynb)
* Data received from an auction house and therefore not made public
* Prediction of value at which an item will be sold to be used as an objective measure
* Optimize starting price such that predicted value will be as high as possible
* Methods:
  * Classification (KNN, LightGBM, RF, XGBoost, etc.)
  * Cross-validation based on LOO CV (leave one auction out)
  * Optimization (Genetic Algorithms) 
  * Python

<img src="https://github.com/MaartenGr/Projects/blob/master/Images/auction_result.png" width="70%"/>

[Github](https://github.com/MaartenGr/Projects/blob/master/Notebooks/AuctionAnalysis.ipynb) | [nbviewer](http://nbviewer.jupyter.org/github/MaartenGr/Projects/blob/master/Notebooks/AuctionAnalysis.ipynb)

---

###  [Statistical Analysis using the Hurdle Model](https://github.com/MaartenGr/Projects/blob/master/Notebooks/AuctionAnalysis.ipynb)
* Used Apple Store data to analyze which business model aspects influence performance of mobile games
* Two groups were identified and compared, namley early and later entrants of the market
* The impact of entry timing and the use of technological innovation was analyzed on performance
* Methods:
  * Zero-Inflated Negative Binomial Regression
  * Hurdle model
  * Python, R

<img src="https://github.com/MaartenGr/Projects/blob/master/Images/appstore.png" width="70%"/>

[Github](https://github.com/MaartenGr/Projects/blob/master/Notebooks/AppStoreAnalysis.ipynb) | [nbviewer](http://nbviewer.jupyter.org/github/MaartenGr/Projects/blob/master/Notebooks/AppStoreAnalysis.ipynb)

---

###  [Predict and optimize demand](https://github.com/MaartenGr/Projects/blob/master/Notebooks/simulation.ipynb)
* Part of the course Data-Driven SCM
* Optimizing order quantity based on predicted demand using machine learning methods
* Simulation model was created to check performance of method calculating expected demand
* Additional weather features were included
* Methods:
  * Regression (XGBoost, LightGBM and CatBoost)
  * Bayesian Optimization (Skopt)
  
<img src="https://github.com/MaartenGr/Projects/blob/master/Images/simulation.png" width="70%"/>

[Github](https://github.com/MaartenGr/Projects/blob/master/Notebooks/simulation.ipynb) | [nbviewer](http://nbviewer.jupyter.org/github/MaartenGr/Projects/blob/master/Notebooks/simulation.ipynb)


---

### [Neural Style Transfer]()
* For the course deep learning I worked on a paper researching optimal selection of hidden layers to create the most appealing images in neural style transfer while speeding up the process of optimization
* Code is not yet provided as I used most of the following code from [here](https://harishnarayanan.org/writing/artistic-style-transfer/) and I merely explored different layers
For the course deep learning I worked on a paper researching the optimal selection of hidden layers to create the most appealing images while speeding up the process of optimization. I used some of the code [here](https://harishnarayanan.org/writing/artistic-style-transfer/) and mostly worked on researching which style layers performed best in the neural style transfer task. Notebook will follow. 

<img src="https://github.com/MaartenGr/Projects/blob/master/Images/neural_style_transfer.png" width="594" height="290"/>

---

###  [Predicting Housing Prices](https://github.com/MaartenGr/Projects/blob/master/Notebooks/HousingPrices.ipynb)
* Project for the course Machine Learning
* Participation of the kaggle competition [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/)
* We were graded on leaderboard scores and I scored 1st of the class with position 33th of the leaderboard
* I used a weighted average of XGBoost, Lasso, ElasticNet, Ridge and Gradient Boosting Regressor
* The focus of this project was mostly on feature engineering

<img src="https://github.com/MaartenGr/Projects/blob/master/Images/kaggle.png" width="50%"/>

![alt text](https://github.com/MaartenGr/Projects/blob/master/Images/kaggle.png)

[Github](https://github.com/MaartenGr/Projects/blob/master/Notebooks/HousingPrices.ipynb) | [nbviewer](http://nbviewer.jupyter.org/github/MaartenGr/Projects/blob/master/Notebooks/HousingPrices.ipynb)

---

## FitBit

During my master Data Science and Entrepreneurship I was looking at various ways of leveraging data for the purpose of entrepreneurship. I realized that my FitBit wasn't all that accurate and at times displayed weird values. For that reason I decided to create a model that could predict what my heart rate would have been if it were missing (e.g. due to a bad signal). 

This was the very first project I did during the pre-master. Looking back, there are some things I could have done differently. For example, I did a simple 10-fold CV to test my models which might lead to overfitting as the folds are chosen randomly.

[Repository](https://github.com/MaartenGr/fitbit/) | [Github](https://github.com/MaartenGr/fitbit/blob/master/3.%20The%20Final%20Product.ipynb) | [nbviewer](http://nbviewer.jupyter.org/github/MaartenGr/fitbit/blob/master/3.%20The%20Final%20Product.ipynb)

<img src="https://github.com/MaartenGr/fitbit/blob/master/fitbit.png"/>

---


## To Be Added
* Description of project for Netscalers
