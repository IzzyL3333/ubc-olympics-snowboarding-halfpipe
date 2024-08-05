# :snowboarder: Inferential Analysis for Olympic Snowboarding Halfpipe Athletes 2002-2014
&emsp; This study aimed to determine whether age, BMI, and gender are contributors to the scoring outcomes in the Winter Olympics Snowboarding Halfpipe. While injury patterns in snowboard athletes are researched extensively, the determinants of snowboarding performance through age and BMI remain unexplored. Athlete data was collected between the 2002 and 2014 Winter Olympics using the official Olympic website and Kaggle. Through an athlete's data, graphs were made to visualize and calculate potential correlations. The following comparisons were made: the athlete's age versus their final score, the athlete's BMI versus their final score, and the athlete’s gender versus their final score. 

&emsp; From the data calculation and analysis, BMI and Age had a weak to moderate correlation with winning a medal in Snowboarding Halfpipe in the Winter Olympics. For future studies, other score-based Olympic sports events should be analyzed to determine whether age and BMI can be optimized for a better score.

## Table of Contents
[Introduction](#introduction)
- [Background](#background)
- [Current Research](#current-research)
- [Aim of Study](#aim-of-study)

[Methods](#methods)
- [Collecting Data](#collecting-data)
- [Visualizting Data](#visualizing-data)
- [Analyzing Data](#analyzing-data)

[Results](#results)
- [Adjusted Score vs Gender](#adjusted-score-vs-gender)
- [Adjusted Score vs Age](#adjusted-score-vs-age)
- [Adjusted Score vs BMI](#adjusted-score-vs-bmi)

[Discussion](#discussion)
- [Meaning of Results](#meaning-of-results)
- [Limitations](#limitations)
- [Additional Research Topics and Future Direction](#additional-research-topics-and-future-direction)

[Conclusion](#conclusion)

[Acknowledgements](#acknowledgements)

[Literature Cited](#literature-cited)

[Data Sources](#data-sources)

## Introduction
### Background
&emsp; The Snowboarding Halfpipe is a score-based winter sport in the Winter Olympics. Snowboarding was not added to the Winter Olympics until 1998 in Nagano, Japan. Today, there are five types of Snowboarding events in the Winter Olympics: Parallel Giant Slalom, Snowboard Cross, Halfpipe, Slopestyle, and Big Air. This study narrowed its focus to the Halfpipe as it is one of the score-based events in Snowboarding. For the Snowboarding Halfpipe, six judges will score athletes based on their tricks and overall impression. There are five scoring criteria in the Snowboarding Halfpipe: execution, variety, difficulty, progression, and amplitude. Since the judge's highest and lowest scores are excluded, the four remaining scores will be averaged for the three runs.
### Current Research
&emsp; The current research on Snowboarding revolves heavily around the injuries of their athletes. In the World Cup, athletes who competed at the national level reported an injury rate of about four injuries per 1000 runs (Torjussen et al., 2005). For recreational snowboarders, the most frequent type of injury was their wrist and hand (Ehrnthaller et al., 2015). For professional snowboarders, the most frequent type of injury was a fracture of the wrist followed by fingers (Ehrnthaller et al., 2015; Torjussen et al.,2005). Elite-level snowboarders are injured most commonly when they perform challenging tricks at greater velocities and greater force on the lower limbs (Wijdicks, et al., 2014). The research field on the factors contributing to Snowboarding Halfpipe winners in the Winter Olympics remains limited. 

&emsp; BMI is a measure of performance optimality and the human body’s health. Performance increases as the range of BMI narrows to an optimal area (Sedeaud et al., 2014). The best athletes remain at the optimum interval whereas athletes away from that interval have a negative performance (Sedeaud et al., 2014). A higher BMI is associated with higher diastolic blood pressure (Haapala et al., 2020). High diastolic blood pressure, the pressure in the arteries when the heart rests between beats, can hurt organs such as the heart and kidneys (Centers for Disease Control and Prevention, 2021). BMI impacts an athlete’s ability to maintain optimal performances and the human body’s health against certain health conditions. 

&emsp; The Snowboarding community could benefit from understanding the physical characteristics of snowboarding athletes to optimize their scores, especially those training professionally at an early age. 

### Aim of Study
&emsp; The study’s purpose was to determine whether an athlete’s age, body mass index (BMI) and gender play a factor in the scoring outcomes in the Winter Olympics Snowboarding Halfpipe. Two hypotheses on Snowboarding Halfpipe athletes were made for this study. The first hypothesis was athletes younger than 28 are more likely to score higher than those older than 28. The second hypothesis was athletes with a BMI higher than 22 are more likely to score higher than those with a BMI of less than 22. The reasoning behind the first hypothesis was the mean age of the top 20 male participants in the 2010 Winter Olympics snowboarding was 28.62 with a standard deviation of 4.65 (Stanula et al., 2013), therefore the range of 20-35 years old was used. The reasoning behind the second hypothesis was the mean BMI of the top 20 male participants in the 2010 Winter Olympics snowboarding was 22.41 with a standard deviation of 1.22 (Stanula et al., 2013), therefore the range of 21.19-23.63 BMI was used. The approach to address the potential influence and an athlete’s age and BMI against score required data collection from a large sample of Snowboarding Halfpipe athletes who have participated in the Winter Olympics.

&emsp; The results showed that the athletes’ age and BMI had an overall weak correlation against the score, regardless of gender. The results also showed that male athletes received a slightly higher score than female athletes.  
## Methods
### Collecting Data
&emsp;	Ten data types were collected from the athletes in the Snowboarding Halfpipe using the Official Olympics website and Kaggle, an online resource providing public datasets for analysis. That data was inserted into an Excel spreadsheet with the following columns: Name, Gender, Height [m], Weight [kg], Age, Medal type, BMI [ $kg/m^{2}$ ], Year, Score, and Event. The athlete’s BMI was calculated by dividing their weight by the height squared. The Winter Olympics was narrowed between 2002 to 2014 for an inferential analysis, using a small sample of data (ie. the 2002-2014 Winter Olympics) to infer about a larger population (ie. 1998-2022 Winter Olympics). The scores from the 2002 and 2010 Winter Olympics needed to be doubled as they were marked out of 50 points compared to 2006 and 2014 which were marked out of 100 points. Only the top 12 male and female athletes in the Winter Olympics were used due to the lack of information on final scores provided by the Olympic website. 
### Visualizing Data
&emsp; From the data collection, the following graphs were formed: Adjusted Score versus Gender, Adjusted Score versus Age, and Adjusted Score versus BMI. The Adjusted Score versus Gender box and whisker plot had the explanatory variable as gender and the response variable as scores. The score versus age scatterplot graph had the x-axis being age and the y-axis being the scores. The score versus BMI scatterplot graph had the x-axis being BMI and the y-axis being the scores. 
### Analyzing Data
&emsp; From the visualized data, the adjusted $R^{2}$ values were calculated to determine a possible correlation between Age, BMI, and score. $R^{2}$ was calculated by the following formula: 1 - (sum of the squares of residuals / total sum of squares). $R^{2}$ values could be used to determine a correlation between two different variables. Using the LinearRegression from sklearn.linear_model package on Jupyter Notebook, a trend line can be made in the form of a slope to discover if age and BMI are valuable determinants of a better score. 
## Results
### Adjusted Score vs Gender
![image](https://github.com/user-attachments/assets/a0e6829d-a7ea-40ad-a092-f42d1f70d17e)

**Figure 1.** The adjusted score of the top 12 male versus the adjusted score of the top 12 female Snowboarding Halfpipe athletes from the 2002-2014 Winter Olympics.

|   | Male | Female |
| ------------- | :---: | :---: |
| **Min Adjusted Score**  | 0.4  | 29.4 |
| **Max Adjusted Score**  | 96.8   | 95.8  |
| **Average Adjusted Score**  | 73.9  | 71.7 |

**Table 1.** The minimum, maximum, and average adjusted score versus the top 12 male and female Snowboarding Halfpipe athletes from the 2002-2014 Winter Olympics based on Figure 1.

### Adjusted Score vs Age
![image](https://github.com/user-attachments/assets/41e43c82-332a-47ca-aac4-69edb0d755b4)

**Figure 2.** The scatterplot of the Score Adjusted versus Age of the top 12 female and male athletes from the 2002-2014 Winter Olympics. 

![image](https://github.com/user-attachments/assets/4e97139f-fd54-4d69-b0eb-a5152491fceb)

**Figure 3.** The scatterplot of the Score Adjusted versus Age of the top 12 male athletes from the 2002-2014 Winter Olympics.

![image](https://github.com/user-attachments/assets/83cac4c6-09f9-438f-839f-7afbd9a79412)

**Figure 4.** The scatterplot of the Score Adjusted versus Age of the top 12 female athletes from the 2002-2014 Winter Olympics.

|   | All Athletes | Male Athletes | Female Athletes |
| ------------- | :---: | :---: | :---: |
| **$R^{2}$**  | 0.0583  | 0.0507 | 0.0612 |

**Table 2.** The $R^{2}$ of adjusted score versus BMI of the top 12 male and female Snowboarding Halfpipe athletes from the 2002-2014 Winter Olympics based on Figure 2,3,4.

### Adjusted Score vs BMI
![image](https://github.com/user-attachments/assets/4453abb5-4140-4d6d-ab68-b90efc62b81d)

**Figure 5.** The scatterplot of the Score Adjusted versus BMI of the top 12 female and male Snowboarding Halfpipe athletes from the 2002-2014 Winter Olympics.

![image](https://github.com/user-attachments/assets/28e2c041-de18-4d15-850b-11bf7c61ae79)

**Figure 6.** The scatterplot of the Score Adjusted versus BMI of the top 12 male Snowboarding Halfpipe athletes from the 2002-2014 Winter Olympics. 

![image](https://github.com/user-attachments/assets/18f33c13-70ed-4694-9062-629aa6b76eec)

**Figure 7.** The scatterplot of the Score Adjusted versus BMI of the top 12 female Snowboarding Halfpipe athletes from the 2002-2014 Winter Olympics. 

|   | All Athletes | Male Athletes | Female Athletes |
| ------------- | :---: | :---: | :---: |
| **$R^{2}$**  | 0.0033  | 0.0024 | 0.0355 |

**Table 3.** The $R^{2}$ of adjusted score versus BMI of the top 12 male and female Snowboarding Halfpipe athletes from the 2002-2014 Winter Olympics based on Figure 5,6,7.

## Discussion
### Meaning of Results
&emsp; The results show that between the top 12 Olympic male and female athletes, the scores differed by ranges and overall average (Fig. 1). On average, male athletes receive a higher score than female athletes by almost 3 points. The athletes’ age and BMI versus score do not correlate with each other (Fig. 2,5). An athlete’s age has a weak correlation to scores (Fig.2). For male athletes, age has a weak correlation to scores (Fig.3). For female athletes, age has a weak correlation to scores (Fig.4). An athlete’s BMI has a weak correlation to scores (Fig.5). For male athletes, BMI has a weak correlation to scores (Fig. 6). For female athletes, BMI has a moderate correlation to scores (Fig. 7). 
### Limitations
&emsp; The limitations of this study include the data on scoring in the Winter Olympics. Currently, the official Olympic website only contains the scores of the top 12 female and male Snowboarding Halfpipe athletes. Given all male and female final scores, it could influence the correlation between age and BMI.
### Additional Research Topics and Future Direction 
&emsp; From the data analysis on Snowboarding Halfpipe athletes in the Winter Olympics, many research topics came through different scored-based sports events and other physical compounding variables. The first research topic could be done on a possible correlation between age and BMI to scores in other score-based Snowboarding events such as Big Air and SlopeStyle. The second research topic could be done on a possible correlation between age and BMI to scores in other score-based winter events like Figure Skating and Freestyle Skiing. The third research topic could be done on a possible correlation between age and BMI to scores in score-based summer events like Gymnastics and Artistic Swimming. The fourth research topic could be done on potential compounding variables such as type of training regiment, length of training, and diets to analyze against scores. The results of these variables could inspire new strategies of score optimization by coaches and scientists. For future direction, other scoring-based sporting events and compounding variables analysis against score can determine the factor(s) that can contribute to the maximum score.  
## Conclusion
&emsp; Our findings showed that athletes younger than 28 are not more likely to score higher than athletes older than 28. Our findings also showed that athletes with a BMI higher than 22 are not more likely to score higher than athletes with a BMI lower than 22. Furthermore, there is a weak correlation between age and BMI against the score. When comparing male and female snowboarding athletes, there is a slight difference in scores.
## Acknowledgements
&emsp; I would like to express my gratitude to my communication science instructor, Kelskie Doering for giving my group her time to discuss new proposals and providing constructive feedback on all assignments related to the Scientific Investigation Project.  
&emsp; Secondly, I would like to thank the International Olympic Committee for providing the public, accessible, and reputable data required for this study. 
Lastly, I want to thank my group members Sham, Omayr, and Bokai for their contribution in gathering, graphing and analyzing data for this research.

## Literature Cited 
Centers for Disease Control and Prevention. (2021, May 18). High blood pressure symptoms and causes. Centers for Disease Control and Prevention. https://www.cdc.gov/bloodpressure/about.htm#:~:text=The%20second%20number%2C%20called%20diastolic,%E2%80%9C120%2F80%20mmHg.%E2%80%9D  

Ehrnthaller, C., Kusche, H., & Gebhard, F. (2015). Differences in injury distribution in professional and recreational snowboarding. Open Access Journal of Sports Medicine, 2105(6), 109-119. 10.2147/OAJSM.S78861

Haapala, E. A., Lee, E., & Laukkanen, J. A. (2020). Associations of Cardiorespiratory Fitness, physical activity, and BMI with Arterial Health in middle‐aged men and women. Physiological Reports, 8(10). https://doi.org/10.14814/phy2.14438 

Sedeaud, A., Marc, A., Marck, A., Dor, F., Schipman, J., Dorsey, M., Toussaint, J. (2014). BMI, a performance parameter for speed improvement. PLoS One, 9(2) doi:http://dx.doi.org/10.1371/journal.pone.0090183

Torjussen, Joern. Bahr, Roald. (2005). Injuries among competitive snowboarders at the national elite level. The American Journal of Sports Medicine. 33. 370-7. 10.1097/00005768-200305001-01609. 

Wijdicks, C.A., Rosenbach, B. S., Flanagan, T. R., Bower, G. E., Newman, K. E., & Clanton, T. O. (2014). Injuries in elite and recreational snowboarders. British Journal of Sports Medicine, 48(1), 11-17. 10.1136/bjsports-2013-093019

## Data Sources
- Official Olympic website: https://olympics.com/en/olympic-games/sochi-2014/results/snowboard/slopestyle-men 
- Kaggle: https://www.kaggle.com/heesoo37/olympic-history-data-a-thorough-analysis/data 
