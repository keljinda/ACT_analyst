Project 1: Standardized Test Analysis

### Overview
![image](https://github.com/user-attachments/assets/b9e7c70e-051b-459b-96b5-ccee8bf45a1e)


### Problem Statement

The ACT is mandatory in several states, which can lead to higher participation rates and a more comprehensive dataset for analysis. 

First Question: How is the ACT test situation in the US? The likelihood of taking it, overall, reflects the quality of the score.

The participation rate in the ACT test varies significantly across different states in the US, and this variation may impact the overall quality of composite scores. 

---

### Datasets

#### Provided Data
There are 3 years of data set for ACT Analysis to find the participation trend.


* [`act_2017.csv`](./data/act_2017.csv): 2017 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2018.csv`](./data/act_2018.csv): 2018 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [us_regions_divisions.csv](https://github.com/keljinda/ACT_analyst/blob/main/data/us_regions_divisions.csv) : us regions and divisions, including state 
* 
#### Datadictionary 


| Field | Type |Description
| --- | --- | --- |
| state | str | Names of all US states and the District of Columbia |
| participation | int64| The percentage of students who took the ACT |
| composite | float64| The mean score of the categories English, Math, Reading, and Science on the ACT |
| year | int64| Year of student who took the ACT test |
| region | str| The United States can be divided into areas of land. In common communications, the United States is divided into five regions: Northeast, Southeast, Midwest, Southwest, and West.|

---

### Deliverables





