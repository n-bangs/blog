---
layout: post
title: Project Luther
---

# Project Luther  

Project two for Metis (Project Luther) was centered around linear regression
techniques. The most valuable lesson learned here was the difficulty 
of scraping the web effectively. My end goal was to take the production
budget, genre, MPAA rating, and season of release and use a model to predict
the domestic total gross. Let's take a look at how this worked out.  
# 1. Scraping  
The majority of my time was spent scraping the web. Primarily using 
BeautifulSoup, I scraped Boxofficemojo.com and IMDb. I gathered information
for over 14,000 films. Unfortunately, after cleaning and filtering I was 
only able to use about 4,000 of these in my modeling.  
# 2. Modeling  
After testing out many regressors, both linear and non-linear, I ended up 
sticking with Linear Regression. My best R-squared was .44 (not so great!). 
According to my model, the best way to maximize domestic total gross is to 
make a rated R comedy and release it in the Winter. A close second was an 
action/adventure, rated R, released in the Summer.   
# 3. Future Steps  
I would like to further analyze the effect of a director's experience on the 
domestic gross, and I would also like to expand my usable data set - 4,000
movies proved to be too few to create a good predictive model.
