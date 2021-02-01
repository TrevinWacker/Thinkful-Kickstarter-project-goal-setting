# kickstarter_project_goal_setting
Analyzing the risk-reward benefits in determining project goal for Kickstarter projects through A/B testing
Project for Thinkful Capstone 1

# Purpose
Project creators on Kickstarter must set their project to succeed over anything; if goals aren't met in the alloted time,  no money is earned and the project fails.
While this can lead many to follow the conventional advice provided by Kickstarter to set intial goal amounts only to cover costs, a secondary goal for creators is to raise 
the most funds to support project creation.  With this in mind, I conducted analysis of over 300,000 Kickstarter projects to find any differences in the success rate of similar
projects with slightly differences in their goal amount, to see if their is any significant penalty in setting a higher goal amount.  While projects can always raise more
than their set goal, having a higher goal would further encourage support for a project to hit that amount, vs not supporting one that has already raised enough to 
be successful.

# Dataset
Projects are given descriptions on project category, length of time posted, date posted, country of origin, and dollar goal and pledge amounts (USD).  All projects
are from 2016-2017.  Future further consideration should be given to the popularity of the project creator, promotion of project, incentives given to those supporting a project, and
the effects of the COVID shakeup, both on the larger public willingness to support projects and the internal shuffle of Kickstarter. 

# Insights
Naturally, the success rate of any project on average decreases as it becomes more expensive, but the nuances within each 'tier' of goal amount lead to varying results. 
For example, for Film & Video projects, there is no signficant differences between success rates projects in the 6th tier (goal ranging $5000-$11,600).  This 
indicates that, if anticipated goal amount for a project lands in this range, there's no signficant indication a project couldn't be successful by increasing their
project goal UP TO $11,600. This is of course said with the understanding that setting higher goals will always incur a risk, so increasing from $5000 to $11,600 may 
not be wise, but from $5000 to $6000 could be beneficial.



# Future work
More concise coding could lead to a more efficient layout and readability, especially in regards to the test setup.  This is also true of summary tables; incorporating
more visual distinctions between signficant results, or different layout of summation, could help give a clearer picture without having to closely examine a table
for differences. At the time of project completion, I didn't have any knowledge on clustering techniques, which would help in creating more similar projects to compare,
rather than giving full consideration to main category.


*Libaries*:
Pandas, numpy, scipy, matplotlib, seaborn
*Techniques*:
Exploratory data analysis, data cleaning, feature engineering, data visualization, A/B testing, minute examination of differences to uncover more specific insights
