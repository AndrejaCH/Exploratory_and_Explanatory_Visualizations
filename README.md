# PISA 2012 - Data Exploration
## by Andreja Ho
Exploratory and Explanatory Data Visualizations with Python, Pandas, Matplotlib and Seaborn

## Dataset

PISA 2012 is a survey of students' skills and knowledge as they approach the end of compulsory education. Original PISA 2012 dataset is very complex and contains 485490 rows and 636 columns. For the purpose of this analysis I focused on only a few features, mentioned above. After cleaning the dataset contains 325497 rows and 19 columns.

First, I looked through the [dictionary](Data/pisadict2012.csv) to learn what data was gathered and define the idea of the interest. Next, I read through the [codebook](https://www.oecd.org/pisa/pisaproducts/PISA-2012-technical-report-final.pdf) to decide what features or variables are best suited for the analysis.
 
I am interested in how specific features impact students’ performance on math, reading, and science testing. The features of interests are:<br>
   - wealth<br> 
   - cultural and home possessions<br>
   - educational resources<br>
   - parents’ and siblings’ presence<br>
   - the educational level of parents<br>
   - skip classes within school day<br>
   - skip whole school day<br>
  
Besides those features, I will be analyzing if there is any difference between<br>
   - gender<br>
   - schools that joined OECD<br>
   - country<br><br>


## Summary of Findings

I started off PISA 2012 exploratory data analysis by plotting distribution of simple variables such as gender, single parents and countries that joined OECD and the ones who didn’t. 

There are slightly more countries that joined OECD, that is 59.6% in comparison to countries that have not joined OECD 40.4%. There is an equal distribution for both genders in this dataset 50,3% females and 49,7% males. There is uneven distribution of both parents present versus single parents. 81.4% of students have both parents and 18.6% of students live in single-parent households.Next I explore distribution of the scores for mathematics, reading and science. All three features had normal distribution.Parent education level for mothers and fathers is very similar. Education levels are distributed in 7 levels from ISCED 0 to ISCED 6 with the highest count in the categories ISCED 4 and ISCED 6.
There were slight positive correlations between students’ scores and parent education, their wealth and home possessions. 
Next investigation was on how frequently students skip classes and school days. Majority of students do not skip classes or skip less than 1 class within the school day. 
There is no significant difference between gender and scores. 
.

## Key Insights for Presentation

Key finding form analysis are correlations between parent education level and overall scores. The higher the education level the higher the student's overall score is. There is a slight difference between countries that joined OECD (Organisation for Economic Co-operation and Development) and the ones that didn’t. Next interesting observation is a slight positive correlation between home possessions (wealth) and students’ overall scores. This is even more obvious when plots are divided by parent educational level.
The interesting findings from this analysis is that students' scores are also dependent on factors that students do not have any control over - that is if a country joined OECD, educational level of their parents and their wealth. It is important to be aware of those differences to provide the best education and well-being for every student. 

