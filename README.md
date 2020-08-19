# Online News Popularity Classification Task

Source of the data I used:  [UCI Machine Learning Repository - Online News Popularity](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity).

Original data includes 60 attributes of an article posted online on Mashable.com and 'target' which is number of shares of that article. I've transformed athe target from continous number to a binary variable. By splitting value I chose 1400 which is a median of number of shares.  53,6% of articles had 1400 or more shares and the rest was below that number.

This was a **binary classification task** in which I had to determine if and article got at least 1400 shares. I wanted to use few different machine learning algorithms to compare their accuracy on that data. I chose to use: **Decision Tree**, **Random Forests** and **Multi Layer Perceptron**.

I also wanted to make some of my own variables based on the ones that were in the original data and check if it improves accuracy. Finally I used 45 variables from original data and 12 that I made on my own. These were for example: number of articles posted that day, ratio of number of tokens in content to number of tokens in title, ratio of links to other Mashable articles to all links in the content.

## Technologies used:
- Python 3
- Jupyter Notebook
- pandas 
- matplotlib
- seaborn
- sci-kit learn