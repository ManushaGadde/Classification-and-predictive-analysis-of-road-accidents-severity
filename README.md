# Classification-and-predictive-analysis-of-road-accidents-severity
<h1>Python</h1>



<h2>Description</h2>
The   main   purpose   of   this  project   is   to   explore   road   accident   data   by   performing   statistical   tests.   Perform   data
visualizations to understand relationships if any. Execute data analysis and data models such as logistic regression,
random  forest,   extreme  gradient  boost, linear   regression,  and  factor   analysis.  Measure  the  performance  of  these
models. And use the output of these models to draw conclusions about accident severity. Finally, determine key
features that drive accident severity so that communities and government authorities can take actionable steps to
reduce accident severity.
<br />


<h2>Languages Used</h2>

- <b>SQL</b> 
- <b>Python</b>

<h2>Tools Used</h2>

- <b>Python Jupyter Notebook</b> 
- <b>phpMyadmin</b> 

<h2>Methodology Used</h2>

- <b>Data Collection</b> 
- <b>Data Cleansing</b> 
- <b>Data Extraction and Storage</b> 
- <b>Data Analysis </b> 
- <b>Data Visualization </b> 

<h2>Data Collection</h2>

- <b>The   source   of   the   data   set   is   from   the   French   Road   Safety   Observatory   "ONISR",  The dataset includes records of every accident that occurred from 2005 to 2019 grouped into four categories in csv
format.
phpMyadmin was  connected   to
Jupyter hub terminal to push the 70 files database. we have created a table for each file because not all
files had the same csv format. After importing the data into the phpMyAdmin, we combined them into 4 tables, each
table representing a category -Characteristics, Vehicles, Places, and Users.

</b> 

<h2>Data Cleaning</h2>

- <b>Cleaning of the data involved reviewing all the dataset attributes. Some years did not have specific columns because
the decisions were made to add additional attributes. Next,pulled all 4 tables into python. Converted them into csv format and merged them into one file.Furthermore,   null   values were replaced    with   zero   for   categorical   columns   and   removed   columns   that   have   over
500,000 or more with null values.</b> 

<h2>Data Analysis</h2>

- <b>Python was used for data analysis. Several packages were imported like pandas, matplotlib, pyplot, numpy, scipy, 
seaborn, sklearn factor analyzer to work on the analysis.Accident severity was determined, the outcome variable, 
was the severity of user injury. The categories of user injury are- 1. Unharmed, 2. Killed, 3. Injured hospitalized, 4. Slightly injured. For our classification models, we divided accident severity into 2 groups- 1(low severity)- 
unharmed and slightly injured. 2- (high severity), killed and injured hospitalized.</b> 

<h2>Data VisualiZation</h2>

- <b>For visualization of our data, Matplotlib was used, one of the most efficient plotting libraries in Python. We chose
histograms to represent the variables influencing the rate of accidents by plotting several factors against the number
of accidents and bar charts to depict the influence of multiple variables on the severity of accidents.</b> 



