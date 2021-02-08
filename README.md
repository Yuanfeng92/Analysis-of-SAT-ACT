# Analysis of SAT & ACT 

## Problem Statement
Following the release of a new SAT format in 2016, the College Board is keen to drive participation rates for the examination across the country. This study aims to analyze the state participation rates and scores for both the SAT and the ACT examinations in 2017 and 2018, to identify key factors influencing these metrics and provide recommendations on how the College Board can best allocate its funds to further improve the numbers.

## Executive Summary
### Contents:
- 2017 Data Import & Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT/ACT|State Participating in Test|
|participation_sat17|float|SAT|Participation Rate of the State for SAT 2017|
|mebrw_sat17|int|SAT|Mean Score for Evidence-based Reading and Writing of the State for SAT 2017|
|math_sat17|int|SAT|Mean Score for Math of the State for SAT 2017|
|total_sat17|int|SAT|Mean Total SAT Score for the State for SAT 2017|
|participation_act17|float|ACT|Participation Rate of the State for ACT 2017|
|english_act17|float|ACT|Mean Score for English of the State for ACT 2017|
|math_act17|float|ACT|Mean Score for Math of the State for ACT 2017|
|reading_act17|float|ACT|Mean Score for Reading of the State for ACT 2017|
|science_act17|float|ACT|Mean Score for Science of the State for ACT 2017|
|composite_act17|float|ACT|Mean Composite Score of the State for ACT 2017|

## Conclusions and Recommendations
### Key Takeaways
From looking at and exploring the relationships between the variables within these datasets, many interesting relationships between the different variables were found. Some notable findings are listed below:
1. Most states will favour only 1 test, resulting in high participation rate in one and low participation rate in another.
2. There are a greater number of states have high participation rate for ACT as compared to SAT.
3. As participation rate increases, the mean scores achieved by the state drops.

### Recommendations
College Board is the American not-for-profit organization that develops and adminsters the SAT and SAT subject tests. Below are some recommendations/suggestions targetted to improve the SAT participation rate.

College Board should target the states with low SAT participation rates in both 2017 and 2018, states where these suggestions could be useful will be states such as **Iowa** (and others including: Kansas, New Mexicom, West Virginia, Arizona, Alaska, Oregon). The reason to target these states is that while these states have **low SAT participation rates**, their **ACT participation rate is not too high either**, probably signifying that there is **no state policy mandating any specific college admissions test**, therefore making them excellent locations to work to improve SAT participration rate.

#### 1. SAT School Day
One way that has been proven effective is to carry out an initiative known as **SAT School Day**. This initiative provides schools, districts and sstates a way to offer SAT to graduating students in school, on a weekday. There are 2 main key benefits to this:
1. This will make it vastly more convenient for students to take the SAT.
- Having the SAT in the school allow students to be in a familiar setting.
- Having it on a weekday ensures that it will not disrupt weekend jobs, plans or family time.
2. Low-income students can get access to certain fee waiver benefits.

From the above analysis, the mean participation rate for states with SAT School Day is much higher than the mean participation rate for all states

#### 2. SAT Marketing
Apart from SAT School Day, the college board could promote the SAT better. After the SAT's revamp in 2016, there are a few key differences between SAT and ACT that may be attractive to draw students to take the SAT:
1. Eliminated obscure vocabulary words - Instead of testing students on words they will be unlikely to use, the new SAT tests students to define a word based on how they are used in context.
2. Dropped the penalty for wrong answers - Students do not have to waste time trying to guess answers they are not sure about.
3. More time to answer for each question - It will be less intensive and taxing on the student.
## Sources
Below are the sources that were referred to in this project:
- SAT 2018 Scores: https://ipsr.ku.edu/ksdata/ksah/education/6ed16.pdf
- States Requiring SAT & ACT: https://www.testive.com/state-sat-act/
- Oklahoma Education: https://www.bbc.com/news/world-us-canada-43623216
- Oklahoma Education: https://www.washingtonpost.com/education/2019/03/05/staggering-teachers-oklahoma-have-left-profession-last-years-heres-why/
- Colorado Mandate SAT: https://www.testive.com/colorado-sat-change-2017/
- Illinois Mandate SAT: https://www.testive.com/illinois/
- SAT School Day: https://collegereadiness.collegeboard.org/sat/k12-educators/sat-school-day/about
