# Kickstarting with Excel

## Overview of Project
    Using data to do analysis on kickstarter campaigns, focusing on the theater category and play subcategory
### Purpose
    To determine the successful, failed, or cancelled outcomes of the play kickstarters based on the established set financial goal. 
    To determine if there may be a better time to launch a kickstarter campaign and have a successful outcome (meet financial goal).
## Analysis and Challenges
    Possible challenges would be to format your original data in the correct way, mostly in regards to the date formatting needed.  
### Analysis of Outcomes Based on Launch Date
    By using a pivot table, I created filters based on Parent Category and Years.  I filtered to only theater for the parent category since that is what we were interested in 
    reviewing for all years. I added the date the kickstarter was created into the rows and grouped them by months. I pulled the Outcomes into the columns section and also used
    the count of outcomes for the values I wanted to see.  This then provided a table and line graph to view outcomes by kickstarter launch date. 
    
### Analysis of Outcomes Based on Goals
    In a separate tab from the Kickstarter data, I made new columns and rows that I could include formulas from the original data set in.  I created a column for each possible
    outcome and then included the total projects so I could calculate the percentage of each outcome.  Each percentage of outcome also a column of its own.  For rows, I created
    groups for goal outcomes to see trends on a range of amounts versus a row for for every specific amount.  This allowed for a more general summary and better visualization in
    my line graph.  I then used the CountIf formula to pull in the criteria that matched the ranges of amounts I had set and if it was in the subcategory of "plays".  https://github.com/laura3kids/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png
### Challenges and Difficulties Encountered
  
## Results
    
- What are two conclusions you can draw about the Outcomes based on Launch Date?
    Greatest success in meeting your financial goals for a theater kickstarter appears to be in May
    November and December appear to be the worst months to launch a successful kickstarter campaign
- What can you conclude about the Outcomes based on Goals?
    The higher your financial goal, the least likely it is that your project will be successful
- What are some limitations of this dataset?
    Unable to show if the successful kickstarters made any money.    
- What are some other possible tables and/or graphs that we could create?
    By using average length of pledge drive time is related to outcomes - If there were a longer the pledge drive time frame, were there more successful outcomes? 
    Were the trends we identified with theater/play the same for all the other categories? 
    Were these trends for outcomes stronger in certain countries than others? 
