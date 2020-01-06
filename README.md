# HW1

### Q1.  
Early in the spring semester, four candidates for a tenure-track assistant professor position will be visiting campus. One part of these visits includes a presentation that is commonly referred to as a job talk. Two of these job talk's will take place during our scheduled class time. A job talk is generally the culmination of several years of work on a series of research projects.

#### a. (6 pts - 1/2 page or so)
Summarize the key points from the talk (on January 15).

#### b. (4 pts - 1/4 page or so)
What are you still confused about?



### Q2.
This course will have a series of 3 projects that will culminate in a presentation that is a shorter version of the job talk. The first will use a dataset from the dating site Ok Cupid. Data is available in R in the `okcupiddata` package. Additional information, including a data dictionary is available in the [package documentation](https://cran.r-project.org/web/packages/okcupiddata/okcupiddata.pdf).


```{r}
#install.packages('okcupiddata')
library(okcupiddata)
data(profiles)
head(profiles)
```

The profiles dataset is messier than most traditional academic datasets, but is similar to "real" datasets. Part of the first project will be focused on data wrangling and visualization, with an ultimate goal of using ANOVA for relative comparisons between different groups.


#### a. (4 pts)
Include three research questions that you'd be interested in exploring with this dataset.

#### b. (6 pts)
For one of the questions in part 2a, create a data visualization (using ggplot2) that displays the data necessary for addressing the research question. Make sure to carefully consider titles and axes for the figure. Also include a short paragraph describing the figure.
