---
layout: post
title: Discovering Bokeh Plots and World Bank Data API
---

Matplotlib is great and is definitely an extremely powerful tool. But let's say it - it can be pain sometimes. While you can generate lots of plots with it, sometimes getting a very simple plot to look nice takes a dozen of lines of additional configuration. I also work with R sometimes and I must admit I often found myself doing that nifty trick that I know is not only mine - doing all the data manipulation in Pandas,
saving the file and then loading it in R in order to use ggplot to quickly generate some graphs. While this works I thought there must be something that is faster to use for simple plots - so I decided to take Bokeh plots for a test ride. 

As Bokeh is newer - it is designed to be interactive and targets web browsers (it even has a JS API, but let's leave it for some other post). I'm mentioning interactivity, beacause you can render interactive plots in Jupyter Notebook, which is a tool of choice of many people doing data analysis with Python.

I decided to try it out. And trying out a new plotting library is best with some nice data, so I decided to look for something new to play with. I headed to [this great repo](https://github.com/caesar0301/awesome-public-datasets). After clicking around I ended up at the World Bank API website, which is a gateway to a ton of World Bank's indicators. It is absolutely awesome and you can see it in action in the notebook for this post.

Yes... the notebook. I invite to continue this post by going to the Jupyter Notebook, in which you will see Bokeh and World Bank API in action along with explanations. Oh, and of course, lots of Pandas!

Continue here:

[My notebooks library](https://notebooks.azure.com/pawel-kordek/libraries/pkordek-blog) -> Exploring Bokeh.ipynb