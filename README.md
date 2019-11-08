# ecommerce_site_a/b_testing
- Read a dataframe, cleanse data and unwanted data.
- Perform A/B testing by running simulations across sample data using bootstrapping technique and defining hypothesis tests to reject/ accept null hypothesis based on p value determination and comparison with null values. Note: Hypothesis is defined based on the conversion rate comparison between old and new e-commerce sites
- Apply regression model to the data depending on the dependent variable outcome determination and determining what independent variable had max impact on the response i.e. conversion rate (probability of leading to purchase) of people visiting new vs old e comm website to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [StatsModels](https://www.statsmodels.org/stable/index.html)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

Install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook finding_donors.ipynb
```  
or
```bash
jupyter notebook finding_donors.ipynb
```

This will open the iPython Notebook software and project file in your browser.

# Important questions answered
- Null/ Alternative hypothesis determination 
- p- value determination for A/B testing vs Regression model approach
- Explanatory variable with highest impact on Conversion rate 

# Sources
https://stackoverflow.com/questions/12146914/what-is-the-difference-between-linear-regression-and-logistic-regression 

https://classroom.udacity.com/nanodegrees/nd002/parts/bb0cbeb6-d3f8-4bae-9dc3-4abba3823e54/modules/82c7c576-88f5-43b6-80fc-c53378527a2d/lessons/b7ae43e6-204a-4816-a177-6c75115cae5f/concepts/f4fcfbc9-30ea-4086-b732-75a278dcdb59 

https://classroom.udacity.com/nanodegrees/nd002/parts/bb0cbeb6-d3f8-4bae-9dc3-4abba3823e54/modules/82c7c576-88f5-43b6-80fc-c53378527a2d/lessons/49462f74-b030-4bb6-bf67-8281c9181404/concepts/df69d406-341a-4dd1-827d-31a85e9d8ac1

https://matplotlib.org/gallery/lines_bars_and_markers/scatter_symbol.html?highlight=scatter%20symbol

https://stackoverflow.com/questions/53148935/one-sample-test-for-proportion

https://www.statisticssolutions.com/what-is-logistic-regression/
