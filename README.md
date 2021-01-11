# School_District_Analysis

## Overview of Project
Prepare all district standardized test data for analysis, reporting and presentation to provide insights about performance trends and patterns. 

The district school board has determined that there was evidence of academic dishonesty and that the Thomas High School (THS) grades were altered. For this reason we will be replacing the grade data for THS 9th graders with "Nans". 

## Results 
How does replacing the 9t grade scores impact the following: 
- #### Disctrict level summary:
Replacing the 9th grade THS test data with "Nans" caused slight deterioration in overall math testing scores/pass rates as well as reading pass rates, there was however a slight increase in reading scores (see images below). Note that there was minimal overall impact as only 1.2% of the total district scores were from THS 9th graders. 
  - Original  
  ![](Resources/district_summary_mod.PNG) 
  - THS 9th grade test scores replaced    
  ![](Resources/district_summary_chal.PNG) 
- #### School level summary and Thomas High School’s performance relative to the other schools: 
THS was the 2nd best "% Overall Passing" rate both before and after the replacement of the 9th grade score data. Only Cabrera High School's overall performance was higher. Again, it is interesting to note that although THS's overall pass rates went down after replacing the 9th grade data, the average score actually increased. (See images below)
  - Original  
  ![](Resources/school_summary_mod.PNG) 
  - THS 9th grade test scores replaced    
  ![](Resources/school_summary_chal.PNG) 
- #### Math and reading scores by grade<br/>
  - Math scores by grade<br/>
     Original<br/> ![](Resources/math_by_grade_mod.PNG)<br/> 
     THS 9th grade test scores replaced ![](Resources/math_by_grade_chal.PNG)<br/>   
  - Reading scores by grade<br/> 
     Original<br/> ![](Resources/reading_by_grade_mod.PNG)<br/>
     THS 9th grade test scores replaced ![](Resources/reading_by_grade_chal.PNG)<br/>
- Scores by school spending
- Scores by school size
- Scores by school type
