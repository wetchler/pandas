# PANDAS Tutorial
### Berkeley GDSO pre-workshop #3: the `pandas` library (July 2019)
Instructor: Everett Wetchler

### http://bit.ly/gdso-pandas

### Other lessons this week
1. (Monday) - [GitHub and git](https://github.com/geoffbacon/collaboration) (Instructor: Geoff)
1. (Tuesday) - [Jupyter notebooks](https://github.com/charlesfrye/DSW2018-tutorials/tree/master/JupyterNotebookForGreatGood) (Instructor: Charles)
1. ** (Wednesday) - [PANDAS (this tutorial)](https://github.com/wetchler/pandas) (Instructor: Everett) **
1. (Thursday) - [Data visualization](https://github.com/lchen23/GDSO_workshop) (Instructor: Liang)
1. (Friday) - [Stats and machine learning](https://github.com/wetchler/ML) (Instructor: Everett)

### Overview of this hour
1. Quick survey (5m)
1. Local Jupyter/GitHub setup (10m)
1. Hands-on! Pair coding on a real dataset (45m)

### 1. Survey (anonymous / low stakes)
http://bit.ly/gdso-survey or scan this:

<a rel='nofollow' href='https://www.qr-code-generator.com/a1/?ut_source=google_c&ut_medium=cpc&ut_campaign=en_qr_code_create_generisch&ut_content=qr_code_creator_exact&ut_term=qr%20code%20creator_e&gclid=EAIaIQobChMI8fnbkMjL4wIVjh6tBh1nbAkaEAAYASAAEgKQmvD_BwE
            ' border='0' style='cursor:default'></a><img src='https://chart.googleapis.com/chart?cht=qr&chl=https%3A%2F%2Fdocs.google.com%2Fforms%2Fd%2Fe%2F1FAIpQLSc8ZVklQzOxLrgClZIaMJs3AzOf-YcqG44cSMAzpHczw3hHCw%2Fviewform%3Fusp%3Dsf_link&chs=180x180&choe=UTF-8&chld=L|2' alt=''>

### 2. (Hopefully) quick and easy installation
1. Install python on your computer via the "Anaconda" program: https://www.anaconda.com/distribution/
   - A helper to install python and python libraries without a headache
   - Further documentation [here](https://docs.anaconda.com/anaconda/)
1. Install GitHub Desktop: https://desktop.github.com/
   - Hides the gnarly "git" part of GitHub
1. If this all totally fails, use the Binder link below:
   - https://mybinder.org/v2/gh/wetchler/pandas/master?filepath=workbook.ipynb
1. Since Binder is sometimes buggy or slow, you can also try Google Colab:
   - https://colab.research.google.com/

```
FILE_HAPPINESS = 'https://raw.githubusercontent.com/wetchler/pandas/master/data/happiness.csv'
FILE_GDP = 'https://raw.githubusercontent.com/wetchler/pandas/master/data/gdp_cleaned_2018.csv'
```

### 3. Get to work!
1. Goals for the day (in order of priority)
   1. Build an intuition what pandas can do.
      - **In brief, pandas is good for _reformatting_ and _summarizing_ data**
      - It's the foundation of all data analysis in Python
   2. Learn where online to learn more.
      - You will NOT be an expert today, pandas is a swiss-army knife with a tonnn it can do. I've been using pandas for 10 years and STILL regularly consult documentation, google questions etc. Luckily online resources are GREAT, so save your brain space and lean on the internet.
   3. Learn the basics to get up and running.
      1. Reading and looking at data
      1. Filtering data
      1. Aggregating and summarizing
      1. Simple plots

1. Pair coding setup
   1. Pair up and pick a "driver"
   1. Fork this repo
      - What's the new URL? How do you know your new repo was "forked" from this one?
   1. Add your friend as a collaborator
   1. Use GitHub Desktop (or regular git) to get a local copy of your repo
   1. Fire up a new Jupyter notebook in your local repo
   1. After 20 minutes we'll switch "drivers" to practice collaboration via GitHub

### Useful resources for later
  - [Markdown](https://help.github.com/en/articles/basic-writing-and-formatting-syntax) - useful for GitHub README files and Jupyter descriptive cells
  - [PANDAS group-by: split/apply/combine](https://pandas.pydata.org/pandas-docs/stable/user_guide/groupby.html) - wrap your head around this stuff
  * If you want to hunker down, try [this longer, 3 hour pandas tutorial](https://www.youtube.com/watch?v=oGzU688xCUs) or really anything from a [Scipy conference](https://www.youtube.com/playlist?list=PLYx7XA2nY5GfdAFycPLBdUDOUtdQIVoMf)
  * **THE BEST WAY TO LEARN IS TO DO REAL ANALYSIS**. Learn only what you need as you go along. You'll remember things that you *actually use* the best.
  - Footnote: it's not beneath you to use Excel / Google Spreadsheets for simple things!
