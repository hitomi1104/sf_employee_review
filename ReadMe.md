# Project Name: Salesforce “Job satisfaction” visualization project

<p align="center">
<img src="images/Salesforce-logo.jpg" width="300">
</p>

#### -- Project Status: [Active]

### Partner
* Salesforce Japan

## Project Intro/Problem Statement
The purpose of this project is to propose a strategy for Salesforce to cintinue to be a great place to work 10 years from now. 
Job satisfaction is determined by employee evaluation.
Globally, including Japan, Salesforce ranks among the top companies in employee reviews.
In this project I will explore what characteristics secifically influence employee satisfaction.

### Hypothesis
By continuously analyzing and visualizing employee's reviews which we can find online as well as understanding what salesforce actually doing well and not continuously will make Salesforce remain to be a great place to work over 10 or more years.

### Data Acquisition
* Webscraping glassdoor review (9888 rows) -> global source
* Webscraping en Japan review (361 rows) -> japanese source
* sadv

### Data Preparation & EDA
#### Data Dictionary
##### glassdoor
| Column Name | Description | Data Type | 
| --- | ----------- | --- |
| title | Headline of the review posted | object |
| author_info | Data, Position, and Location | object |
| rating | rating from star 1 to star 5 | float64 |
| pros | Number of sent newsletters | object |
| cons | Number of newsletters not delivered | object |
##### en Japan
| Column Name | Description |
| --- | ----------- |
| namefrom | Name of sender (company name) |
| sendingdate | Date newsletter was sent |
| subject | Subject of the newsletter |
| sent | Number of sent newsletters |
| nondelivered | Number of newsletters not delivered |
##### glassdoor & en Japan combined
| Column Name | Description |
| --- | ----------- |
| namefrom | Name of sender (company name) |
| sendingdate | Date newsletter was sent |
| subject | Subject of the newsletter |
| sent | Number of sent newsletters |
| nondelivered | Number of newsletters not delivered |
##### product
| Column Name | Description |
| --- | ----------- |
| namefrom | Name of sender (company name) |
| sendingdate | Date newsletter was sent |
| subject | Subject of the newsletter |
| sent | Number of sent newsletters |
| nondelivered | Number of newsletters not delivered |

#### NLP
#### NLU
### Findings
### Limitations
### Conslusion
### Further Work
#### Key Learnings & Challenge

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Emotion Analysis
* etc.

### Technologies
* Python
* Jupyter

#### Libraries used
* Numpy
* Pandas
* SciPy
* Seaborn
* Matplotlib
* NLTK
* SciKit-Learn
* WordCloud
#### Webscraping
* Beautiful Soup
* Request
* Selenium


## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- presentation


## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


#### Other Members:


## Contact
https://github.com/jasminludolf/GA_DSI_capstone

