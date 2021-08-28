Hosted Presentation in Tableau: https://public.tableau.com/app/profile/veerpal/viz/Instagram_Analysis_ML/MLStory?publish=yes


# Detect top trending topics and hashtags

-   [Table of contents](#table-of-contents)

-   [Description](#description)

-   [Key Features](#key-features)

-   [Development Process](#developement-process)

-   [The Output](#the-ouput)

-   [Installation and Usage](#installation-and-usage)

-   [Credits, tools and other references](#credits-tools-and-other-references)

## Description

The expectation with this project is to gauge how well an influencer engages with it's followers, 
what trends are occuring with the usage of hashtags and the sentiments of the posts. 
Also, look at the various relationships between likes, comments, followers, # of posts and so forth. 

## Key Features

Key attributes of the project: Instagram, Instagramy, NLTK- SentimentIntensityAnalyzer

## Development Process

Utilized Python-Jupyter Notebooks, Tableau, & Excel to analyze, visualize, and assess sentiment analysis. 

## The Output

Tableau Story with Instagram Users (29 users), recent 12 posts, sentiment analysis on each post, 
and an overall analysis on the average sentiment analysis. 

## Installation and Usage
Jupyter Notebook:
Instagramy Library in conjunction with pandas, time
https://pypi.org/project/instagramy/#Instagram-Post-details 
-Pulled user profile data
-Pulled posts & hashtags
Wordcloud, Pillow, matplotlib, numpy, collections
Machine Learning Portion: Utilize Natural Language processing libraries to assess sentiments of each post
Tried/tested: sklearn model; with GradientBoostRegressor, in conjunction with:Matplotlib, pandas, tensorflow, numpy, re, seaborn, %matplotlib inline
Nautal Language Processing: Pandas, Spacy, nltk, os, string, nltk.stem - WordNetLemmatizer, nltk.sentiment - SentimentIntensityAnalyzer
Tableau



```bash
Git clone https://github.com/speedracer05/Final_Project.git
```
### Install the required libraries.
```bash
pip install beautifulsoup4, requests
pip install requests
pip install selenium
```

```bash
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
import numpy as np
from sklearn.ensemble import RandomForestRegressor
import bs4 import BeautifulSoup
import requests
import re
```

## Credits, tools and other references
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin at quam et orci
ultricies ornare. Fusce nec magna aliquet, congue ante in, lobortis augue. Nunc
hendrerit massa ut risus molestie egestas.
