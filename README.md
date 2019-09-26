# Understanding the differences between ACT and SAT enrollment in American States
This project is a part of the curriculum for General Assembly Data Science Immersive.

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to explore the data obtained for participation of ACT and SAT in US in 2017 and to understand the general college test enrollment preferences between the states. 

### Methods Used
* Data Cleaning Methods
* Inferential Statistics
* Data Visualization

### Technologies
* Python
* Pandas, jupyter, numpy, scipy
* Matplotlib, Seaborn
* Tableau

## Project Description
- Data was obtained from instructors and cleaned using these sources:
  - 2018 ACT: https://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf
  - 2018 SAT: Complete dataset
  - 2017 ACT: https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows
  - 2017 SAT: https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting

## Getting Started

1. Please clone this repository before using it. 
2. Datasets are kept in .csv files that are contained in [here](Repo folder containing raw data) within this repo.   
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Resulting Data Dictionary

### ACT 2017
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT|States of America with results| 
|act_2017_participation|int|ACT|Participation rate of students in 2017 ACT per state|
|act_2017_english|float|ACT|Average score of the state in English in 2017 ACT|
|act_2017_math|float|ACT|Average score of the state in Math in 2017 ACT|
|act_2017_reading|float|ACT|Average score of the state in Reading in 2017 ACT|
|act_2017_science|float|ACT|Average score of the state in Science in 2017 ACT|
|act_2017_composite|float|ACT|Average Composite score (total score) of the state in 2017 ACT|

### SAT 2017
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT|States of America with SAT results|
|sat_2017_participation|int|SAT|Participation rate of students in 2017 SAT per state|
|sat_2017_evidencebasedreadingandwriting|int|SAT|Average score of the state in Evidence-Based Reading and Writing in 2017 SAT|
|sat_2017_math|int|SAT|Average score of the state in Math in 2017 SAT|
|sat_2017_total|int|SAT|Average total score of the state in 2017 SAT|

## ACT 2018
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT|States of America with results| 
|act_2018_participation|int|ACT|Participation rate of students in 2018 ACT per state|
|act_2018_english|float|ACT|Average score of the state in English in 2018 ACT|
|act_2018_math|float|ACT|Average score of the state in Math in 2018 ACT|
|act_2018_reading|float|ACT|Average score of the state in Reading in 2018 ACT|
|act_2018_science|float|ACT|Average score of the state in Science in 2018 ACT|
|act_2018_composite|float|ACT|Average Composite score (total score) of the state in 2018 ACT|

## SAT 2018
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT|States of America with SAT results|
|sat_2018_participation|int|SAT|Participation rate of students in 2018 SAT per state|
|sat_2018_evidencebasedreadingandwriting|int|SAT|Average score of the state in Evidence-Based Reading and Writing in 2018 SAT|
|sat_2018_math|int|SAT|Average score of the state in Math in 2018 SAT|
|sat_2018_total|int|SAT|Average total score of the state in 2018 SAT|

