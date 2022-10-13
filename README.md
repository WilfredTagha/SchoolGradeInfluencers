# Portuguese Dataset Exploration
## by Wilfred Njeunwi Tagha


## Dataset

> This data approach student achievement in secondary education of two Portuguese schools. The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires. Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por). In [Cortez and Silva, 2008], the two datasets were modeled under binary/five-level classification and regression tasks. This analysis focuses only on the Portuguese language dataset. Here's the link to the data https://www.kaggle.com/datasets/whenamancodes/student-performance. I also had to change the data values of some categorical data to thier appropriate lables and type since what was given were all coded by numbers. so I decoded them using the dictionary given alongside the data set. Finally This dataset has 649 records and 33 features. A few of the variables are categorical. About five columns are numerical such as absences, grades(G1, G2 and G3) and age. Most of the rest are ordered categories.



## Summary of Findings

> Here are the findings I got from the exploration.  
> Females are more than males
> The age range of students is between 16 and 22 though most of them are about 16 and 18
> Most students study for 2 to 5 hours daily while a larger fraction of the rest study for less than 2 hours. Quite interesting to see that some study for more than 10 hours.
> Students show to have very good family relations. Just a few are fair and very bad while a good fraction have excellent family relations.
> As the level of alcoholic conusmtion(what I cal drinking habbit) increases, the number of students involves reduces. More students are associated with low drinking habbits both for week days and for school days.
> The outing habbits of students are niether very high nor very low. Most of them are between high, low and moderate.
> Few students have very low free time. Most of them have moderate and high free time and a couple of them with very high freetime.
> The number of absences is highly skewed to the right. Performing a log transformation makes it clearer that most students have between two and 10 absences.
> Most students have an average performance and thier grade performance is a normal distribution.
> The grades strongly correlate with one another.
> students with higher grades are mostlikely to have very low number of absences
> Students with lesser alcoholic consumption are morelikely to perfrom better than those with higher alcholic consumption
> Study time has a lot positive effect on the grade of the students even though it seems stagnant afeter ten hours. However when checked further the positive effect for females increases even after 10 hours but decreases for males.
> Family relations doesn't really have an effect on the activities and behaviour of the students
> freetime and going out have similar effects on grades; when too much, the performance is poor but when it is least the performance is still low. However students with higher grades tend to have some time(more than the least) for flexing(outing and freetime)
> Females perfrom averagely better than males.



## Key Insights for Presentation

> Key insights will be from gender, studytime and flexing(outing and freetime)
> I'll begin by looking at the distribution of the grades and gender. Then I'll look at
the effect of study time on the grades and that of gender then the relation between Gender, studytime and grades.
>Finally, I'll look at the effect of flexing on grades.
