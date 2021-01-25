# School_District_Analysis

## Project Overview
The following analysis was performed to deteremine the effects of removing the 9th grade math and reading scores from Thomas High School on the following summary data:

1. School District Summary
2. School Summary
3. Top 5 & Bottom 5 Schools based on Overall Passing percentage
4.

### ***NOTE: Due to GitHub DataFrame rendering issues for Jupyter Notebook files, the [PyCitySchools_Challenge.ipynb](PyCitySchools_Challenge.ipynb) file can also be viewed [here](https://nbviewer.jupyter.org/github/joshb738/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb).***

## Resources 
- Software: Anaconda 4.9.2, Jupyter Notebook 6.1.4, Python 3.8.5
- Data Sources: - [students_complete.csv](Resources/students_complete.csv), [schools_complete.csv](Resources/schools_complete.csv)

## Results: 

The removal of 9th grade reading and math scores from Thomas High School has resulted in the following changes:  

1. **School District Summary**
   - 0.1 decrease in the Average Math score.
   - 0.2% decrease in the students passing math.
   - 0.1% decrease in the students passing reading.
   - 0.3% decrease in the students overall passing score.
   
   a) **Original**
   <p align="left">
   <img src="Resources/district_summary_original.PNG">
   </p>
   
   b) **Revised**
   <p align="left">
   <img src="Resources/district_summary_revised.PNG">
   </p>
   
2. **School Summary**
   - Approximately **26.27%** increase in the students passing math percentage.
   - Approximately **27.36%** increase in the students passing reading percentage.
   - Approximately **25.55%** increase in the students overall passing percentage.
   
   a) **Original**
   <p align="left">
   <img src="Resources/per_school_summary_original1.PNG">
   </p>
   
   b) **Revised**
   <p align="left">
   <img src="Resources/per_school_summary_revised.PNG">
   </p>

3. **Top & Bottom 5 Schools based on Overall Passing percentage**
   a) With and Overall Passing percentage of **90.63%** Thomas High has secured second-place position in the top 5 schools
   <p align="left">
   <img src="Resources/top5_schools_revised.PNG">
   </p>
   
   - No reportable effects have occured to the bottom 5 performing school.
   
   a) [Bottom 5 Schools - Original](Resources/bottom5_schools_original.PNG)
   
   b) [Bottom 5 Schools - Revised](Resources/bottom5_schools_revised.PNG)
   
 4. a) Average Math(left) and reading(righ) scores by grade
  
  <img src="Resources/average_math_score_revised.PNG"> <img src="Resources/average_reading_score_revised.PNG">
  - Scores by school spending
  - Scores by school size
  - Scores by school type


## Summary
 Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
