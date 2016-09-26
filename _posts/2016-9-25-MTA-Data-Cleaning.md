---
layout: post
title: MTA Data Cleaning
---

For Project One at Metis we were tasked with using the MTA Turnstile data to 
make conclusions about how to optimize canvassing for e-mails in New York. 
The most important part of this project for me was its lesson in data cleaning.
The turnstile data was insidiously error-ridden and for this reason I will be 
dedicating most of this post to just the cleaning process.  

# 1. The Data

Naturally, the first step is to gather the data you are going to use.
This can be found at the [MTA Website](http://web.mta.info/developers/turnstile.html).
For this example I will be cleaning the data from the weeks of [September 03, 
2016](http://web.mta.info/developers/data/nyct/turnstile/turnstile_160903.txt), 
[September 10, 2016]
(http://web.mta.info/developers/data/nyct/turnstile/turnstile_160910.txt), and 
[September 17, 2016](http://web.mta.info/developers/data/nyct/turnstile/turnstile_160917.txt).
