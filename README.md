# pandas-challenge
I am turning this assignment in late because I was in the hospital for a week when we were working on this assignment.
To keep up with where the class was when I returned, I held off until I had the time to circle back and complete.
jupyter notebook file name is module_four and is located in the PyCitySchools folder.
The read in csv files are located in the Resources folder.

* District Summary
There are a total of 15 schools.
There are 39,170 total students.
The total budget is $24,649.428.
The average math score is 78.99%.
A total of 74.98% students passed math.
The average reading score is 81.88%.
A total of 85.81% students passed reading.
The overall Pass rate is 65.17%.

* School Summary
There are 2 types of schools District = 7 & Charter = 8.
The notebook breaks down the different schools by the Total Students, each Budget
and creates a per student budget. It also provides an average of math, reading and overall
scores by school & the number of students at each school who were passing.
I created a DataFrame for each question and then merged them at the end to create the school
breakdown of budget, per student budget and their passing stats.

* Highest and Worst Schools by overall passing
This is simply a printout of the per_school_summary_df using ascending=False for the best
ascending=True for the lowest performing schools.

* Math Scores by Grade & Reading Scores by Grade
These mirror each other and use the 4 dataFrames by class using the grade column set being == each grade.
Then I used the groupby with School and the corresponding score column to get the math and reading scores
by each school.

* Scores by School Spending & Scores by School Sizes
Utilized the preset bins and labels to obtain to group each school by the spening amounts
and used the requested command of pd.cut to create the new df. Then used that to create addtl
dataFrames broken down by spending per subject compared to the grading outcomes and scores per size of schools.

* Scores by School Type
This mirrors the School Sizes and compares district schools vs charter schools and their avg scores and passing
percentages.

