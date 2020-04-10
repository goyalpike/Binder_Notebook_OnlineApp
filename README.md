# Make Your Notebook as Online-App using Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/goyalpike/Binder_Notebook_OnlineApp/master?urlpath=%2Fvoila%2Frender%2FIdentify_Bear.ipynb)

In this repo, basic steps are shown to deploy your model as an App on [binder plateform](https://mybinder.org/). It basically turn your jupternotebook into an interactive web-browser by using [Voila](https://voila.readthedocs.io/en/stable/index.html). Click on `lauch-binder` button above to get an interactive binder plateform for this repository.


### Steps to do
1. Go to [mybinder.org](https://mybinder.org/)
2. Provide the name of the respository 
3. Path to the jupyter notebook path in the respository. ***Note that*** if the relative path to the file, let us say' is `path-to-file.ipynb` then write the path on [mybinder.org](https://mybinder.org/) as `/voila/render/path-to-file.ipynb`. What it does is that it renders the notebook using `voila` and show you only `Markdown` and `widgets functionality` of the notebook.
4. Click on the lauch, and copy and paste the shown test in your `README.md` file.

### A great source to get basic understanding of it:

* [Chapter 2](https://github.com/fastai/fastbook/blob/master/02_production.ipynb) of the book Deep [Learning for Coders with fastai and PyTorch](https://www.amazon.com/Deep-Learning-Coders-fastai-PyTorch/dp/1492045527) --- [GitHub link of the book](https://github.com/fastai/fastbook)
* [A repository of the source code](https://github.com/fastai/bear_voila)

Thank you, [FastAI team](https://www.fast.ai/). You rock. 
