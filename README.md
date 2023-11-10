# Overview

For this project, I will be analyzing Historical Tesla stock data. I got the data from the Nasdaq Stock website and downloaded all of their available data on Tesla as of 1 November 2023. You can find a link to the data in the [useful websites](#useful-websites) section. 

A huge portion of the reason I am doing this project is pure unadulterated curiosity. I find analyzing things fun. Another, and probably more important reason is to showcase my skills. This is a project, that I will have a lot of fun with. I chose Tesla for the simple reason that it is a company I am familiar with. 

At minimum, I will research 2 questions about the data, however one challenge I will very likely have is limiting myself to a reasonable number of questions to research.

[Software Demo Video -- Coming 11 Nov 2023](http://youtube.link.goes.here)

# Data Analysis Results

Is a large difference in the daily range (the difference between high and low prices for the day) good for Tesla closing prices?
: In short, possibly, but many other factors are likely involved. In the days with the most extreme gaps in high and low trading prices, there is a weak positive correlation that gets stronger as you include more data in the analysis, however, even with the most extreme correlation, the split of the days gained verses days lost is very close to 50%, so caution is recommended when trying to apply this in any real format. 

Is a high trading volume good for the closing prices on Tesla stock?
: In short, it seems to play little to no role. There is a very weak negative correlation between increased volume and the price of the stock increasing, suggesting there is a slight tendency for the stock to close at a lower price on those days with a high volume, but the correlation is extremely weak and at best has many other factors involved. 

# Development Environment

* Visual Studio Code
* Python 3.11.5 
* Anaconda
* Pandas
* NumPy
* Jupyter Notebook

# Useful Websites

* [VS Code Download](https://code.visualstudio.com/download)
* [Anaconda Download](https://www.anaconda.com/)
* [Anaconda Install Tutorial](https://www.youtube.com/watch?v=h1sAzPojKMg)
* [Jupyter Notebooks in VS Code tutorial](https://www.youtube.com/watch?v=DA6ZAHBPF1U)
* [Titanic Data Analysis Github Repository](https://github.com/claudiaregio/data-science)
* [Nasdaq Stock Data on Tesla](https://www.nasdaq.com/market-activity/stocks/tsla/historical)
* [NumPy Official Site](https://numpy.org/)
* [Panda's Overview](https://pandas.pydata.org/docs/getting_started/overview.html)
* [10 Minutes to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html#min)
* [Pandas Getting Started Tutorials](https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html)
* [Getting started with Data Analysis with Python Pandas](https://towardsdatascience.com/getting-started-to-data-analysis-with-python-pandas-with-titanic-dataset-a195ab043c77)
* [Kaggle Exploratory Data Analysis with Pandas](https://www.kaggle.com/code/kashnitsky/topic-1-exploratory-data-analysis-with-pandas/notebook)
* [Pandas Official Site](https://pandas.pydata.org/)
* [Oreilly Python for Data Analysis book](https://learning.oreilly.com/library/view/python-for-data/9781098104023/)
* [Geeks For Geeks Pandas DataFrame describe() Method](https://www.geeksforgeeks.org/python-pandas-dataframe-describe-method/#)
* [Cleaning Up Currency Data with Pandas](https://pbpython.com/currency-cleanup.html)
* [Pandas .dt and .day Documentation](https://pandas.pydata.org/docs/reference/api/pandas.Series.dt.day.html)
* [Pandas .day_name Documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.dt.day_name.html)
* [Pandas .month_name Documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.dt.month_name.html)
* [Pandas .isocalendar Documentation](https://pandas.pydata.org/docs/reference/api/pandas.Series.dt.isocalendar.html)
* [StackOverflow extract week as series](https://stackoverflow.com/questions/61636684/pandas-extract-week-of-year-and-year-from-date)
* [Pandas .quarter Documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.dt.quarter.html)
* [Pandas .dayofyear Documentation](https://pandas.pydata.org/docs/reference/api/pandas.Series.dt.dayofyear.html)
* [Python Guides Matplotlib two y axes](https://pythonguides.com/matplotlib-two-y-axes/)
* [Statology How to Create a Matplotlib Plot with Two Y Axes](https://www.statology.org/matplotlib-two-y-axes/)
* [Data Science Parichy Matplotlib – Create a Plot with two Y Axes and shared X Axis](https://datascienceparichay.com/article/matplotlib-create-plot-with-two-y-axes-and-shared-x-axis/)
* [Matplotlib Creating multiple subplots using plt.subplots](https://matplotlib.org/stable/gallery/subplots_axes_and_figures/subplots_demo.html)
* [Stackoverflow How to plot in multiple subplots](https://stackoverflow.com/questions/31726643/how-to-plot-in-multiple-subplots)
* [Geeks for Geeks Plot multiple plots in Matplotlib](https://www.geeksforgeeks.org/plot-multiple-plots-in-matplotlib/#)
* [Geeks for Geeks How to create multiple subplots in Matplotlib in Python?](https://www.geeksforgeeks.org/how-to-create-multiple-subplots-in-matplotlib-in-python/)
* [Web Site Name](http://url.link.goes.here)
* [Web Site Name](http://url.link.goes.here)

# Future Work
## Minimum Viable Product
* Prep Data for analysis
* Maintain data integrity
* Summarize data elements
* Provide visualizations to data
* Answer at least 2 questions about the data

## Future Plans
* Build a tool to allow for custom analysis
* Modify code to allow for importing data from website 
* Allow for analysis of other companies