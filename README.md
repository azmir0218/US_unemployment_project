# Analysis of US unemployment Data of the last three recessions

# Overview: 
For this project we cleaned and extracted data from our data source using Jupiter Notebook. By doing this, it allowed us to compare unemployment rates to various contributors . Some of the categories we looked at  were education, gender, race and ethnicity. We had access to 20 years worth of data but focused on our past recessions. 
### Importance:
The purpose of the project was to demonstrate our skills in order to analyze and better understand a data set. As a group we decided to explore data regarding unemployment. Our data provided a baseline to what factors contribute to the jobless rate in the US for the last 20 years. This will help identify gaps in the labor participation and how to address issues of diversity, equity, and inclusion (DEI) and the future of employees in the US labor force. 
### Problem Statement:
To predict the likelihood of unemployment during times of recession in the US based on one’s race and ethnicity, educational attainment across the groups, and the degree of discrimination of gender encountered in the workplace. 
# Program installation: 
###  Jupiter Notebook  and Python:
Jupiter notebook is a web application that allows you to create and share live code. It allows you to also share visualizations, equations and text. Some of its uses include data cleaning and viewing, transformations, and statistical modeling.  Jupiter supports Julia, Python, and R. 

A basic level of  knowledge of Jupyter notebook and Python was needed in order to complete this project. We did some basic things such as reading a csv. file, cleaning the file , making data frames, and using data frames to make graphs. 
### Installing Juypter notebook
There are different ways you can install Jupiter notebook, We can use either mamba or conda. 
Installation with mamba: 
In you terminal or on your command line type:

<img width="592" alt="Screen Shot 2021-10-28 at 6 29 10 PM" src="https://user-images.githubusercontent.com/89117449/139351546-3a598812-30ee-4267-b106-1c26d1b86547.png">

Installation using conda:
In your terminal of command line type:

<img width="594" alt="Screen Shot 2021-10-28 at 6 29 33 PM" src="https://user-images.githubusercontent.com/89117449/139351637-771a2030-f578-4e53-892b-a368f1a69738.png">

Run Jupyter Notebook 
Just run the following in your terminal or command line!
<img width="592" alt="Screen Shot 2021-10-28 at 6 33 23 PM" src="https://user-images.githubusercontent.com/89117449/139351643-f42b396d-2700-4c4e-aad4-012ab49ef2da.png">

If you are unable to install Jupyter notebook :

Jupyter allows you to try Jupyter Notebook on your browser!
# Data Source:
For our dataset, we used the Bureau of Labor Statistics unemployment data form each recession period within the last 20 years 

https://data.bls.gov/cgi-bin/surveymost?ln

# Data Manipulation  and analysis:
The following include snippets of what we did to clean and analyze the data. 

### Reading / Data frame: 

<img width="899" alt="Screen Shot 2021-10-28 at 7 09 12 PM" src="https://user-images.githubusercontent.com/89117449/139351763-66d3117e-f2fa-4278-8d9d-c87998ca6391.png">

### Cleaning: 

<img width="927" alt="Screen Shot 2021-10-28 at 7 10 02 PM" src="https://user-images.githubusercontent.com/89117449/139351805-8ca8e79d-bb1c-4b84-b4fb-7802833497f8.png">

### Visuals: 

<img width="697" alt="Screen Shot 2021-10-28 at 7 14 43 PM" src="https://user-images.githubusercontent.com/89117449/139351830-da9ef9e3-5fed-42eb-ad08-22166c6dc3bc.png">
<img width="684" alt="Screen Shot 2021-10-28 at 7 15 23 PM" src="https://user-images.githubusercontent.com/89117449/139351847-cb1ab231-81ad-4580-9633-3a7bfc5e9c99.png">

### Analysis: 

<img width="865" alt="Screen Shot 2021-10-28 at 7 39 08 PM" src="https://user-images.githubusercontent.com/89117449/139351864-257bdd85-834a-47cd-a280-da1ff8dd79cd.png">

# Findings: 
All of our findings came directly from the graphs. 
### Overall unemployment: 

* Unemployment in the Dot-Com Recession steadily climbed from 4.3% in March 2001 to 5.5% in November 2001.
* Unemployment in the Great Recession began at 5% in December 2007 and peaked at 9.5% in June 2009.
* Unemployment in the COVID Recession began at 3.5% in February of 2020 and exploded to 14.8% in April 2020.

### Gender Unemployment:
##### Dot-Com
* Women’s unemployment rate in the Dot-Com Recession began at 3.6% in March 2001 and peaked at 4.8% in November 2001.
* Men’s unemployment in the Dot-Com Recession began at 3.8% in March 2001 and peaked at 5% in November 2001.
##### Great Recession
* Women’s unemployment rate in the Great Recession began at 4.4% in December 2007 and peaked at 7.6% in June 2009.
* Men’s unemployment rate in the Great  Recession began at 4.4% in December 2007and peaked at 9.9% in June 2009.
##### COVID
* Women’s unemployment rate in the COVID Recession began at 3.1% in February 2020 and peaked at 15.5% in April 2020.
* Men’s unemployment rate in the COVID Recession began at 3.2% in February 2020 and peaked at 13.1% in April 2020.

### Race Unemployment:
##### Dot-Com
* The White unemployment rate in the Dot-Com Recession began at 3.7% in March 2001 and peaked at 4.9% in November 2001.
* The Black unemployment rate in the Dot-Com Recession began at 8.3% in March 2001 and peaked at 9.8% in November 2001.
* Asian unemployment rate was not tracked by the Bureau of Labor Statistics until 2013.
* The Hispanic unemployment rate in the Dot-Com Recession began at 6.2% in March 2001 and peaked at 7.3% in November 2001.
##### Great Recession
* The White unemployment rate in the Great Recession began at 4.4% in December 2007 and peaked at 8.7% in June 2009.
* The Black unemployment rate in the Great Recession began at 9% in December 2007 and peaked at 14.8% in June 2009.
* The Asian unemployment rate in the Great Recession began at 3.7% in December 2007 and peaked at 7.9% in June 2009.
* The Hispanic unemployment rate in the Great Recession began at 6.3% in December 2007 and peaked at 12.1% in June 2009.
##### COVID
* The White unemployment rate in the COVID Recession began at 3% in February 2020 and peaked at 14.1% in April 2020.
* The Black unemployment rate in the COVID Recession began at 6% in February 2020 and peaked at 16.7% in April 2020.
* The Asian unemployment rate in the COVID Recession began at 2.4% in February 2020 and peaked at 14.5% in April 2020.
* The Hispanic unemployment rate in the COVID Recession began at 4.4% in February 2020 and peaked at 18.9% in April 2020.
### Education Unemployment:
##### Dot-Com
* The unemployment rate of less than high school graduates over age 25 in the Dot-Com Recession began at 6.8% in March 2001 and peaked at 8% in November 2001.
* The unemployment rate of high school graduates without a college degree in the Dot-Com Recession began at 3.8% in March 2001 and peaked at 5% in November 2001.
* The unemployment rate of those with some college or an associate’s degree in the Dot-Com Recession began at 2.7% in March 2001 and peaked at 4.2% in November 2001.
* The unemployment rate of those with a bachelor’s degree or greater in the Dot-Com Recession began at 2% in March 2001 and peaked at 2.9% in November 2001.
##### Great Recession
* The unemployment rate of less than high school graduates over age 25 in the Great Recession began at 7.7% in December 2007 and peaked at 15.6% in June 2009.
* The unemployment rate of high school graduates without a college degree in the Great Recession began at 4.7% in December 2007 and peaked at 9.7% in June 2009.
* The unemployment rate of those with some college or an associate’s degree in the Great Recession began at 3.8% in December 2007 and peaked at 8.1% in June 2009.
* The unemployment rate of those with a bachelor’s degree or greater in the Great Recession began at 2.1% in December 2007 and peaked at 4.8% in June 2009.
##### COVID
* The unemployment rate of less than high school graduates over age 25 in the COVID Recession began at 5.8% in February 2020 and peaked at 21% in April 2020.
* The unemployment rate of high school graduates without a college degree in the COVID Recession began at 3.5% in February 2020 and peaked at 17.3% in April 2020.
* The unemployment rate of those with some college or an associate’s degree in the COVID Recession began at 3% in February 2020 and peaked at 15% in April 2020.
* The unemployment rate of those with a bachelor’s degree or greater in the COVID Recession began at 1.9% in February 2020 and peaked at 8.4% in April 2020.

### Conclusion:
* P - Value: A p-value is a measure of the probability that an observed difference could have occurred just by random chance.
* Typical values for are 0.1, 0.05, and 0.01. These values correspond to the probability of observing such an extreme value by chance.
Although there are noted differences observed, the differences failed to reach significance. 

##### Chi Square Test for Education vs Unemployment :
<img width="690" alt="Education" src="https://github.com/EpohDespair/Project-1/blob/main/Images/Education.png">

##### Chi Square Test for Gender vs Unemployment:
<img width="690" alt="Gender" src="https://github.com/EpohDespair/Project-1/blob/main/Images/Gender.png">

##### Chi Square Test for Race vs Unemployment:
<img width="690" alt="Race" src="https://github.com/EpohDespair/Project-1/blob/main/Images/Race.png">

# Other uses for the code:
While we did use our code to compare unemployment to other variables. Our code can be used to help other students compare other sets of data. It could serve as a base or template for other projects. 

# Maintenance and contributors: 
* Anggiela Yupanqui 
* Hope Diebold
* Nepanji Davis
* Azmir Suljic
* Alex Mull-Dreyer

