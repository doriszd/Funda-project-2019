# Fundamentals of Data Analysis - Tips dataset

![tips](tips_pic.jpg)



Project for Fundamentals of Data analysis at Galway - Mayo Institute of Technology. The aim of this project is to look into "Tips" dataset and show its features through Python packages, seaborn and Jupyter. 

# Author

Doris Zdravkovic

# Tips dataset

Dataset consists of 244 cases which were recorded by a food server during an interval of two and half months in early 1990. Each record includes a day and time, and taken together they show the server’s work schedule. There are 7 variables used in a dataset:

1. the price of total bill in US dollars, including tax.

2. tip given to the waiter, also in US dollars.

3. the sex of customers. The waiter recorded only the sex of customer who paid for the bill (0 = male, 1 = female)

4. it was recorded if there were any smokers in party (0 = Yes, 1 = No)

5. day of the visit. The waiter recorded tips only taken from Thursday to Sunday (3 = Thur, 4 = Fri, 5 = Sat, 6 = Sun)

6. time of the day the customers left the restaurant (0 = Day, 1 = Night). 

7. the size of the party.


# Seaborn

Seaborn is a library for making statistical graphics in Python. It is built on top of matplotlib and closely integrated with pandas data structures.

Here is some of the functionality that seaborn offers:

- A dataset-oriented API for examining relationships between multiple variables
- Specialized support for using categorical variables to show observations or aggregate statistics
- Options for visualizing univariate or bivariate distributions and for comparing them between subsets of data
- Automatic estimation and plotting of linear regression models for different kinds dependent variables
- Convenient views onto the overall structure of complex datasets
- High-level abstractions for structuring multi-plot grids that let you easily build complex visualizations
- Concise control over matplotlib figure styling with several built-in themes
- Tools for choosing color palettes that faithfully reveal patterns in your data

Seaborn aims to make visualization a central part of exploring and understanding data. Its dataset-oriented plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots.For more information about seaborn go to: https://seaborn.pydata.org/introduction.html

# Jupyter

The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.

To install your jupyter notebook, you have to:

1. Enter the startup folder by typing cd /folder_name .
2. Run jupyter notebook command to launch the Jupyter Notebook App. The notebook interface will appear in a new browser window or tab.
3. In the top right corner press New, Python 3 to open new file in jupyter
4. Click ESC and key shortcut m to markdown or double click the text in the cell if you want to edit. 
5. You can run the notebook document step-by-step (one cell a time) by pressing shift + enter.
6. You can run the whole notebook in a single step by clicking on the menu Cell -> Run All.
7. Closing the browser (or the tab) will not close the Jupyter Notebook App. To completely shut it down you need to close the associated terminal.

For more information about Jupyter notebook go to: https://jupyter.readthedocs.io/en/latest/


# Downloading the repository

1. Go to GitHub.
2. Navigate to the main page of the repository:https://github.com/doriszd/Funda-project-2019
3. Under the repository name, click Clone or download
4. Save the repository to a local folder location on your computer.
5. Navigate to your target directory in the command line
6. To add new content on gitHub type add .
7. Type git commit -m "Write a message here"
8. To send it to gitHub type git push

# About this Project

There are 5 main aims in this project:

##### 1. The first aim of this project is to determine the relationship between the total bill and the tip. It would be interesting to see what percent of money customers leave to tip their waiter.

##### 2. Determine who gives higher tips, men or women, taking into consideration total bill and their tip.

##### 3. Another aim is to analyse the day of the week considering the amount of the tip. Only tips from Thursday to Sunday have been recorded in this dataset. 

##### 4. Look into the relationship between the time of the day (day or night) when customers left the restaurant and the tip.

##### 5. See the relationship between size of the group and the tip.¶

# Conclusion

Results showed that the average bill is 19.78 dollars, and the average tip is 2.99 dollars (15.11%). Since average tip in USA is between 15% - 20% depending on the location, type of the restaurant and other attributes we can say that the findings of this research are similar to what has been proved before in other researches. We have to have in mind that this data was recorded in 1990's which might be the reason why it corresponds to the lower end of this range (15%), especially because the amount of tip has been increasing in last couple of decades. Although the average tip is in expected range (15-20%) we have to take into consideration that the restaurant where data was recorded was in suburban shopping mall, so slightly lower average tip is not that surprising. The results might have been different if data was recorded in 5 star restaurant.

Full analysis on tips find here: 

https://github.com/doriszd/Funda-project-2019/blob/master/Tips%20analysis.ipynb

# Table of contents

Introduction
1. Previous research findings on tips
2. Aims of this research
3. "Tips" dataset
4. Methods
- Pandas
- Seaborn
- Matplotlib
- Jupyter notebook
- GitHub
5. Descriptive analysis
- Variables "total_bill", "tip" and "size" described
- Variable "smoker" described
- Variable "sex" described
- Variable "day" described
- Variable "time" described
- Variable "size" described
- Seaborn pair plot
6. Regression analysis
7. Interpretation



# References

https://www.researchgate.net/publication/23748773_The_implications_of_tipping_for_economics_and_management
https://scholarship.sha.cornell.edu/cgi/viewcontent.cgi?referer=&httpsredir=1&article=1036&context=articles
https://pdfs.semanticscholar.org/20f8/54f6aad4533f2069a023ebc32ec78c43dd92.pdf
https://ecommons.luc.edu/cgi/viewcontent.cgi?article=4067&context=luc_theses
https://scholarship.sha.cornell.edu/cgi/viewcontent.cgi?article=1102&context=articles
https://learningenglish.voanews.com/a/who-pays-better-tips-men-or-women/3941732.html
https://www.tripadvisor.ie/Travel-g191-s606/United-States:Tipping.And.Etiquette.html
https://www.eater.com/2017/1/24/14365152/best-tips-servers-sunday
https://www.monster.com/career-advice/article/waiters-earn-tips-0217
http://money.com/money/3394185/tipping-myths-realities-history/
https://www.motherjones.com/environment/2016/04/restaurants-tipping-racist-origins-saru-jayaraman-forked/
https://core.ac.uk/download/pdf/145015505.pdf
https://statistics.laerd.com/statistical-guides/descriptive-inferential-statistics.php
https://pandas.pydata.org/index.html
https://stackabuse.com/beginners-tutorial-on-the-pandas-python-library/
https://elitedatascience.com/python-seaborn-tutorial
https://matplotlib.org/
https://jupyter-notebook.readthedocs.io/en/stable/notebook.html
https://towardsdatascience.com/intro-to-descriptive-statistics-252e9c464ac9
https://en.wikipedia.org/wiki/GitHub
https://apiumhub.com/tech-blog-barcelona/using-github/
https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.shape.html
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.iloc.html
https://towardsdatascience.com/hitchhikers-guide-to-exploratory-data-analysis-6e8d896d3f7e
https://www.investopedia.com/terms/d/descriptive_statistics.asp
https://dfrieds.com/data-analysis/value-counts-python-pandas
https://matplotlib.org/3.1.1/gallery/pie_and_polar_charts/pie_features.html#sphx-glr-gallery-pie-and-polar-charts-pie-features-py
https://towardsdatascience.com/hitchhikers-guide-to-exploratory-data-analysis-6e8d896d3f7e
http://seaborn.pydata.org/generated/seaborn.pairplot.html
https://www.thebalancesmb.com/what-is-simple-linear-regression-2296697
https://www.surveygizmo.com/resources/blog/regression-analysis/
http://seaborn.pydata.org/generated/seaborn.regplot.html
http://seaborn.pydata.org/generated/seaborn.lmplot.html
https://seaborn.pydata.org/tutorial/regression.html