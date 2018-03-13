# Machine Learning

(!) = Definitely needs to be reworded or explained more

Standardized CodeRabbit introduction

Introduction
------------------------------------------------------------------------------
* Data is becoming more easily available
* Data sets are becoming larger
* Both the private companies and government institutions are becoming better at
  generating, streaming, and storing data
 
* We need algorithms/models (!) that can help us gain insight from increasingly 
  large and complex datasets

* Machine Learning is a discipline that studies how computers can automatically 
  analyze and draw conclusions from data. (!)
  * Even though technically it is a subfield of mathematics and does not 
    necessarily need to use computers.

* Examples (I'll probably choose three):
  * Facebook and Snapchat use machine learning to build technology that can 
    recognize faces
  * Online advertisers use machine learning to offer you the products you are 
    most likely to buy
  * Large banks use machine learning to detect credit fraud
  * Self-Driving cars use machine learning to saftely navagate through roads.
  * Hedge Funds use machine learning to predict movements in the stock market.
  * Netflix uses machine learning to recommend movies and TV shows you might 
    like.

Body
------------------------------------------------------------------------------
I'm actually not sure where to go with the body for the first video's transcript...

Here are some potnetial options:

1. How are institutions getting more data?
    * Many free applications on both your browser and your phone are designed to
      record and store your data
      * retweets, likes, views, right swipes, your location, and even your tax 
        return information are all saved by these applications
    * Some companies store your credit card information, social security number,
      and spending history
      * This is why data breaches like those at Target and Experian are so
        dangerous (!)
    * Some countries have strong privacy laws that require companies to keep
      your data secure and anonymous (!), others do not
      * This is a very controversial issue
     
2. The Inner workings of a machine learning model
    * There are two types of models:
      * Classification - We try to predict a category
        * Is an email important or spam?
        * Is this a picture of a cat or a dog?
      * Regression - We try to predict a number
        * How much does this house cost?
        * What is this person's credit score?
    * We can have algorithms generate these models for us
      * Most algorithms use calculus and matrix algebra to create models
      * luckily, most programming languages have libraries or packages that allow
        us to use these algorithms while the pre-packaged code deals with the
        heavy lifting in the background. (!)
  
  3. What are the steps involved in training a machine learning model?
      * Aquire and preprocess data
        * Getting data
          * Companies that provide servies or applications can record user
            or client activity (See retweets, likes, etc. from earlier)
          * Governments often get data through surveys
          * Buy data from large companies
          * There is even data available for free online
            * [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php)
            * [Kaggle](https://www.kaggle.com/datasets)
            * [US Government](https://www.data.gov/)
            * Web Scraping
        * Preprocessing Data
          * Many models require data to be in a specific format before they can
            work on a dataset.
          * It is very common for models to require tabular data.
            * Tabular data is data that can be stored in a table or spreadsheet
              with one column for each variable and one row for each observation.
            * Some specialized models can take in non-tabular data with very little
              intervention
              * Convolutional Neural Networks can train on pictures
              * Recurrent Neural Networks can train on sounds
      * Train a model
        * See Regression vs Classification from earlier
        * There is a wide array of models that are useful for different circumstance
          * Linear Regression
          * Logistic Regression
          * K Nearest Neighbors
          * Decision Trees
          * Support Vector Machines
          * Random Forests
          * Extreme Gradient Boosting
          * Neural Networks
          * This does not include Unsupervised Learning Algorithms
            * K Means Clustering
            * Heirarchical Clustering
            * Singular Value Decomposition
            * Principle Components Analysis
      * Interpret results and draw conclusions
        * The two most common metrics machine learning researchers and engineers
          use to evaluate the quality of a model's results are precision and
          recall.
          *  Precision 
        * Models can suffer from overfitting
          * Drawing conclusions that are either too complex or based on too
            small an amout of data
        * Models can be misinterpreted
          * Correlation does not guarantee causation
            * (I'm sure we could find some interesting correlation from the 
              internet to post here)
        * At the end of the data, the only purpose of machine learning is to
          provide information to people or software so they can make better
          decisions
          
4. Something else you think would be better to talk about in an introductory
   video.
     
Conclusion
-------------------------------------------------------------------------------
Machine Learning is pretty cool.
