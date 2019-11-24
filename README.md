# Wrangle and Analyze Twitter Data 
This repository holds a Jupyter notebook where I performed data cleaning, analysing and visualization on tweet data of [@dog_rates](https://twitter.com/dog_rates) also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs), with Python.
<p align="center"><img src="https://cdn10.bostonmagazine.com/wp-content/uploads/sites/2/2017/04/WeRateDogs.jpg" width=250></p>

## Overview
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though, almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because ["they're good dogs Brent."](http://knowyourmeme.com/memes/theyre-good-dogs-brent) WeRateDogs has over 4 million followers and has received international media coverage.

## Description
I analysed this tweet archive data by following steps. 

1. Using python and Pandas, I read csv, tsv and json files which contain the archives of @dog_rates account. Next, I accessed each dataframes and defined the data's quality and tidiness issues. 
2. I clearned those quality and tidiness issues using python and Pandas for further analysis, removing unneeded columns/rows and wrongly captured data in the wrangling process, and tyding up by combining those three dataframes. 
3. Using matplotlib and python, I conducted exploratory and explanatory data analysis.
