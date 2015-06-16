## DAT7 Course Repository

Course materials for [General Assembly's Data Science course](https://generalassemb.ly/education/data-science/washington-dc/) in Washington, DC (6/1/15 - 8/12/15).

**Instructor:** [Kevin Markham](http://www.dataschool.io/about/)

### [Course Project](project/README.md)

Monday | Wednesday
--- | ---
6/1: Introduction to Data Science | 6/3: Command Line and Version Control
6/8: Data Reading and Cleaning | 6/10: Exploratory Data Analysis
6/15: Visualization | 6/17: Machine Learning and APIs<br>**Project Discussion Deadline**
6/22: K-Nearest Neighbors<br>**Project Question and Dataset Due** | 6/24: Model Evaluation Part 1
6/29: Linear Regression | 7/1: Reproducibility and Regular Expressions
7/6: Logistic Regression | 7/8: **First Project Presentation**
7/13: Model Evaluation Part 2 | 7/15: Kaggle Competition
7/20: Decision Trees | 7/22: Naive Bayes and Text Data
7/27: Natural Language Processing<br>**Draft Paper Due** | 7/29: Ensembling
8/3: Clustering, **Peer Review Due** | 8/5: Course Review
8/10: **Final Project Presentation** | 8/12: **Final Project Presentation**

<!--
### Before the Course Begins
* Install [Git](http://git-scm.com/downloads).
* Create an account on the [GitHub](https://github.com/) website.
    * It is not necessary to download "GitHub for Windows" or "GitHub for Mac"
* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
    * If you choose not to use Anaconda, here is a list of the [Python packages](other/python_packages.md) you will need to install during the course.
* Once you receive an email invitation from Slack, join our "DAT7 team" and add your photo.
* Practice Python using the resources below.
* Attend one or both of our Python workshops, depending on your current skill level: [beginner](https://generalassemb.ly/education/intro-to-python-programming/washington-dc/12239) (Saturday 5/16 10am-2pm) and [intermediate](https://generalassemb.ly/education/python-for-data-science-intermediate/washington-dc/12242) (Saturday 5/30 10am-2pm).
* We would like to check the setup of your laptop before the course begins.
    * You can have your laptop checked after the intermediate Python workshop on Saturday 5/30 (2pm-3pm), at the [15th & K Starbucks](http://www.yelp.com/biz/starbucks-washington-15) on Sunday 5/31 (11am-1pm), or before class on Monday 6/1 (5pm-6:30pm).
    * Alternatively, you can walk through the [setup checklist](other/setup_checklist.md) yourself. In this case, please post a message in the "setupchecklist" channel in Slack noting whether or not you had any issues.
-->

### Python Resources
* [Codecademy's Python course](http://www.codecademy.com/en/tracks/python): Good beginner material, including tons of in-browser exercises.
* [DataQuest](https://dataquest.io/): Similar interface to Codecademy, but focused on teaching Python in the context of data science.
* [Google's Python Class](https://developers.google.com/edu/python/): Slightly more advanced, including hours of useful lecture videos and downloadable exercises (with solutions).
* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182): Read through the Overview section for a quick introduction to Python.
* [Python for Informatics](http://www.pythonlearn.com/book.php): A very beginner-oriented book, with associated [slides](https://drive.google.com/folderview?id=0B7X1ycQalUnyal9yeUx3VW81VDg&usp=sharing) and [videos](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj4JXIwMwN1_ss1Tk8wZShEJ).
* [Beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) workshop code: Useful for review and reference.
* [Python 2.7x Reference Guide](https://github.com/justmarkham/python-reference/blob/master/reference.py): Kevin's beginner-oriented guide that demonstrates a ton of Python concepts through short, well-commented examples.
* [Python Tutor](http://pythontutor.com/): Allows you to visualize the execution of Python code.

### Submission Forms
* [Feedback form](http://bit.ly/dat7feedback)
* [Homework and project submissions](http://bit.ly/dat7homework)

-----

### Class 1: Introduction to Data Science
* Welcome from General Assembly staff
* Course overview ([slides](slides/01_course_overview.pdf))
* Introduction to data science ([slides](slides/01_intro_to_data_science.pdf))
* Discuss the [course project](project/README.md)
* Types of data ([slides](slides/01_types_of_data.pdf)) and [public data sources](project/public_data.md)
* Wrap up: Slack tour, submission forms

**Homework:**
* Work through GA's friendly [command line tutorial](http://generalassembly.github.io/prework/command-line/#/) using Terminal (Linux/Mac) or Git Bash (Windows), and then browse through this [command line reference](code/02_command_line.md).
* Watch videos 1 through 8 (21 minutes) of [Introduction to Git and GitHub](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD).
* If your laptop has any setup issues, please work with us to resolve them by Wednesday.

**Resources:**
* For a useful look at the different types of data scientists, read [Analyzing the Analyzers](http://cdn.oreillystatic.com/oreilly/radarreport/0636920029014/Analyzing_the_Analyzers.pdf) (32 pages).
* For some thoughts on what it's like to be a data scientist, read these short posts from [Win-Vector](http://www.win-vector.com/blog/2012/09/on-being-a-data-scientist/) and [Datascope Analytics](http://datascopeanalytics.com/what-we-think/2014/07/31/six-qualities-of-a-great-data-scientist).
* Quora has a [data science topic FAQ](https://www.quora.com/Data-Science) with lots of interesting Q&A.
* Keep up with local data-related events through the Data Community DC [event calendar](http://www.datacommunitydc.org/calendar) or [weekly newsletter](http://www.datacommunitydc.org/newsletter).

-----

### Class 2: Command Line and Version Control
* Command line exercise ([code](code/02_command_line.md))
* Git and GitHub ([slides](slides/02_git_github.pdf))
* Intermediate command line
* Wrap up: Course schedule, office hours

**Homework:**
* Complete the homework exercise listed in the [command line introduction](code/02_command_line.md#homework-exercise). Create a Markdown document that includes your answers and the code you used to arrive at those answers. Add this file to a GitHub repo that you'll use for all of your coursework, and submit a link to your repo using the homework submission form.
* Review the code from the [beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) Python workshops. If you don't feel comfortable with any of the content (up through the "dictionaries" section), you should spend some time this weekend practicing Python. Here are my recommended resources:
    * If you like learning from a book, [Python for Informatics](http://www.pythonlearn.com/html-270/) has useful chapters on strings, lists, and dictionaries.
    * If you prefer interactive exercises, try these lessons from [Codecademy](http://www.codecademy.com/en/tracks/python): "Python Lists and Dictionaries" and "A Day at the Supermarket".
    * If you have more time, try these much longer lessons from [DataQuest](https://dataquest.io/missions): "Find the US city with the lowest crime rate" and "Discover weather patterns in LA".
    * If you've already mastered these topics and want more of a challenge, try solving the second [Python Challenge](http://www.pythonchallenge.com/) and send me your code in Slack.
* If there are specific Python topics you want me to cover next week, send me a Slack message.

**Git and Markdown Resources:**
* [Pro Git](http://git-scm.com/book/en/v2) is an excellent book for learning Git. Read the first two chapters to gain a deeper understanding of version control and basic commands.
* If you want to practice a lot of Git (and learn many more commands), [Git Immersion](http://gitimmersion.com/) looks promising.
* If you want to understand how to contribute on GitHub, you first have to understand [forks and pull requests](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/).
* [GitRef](http://gitref.org/) is my favorite reference guide for Git commands, and [Git quick reference for beginners](http://www.dataschool.io/git-quick-reference-for-beginners/) is a shorter guide with commands grouped by workflow.
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) provides a thorough set of Markdown examples with concise explanations. GitHub's [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) is a simpler and more attractive guide, but is less comprehensive.

**Command Line Resources:**
* If you want to go much deeper into the command line, [Data Science at the Command Line](http://shop.oreilly.com/product/0636920032823.do) is a great book. The [companion website](http://datascienceatthecommandline.com/) provides installation instructions for a "data science toolbox" (a virtual machine with many more command line tools), as well as a long reference guide to popular command line tools.
* If you want to do more at the command line with CSV files, try out [csvkit](http://csvkit.readthedocs.org/), which can be installed via `pip`.

-----

### Class 3: Data Reading and Cleaning
* Git and GitHub assorted tips ([slides](slides/02_git_github.pdf))
* Review command line homework
* Python:
    * Spyder interface
    * Review of list comprehensions
    * Lesson on file reading with airline safety data ([code](code/03_file_reading.py), [data](data/airlines.csv), [article](http://fivethirtyeight.com/features/should-travelers-avoid-flying-airlines-that-have-had-crashes-in-the-past/))
    * Data cleaning exercise
    * Walkthrough of homework with Chipotle order data ([code](code/03_python_homework_chipotle.py), [data](data/chipotle.tsv), [article](http://www.nytimes.com/interactive/2015/02/17/upshot/what-do-people-actually-order-at-chipotle.html))

**Homework:**
* Complete the [homework assignment](code/03_python_homework_chipotle.py) with the [Chipotle data](data/chipotle.tsv), and add a commented Python script to your GitHub repo. If you are unable to complete a part, try writing some pseudocode instead! You have until Monday to complete this assignment.

**Resources:**
* [PEP 8](https://www.python.org/dev/peps/pep-0008/) is Python's "classic" style guide, and is worth a read if you want to write readable code that is consistent with the rest of the Python community.

-----

### Class 4: Exploratory Data Analysis
* Pandas ([code](code/04_pandas.py)):
    * MovieLens 100k movie ratings ([data](data/u.user), [data dictionary](http://files.grouplens.org/datasets/movielens/ml-100k-README.txt), [website](http://grouplens.org/datasets/movielens/))
    * Alcohol consumption by country ([data](data/drinks.csv), [article](http://fivethirtyeight.com/datalab/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/))
    * Reports of UFO sightings ([data](data/ufo.csv), [website](http://www.nuforc.org/webreports.html))

**Homework:**
* Complete "Exercise Three" from today's Pandas script. **Note:** You do not need to submit this assignment.
* Your deadline for discussing your project ideas with an instructor is next Wednesday.
* Read [How Software in Half of NYC Cabs Generates $5.2 Million a Year in Extra Tips](http://iquantny.tumblr.com/post/107245431809/how-software-in-half-of-nyc-cabs-generates-5-2) for an excellent example of exploratory data analysis.

**Resources:**
* Browsing or searching the Pandas [API Reference](http://pandas.pydata.org/pandas-docs/stable/api.html) is an excellent way to locate a function even if you don't know its exact name.
* [What I do when I get a new data set as told through tweets](http://simplystatistics.org/2014/06/13/what-i-do-when-i-get-a-new-data-set-as-told-through-tweets/) is a fun (yet enlightening) look at the process of exploratory data analysis.

-----

### Class 5: Visualization
* Review Python homework with the Chipotle data
* Part 2 of Exploratory Data Analysis with Pandas ([code](code/04_pandas.py))
* Visualization with Pandas and Matplotlib ([code](code/05_pandas_visualization.py))

**Homework:**
* Complete the [homework assignment](code/05_pandas_homework_imdb.py) with the [IMDB data](data/imdb_1000.csv), and add a Python script to your GitHub repo. This assignment is due next Monday. **Note:** A visualization component will be added to this assignment!

**Pandas Resources:**
* To learn more Pandas, review this [three-part tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/), or review these two excellent (but extremely long) notebooks on Pandas: [introduction](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_5-Introduction-to-Pandas.ipynb) and [data wrangling](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_6-Data-Wrangling-with-Pandas.ipynb).
* If you want to go really deep into Pandas (and NumPy), read the book [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do) by the creator of Pandas.
* Here are examples of different types of [joins in Pandas](http://www.gregreda.com/2013/10/26/working-with-pandas-dataframes/#joining), for when you need to figure out how to merge two DataFrames.

**Visualization Resources:**
* Watch [Look at Your Data](https://www.youtube.com/watch?v=coNDCIMH8bk) (18 minutes) for an excellent example of why visualization is useful for understanding your data.
* For more on Pandas plotting, read this [notebook](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_7-Plotting-with-Pandas.ipynb) or the [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation.
* To learn how to customize your plots further, browse through this [notebook on matplotlib](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_4-Matplotlib.ipynb) or this [similar notebook](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb).
* To explore different types of visualizations and when to use them, [Choosing a Good Chart](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf) and [The Graphic Continuum](http://www.coolinfographics.com/storage/post-images/The-Graphic-Continuum-POSTER.jpg) are nice one-page references, and the interactive [R Graph Catalog](http://shinyapps.stat.ubc.ca/r-graph-catalog/) has handy filtering capabilities.
* This [PowerPoint presentation](http://www2.research.att.com/~volinsky/DataMining/Columbia2011/Slides/Topic2-EDAViz.ppt) from Columbia's Data Mining class contains lots of good advice for properly using different types of visualizations.

<!--
### Class 6: Machine Learning and APIs
* Human learning exercise:
    * [Iris dataset](http://archive.ics.uci.edu/ml/datasets/Iris) hosted by the UCI Machine Learning Repository
    * [Iris photo](http://sebastianraschka.com/Images/2014_python_lda/iris_petal_sepal.png)
* Introduction to machine learning (slides)
* Machine learning exercise ([article](http://blog.dominodatalab.com/10-interesting-uses-of-data-science/))
* Course project:
    * [Example projects](https://github.com/justmarkham/DAT-project-examples)
    * Project question exercise
* APIs

**Machine Learning Resources:*
* For a very quick summary of the key points about machine learning, watch [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk) (10 minutes) or read the associated [notebook](http://nbviewer.ipython.org/github/justmarkham/scikit-learn-videos/blob/master/01_machine_learning_intro.ipynb).
* For a more in-depth introduction to machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (It's a free PDF download!)
* For a really nice comparison of supervised versus unsupervised learning, plus an introduction to reinforcement learning, watch this [video](http://work.caltech.edu/library/014.html) (13 minutes) from Caltech's [Learning From Data](http://work.caltech.edu/telecourse.html) course.
* For a preview of some of the machine learning content we will cover during the course, read Sebastian Raschka's [overview of the supervised learning process](https://github.com/rasbt/pattern_classification/blob/master/machine_learning/supervised_intro/introduction_to_supervised_machine_learning.md).
* [The Emoji Translation Project](https://www.kickstarter.com/projects/fred/the-emoji-translation-project) is a really fun application of machine learning.
* Look up the [characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/), and then read about the [67 distinct segments](http://doc.arcgis.com/en/esri-demographics/data/tapestry-segmentation.htm) in detail.
-->
