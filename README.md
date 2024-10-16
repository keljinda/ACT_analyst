
Project 1: Standardized Test Analysis

### Overview
![image](https://github.com/user-attachments/assets/b9e7c70e-051b-459b-96b5-ccee8bf45a1e)

The purpose of this project is to lay the groundwork for those who wish to become data scientists or comprehend the data analyst cycle. In addition to the Python programming structure, the implementation structure is created from the beginning to the end of the audience presentation.
The project's standard requirements are
1. Technically, Github will still be used.
2. Fundamental Python Coding and Key Libraries
3. The Jupyter notebook
4. The life cycle of a data analyst project
5. Inquisitive about the information and eager to learn more to get the answer

After finishing the assignment, students will benefit from the course and learn the what, when, where, why, and how of becoming data scientists.
   
### Problem Statement
"What is the current state of the ACT test in the U.S.?"

The ACT is mandatory in several states, which can lead to higher participation rates and a more comprehensive dataset for analysis. 

First Question: How is the ACT test situation in the US? The likelihood of taking it, overall, reflects the quality of the score.

ACT participation rates vary a lot across different U.S. states. Some states require the test, while others don’t, and this affects both test scores and how students perform overall. Looking at these trends by year and region can help us understand the reasons for participation drops and how they might relate to college readiness. Comparing ACT participation with SAT rates could also give more insights and help improve participation in areas where it’s decreasing.

---

### Datasets

#### Provided Data
There are 3 years of data set for ACT Analysis to find the participation trend.


* [act_2017.csv](./data/act_2017.csv): 2017 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [act_2018.csv](./data/act_2018.csv): 2018 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [act_2019.csv](./data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [us_regions_divisions.csv](https://github.com/keljinda/ACT_analyst/blob/main/data/us_regions_divisions.csv) : us regions and divisions, including state 
* 
#### Data Dictionary 


| Field | Type |Description
| --- | --- | --- |
| state | str | Names of all US states and the District of Columbia |
| participation | int64| The percentage of students who took the ACT |
| composite | float64| The mean score of the categories English, Math, Reading, and Science on the ACT |
| year | int64| Year of student who took the ACT test |
| region | str| The United States can be divided into areas of land. In common communications, the United States is divided into five regions: Northeast, Southeast, Midwest, Southwest, and West.|

---

### Conclusion

A deeper analysis is recommended to investigate the specific reasons behind declining participation rates in regions with historically high participation. This analysis should focus on how changes in educational policy, economic conditions, and test perceptions are shaping these trends. For example, one question to consider is: Why does accounting, a major that typically doesn't require advanced science knowledge, require a science score from the ACT?




