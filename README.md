# School_District_Analysis
 **Overview of the school district analysis**  
The purpose of this analysis was to examine the data for Thomas High School after question of possible tampering with grades reported for the 9th grade class. We removed the data in question, and repeated the analysis pulling in fresh data. Findings are summarized below.
    
   **Results**  
   
*How is the district summary affected?*

 - The district summary dataframe changed slightly from the original, with the overall passing % dipping to 64.9%.![enter image description here](https://github.com/ozzirk/School_District_Analysis/blob/main/district_summary.png?raw=true)

  *How is the school summary affected?*
  
 - The school summary specifically for THS was updated to show the accurate grades for the 9th grade population. THS math and reading scores saw a large uptick. This updated the overall passing rate for the school to 90.63% when it was formerly 65.07%.

  *How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?*
  - Updating THS math and reading scores catapults the school's performance from 8th to 2nd place, relative to the other schools. This is a huge improvement!
 ![enter image description here](https://github.com/ozzirk/School_District_Analysis/blob/main/High%20Performing%20Schools.png?raw=true)



  *Replacing the ninth-grade scores affects the following:*
 - Math and reading scores have been updated to the following:
 - Scores by school spending
 ![enter image description here](https://github.com/ozzirk/School_District_Analysis/blob/main/SchoolSpending.png?raw=true)
 - Scores by school size
 
 ![enter image description here](https://github.com/ozzirk/School_District_Analysis/blob/main/SchoolSize.png?raw=true)
 - Scores by school type

 ![enter image description here](https://github.com/ozzirk/School_District_Analysis/blob/main/SchoolType.png?raw=true)

 **Summary**  
 There were four major changes in the updated school district analysis after reading and math scores for the ninth grade at THS were replaced with NaNs:

 1. THS overall passing rate increased
 2. THS moved from 8th top school to 2nd top school based on overall passing rate
 3. NaN appeared whenever pulling math or reading scores for the 9th grade population
 4. The rest of the grades have been validated for accuracy, and the school can continue to uphold state-testing standards
