## Running in browser (on [mybinder.org](https://mybinder.org/))

Click on Binder icon below.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nd7141/notebooks/master)


After some time (it may take up to 2-3 minutes, be patient) binder will load the environment and you can use familiar Jupyter interface. For example, clicking on `ICLR_Reviews.ipynb`, you will open the notebook with the analysis of ICLR reviews. Note that in the tools like nbviewer or colab _qgrid_ library does not display the tables, so that's why by default the table in the notebook is not visible, and you have to generate the table by running the cells yourself. 

## Running locally 

First, install requirements:
* **openreview**
* **numpy**
* **pandas**
* **qgrid** (better via _conda_, consult [here](https://github.com/quantopian/qgrid#installation) for _pip_ installation)
* **jellyfish** (via _pip_)
* **matplotlib**

Then, download the latest version of the notebook and run it as usual. 

## Highlights

Currently analysis includes:
* Interactive table with all reviews for all papers, which you can sort or filter by the topic, rating, or any other column.

![](https://github.com/nd7141/notebooks/blob/master/figures/interactive_table.png)

* Frequency by topic. 

![](https://github.com/nd7141/notebooks/blob/master/figures/frequency.png)

* Heatmap of confidence over the reviews. 

![](https://github.com/nd7141/notebooks/blob/master/figures/heatmap.png)

* Raw statistics on the reviews such as average review and counts of each score.

![](https://github.com/nd7141/notebooks/blob/master/figures/scores.png)


## Feedback
Any suggestions, questions, and contributions are welcome.
