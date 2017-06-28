# Buy the Rumor, Sell The Fact

A capstone project for Udacity's Machine Learning Nanodegree, in which we'll
explore the use of news headlines to predict the S&P 500 Index's behavior.

### Prerequisites

To run the code contained in this repo, please download Jupyter Notebook:
http://jupyter.readthedocs.io/en/latest/install.html

Once installed, make sure that you have the following libraries for Python 2.7x:
* `sklearn`
* `numpy`
* `pandas`
* `matplotlib`

If lacking any of these libraries, you can install using pip:
`pip install <library>`

(If you lack pip, please go here: https://pip.pypa.io/en/stable/installing/)

### Run the Thing

1) Clone the repo to your local machine, ensuring you have all the requisite
data files in the 'data' folder:

* `full_headlines.csv`
* `full_snp.csv`

2) If you want to skip the full_headlines to biz_headlines transformation process,
just change the WRITTEN varible in the first code cell to True. The data folder
should also have `biz_headlines.csv`, which is the output of that cell.

The jupyter notebook is self-contained, but please pay attention to individual
cell code comments and instructions as certain variables may need switching
(e.g., TRUE to FALSE) depending on your desired output. Otherwise, run the cells
and have fun!
