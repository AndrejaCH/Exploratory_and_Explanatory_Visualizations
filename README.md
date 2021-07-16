# PISA 2012 - Data Exploration
## by Andreja Ho
Exploratory and Explanatory Data Visualizations with Python, Pandas, Matplotlib and Seaborn

***A comprehensive report about Exploratory and Explanatory Data Analysis its steps can be found in the [jupyter notebook](Data_Exploration.ipynb)***


## Dataset

PISA 2012 is a survey of students' skills and knowledge as they approach the end of compulsory education. The original PISA 2012 dataset is very complex and contains 485490 rows and 636 columns. For the purpose of this analysis, I focused on only a few features, mentioned below. After cleaning the dataset contains 325497 rows and 19 columns.

First, I looked through the [dictionary](Data/pisadict2012.csv) to learn what data was gathered and define the idea of the interest. Next, I read through the [codebook](https://www.oecd.org/pisa/pisaproducts/PISA-2012-technical-report-final.pdf) to decide what features or variables are best suited for the analysis.
 
I am interested in how specific features impact students’ performance on math, reading, and science testing. The features of interests are:<br>
   - wealth<br> 
   - cultural and home possessions<br>
   - educational resources<br>
   - parents’ and siblings’ presence<br>
   - the educational level of parents<br>
   - skip classes within the school day<br>
   - skip whole school day<br>
  
Besides those features, I will be analyzing if there is any difference between<br>
   - gender<br>
   - schools that joined OECD<br>
   - country<br><br>


## Summary of Findings

I started off PISA 2012 exploratory data analysis by plotting the distribution of simple variables such as gender, single parents, and countries that joined OECD and the ones that didn’t.
There are slightly more countries that joined OECD, that is 59.6% in comparison to countries that have not joined OECD 40.4%. There is an equal distribution for both genders in this dataset 50,3% females and 49,7% males. 81.4% of students live with two parents while 18.6% of students live in single-parent households. Next, I explore the distribution of the scores for mathematics, reading, and science. All three features had a normal distribution. Parent education level for mothers and fathers is very similar and are distributed in 7 levels from ISCED 0 to ISCED 6 with the highest count in the categories ISCED 4 and ISCED 6. There were slight positive correlations between students’ scores and parent education, their wealth, and home possessions. The next investigation was on how frequently students skip classes and school days. The majority of students do not skip classes or skip less than 1 class within the school day. Students who don’t skip school days or skip less than 1 class in school day tend to have higher scores. There is no significant difference between gender and their scores.

## Key Insights for Presentation

Key findings from the analysis are correlations between parent education level and overall scores. The higher the education level the higher the student's overall score is. There is a slight difference in students’ scores between countries that joined OECD (Organisation for Economic Co-operation and Development) and the ones that didn’t. Students from countries that are part of OECD tend to have higher scores. The next interesting observation is a slight positive correlation between home possessions (wealth) and students’ overall scores. This is even more obvious when plots are divided by parent educational level. 


