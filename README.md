# School_District_Analysis

# 1. Overview of the school district analysis:

The point of the school district analysis is to determine the correlation between school performances and factors, such as budget, school size, and type of school. From this analysis, we can evaluate whether budgets are optimally allocated to enhance the overall school performance.   Later, we found out that the ninth-grade math and reading scores of the Thomas High Schools were compromised. Therefore, we re-analyze the data to see whether anything was different.

# 2. Results:

- The district summary of the new analysis had marginaly lower "Average Math Score", "% Passing Math", "% Passing Reading", and "% Overall Passing" compared to the original analysis (see the tables below).

District summary - new

![Screen Shot 2022-08-23 at 2 11 05 PM](https://user-images.githubusercontent.com/108419097/186232981-c0dfe438-b4fe-4df6-821a-90d166267678.png)

District summary - original

![Screen Shot 2022-08-23 at 2 21 46 PM](https://user-images.githubusercontent.com/108419097/186234822-82f1950f-2e59-4282-b253-799c9470a753.png)


- The school summary of the new analysis remained unchanged for all schools except Thomas High School (see the tables below).  Thomas High School had marginaly lower "Average Math Score", "Average Reading Score", "% Passing Math", "% Passing Reading", and "% Overall Passing" compared to the original analysis. 

School summary - new

![Screen Shot 2022-08-23 at 2 49 44 PM](https://user-images.githubusercontent.com/108419097/186239706-c5774741-1ea9-4c08-b71e-48b44de7a145.png)

School summary - original

![Screen Shot 2022-08-23 at 2 50 13 PM](https://user-images.githubusercontent.com/108419097/186239799-f2c9a75c-5ffe-492c-bc5b-3b93a7e63536.png)


- Replacing the ninth graders's math and reading scores does not affect Thomas High School's performance relative to other schools (see the tables below, showing the tail for per_school_summary_df for ease). 

Thomas High School summary - new

![Screen Shot 2022-08-23 at 2 43 49 PM](https://user-images.githubusercontent.com/108419097/186238631-dcc65bd4-147b-43d4-ae62-59771ea8938f.png)

Thomas High School summary - original

![Screen Shot 2022-08-23 at 2 39 50 PM](https://user-images.githubusercontent.com/108419097/186237981-a7d475c4-a971-47ca-9e56-c27f1cf82242.png)

- Replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade were not avaialble for the 9th grader of Thomas High School.
  - Scores by school spending did not change.

