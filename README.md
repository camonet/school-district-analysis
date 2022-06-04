# school-district-analysis


## Overview of the school district analysis: Explain the purpose of this analysis.
The purpose of this analysis was to redo the school district analysis after it was found that the 9th grade scores at Thomas High School were tampered with. 

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
How is the district summary affected?

<img width="667" alt="District Summary Df 1" src="https://user-images.githubusercontent.com/99444856/171899829-9d709438-1c4e-4266-a4ce-816a49e50e35.png">
Above: Initial District Summary
<img width="572" alt="District Summary Df 2" src="https://user-images.githubusercontent.com/99444856/171899861-8462c93f-5220-4bba-af1e-bbecba2fd884.png">
Above: District summary with Thomas High School (THS) 9th grade grades removed

- The District summary was not significantly affected. As the images show, the district summary statistics were only minorly affected negatively. 

How is the school summary affected?
<img width="442" alt="Thomas High School Before" src="https://user-images.githubusercontent.com/99444856/172020247-76e64e35-f176-4ff6-83f7-fb489dc9f4e9.png">
Above: Intial THS School Summary
<img width="442" alt="Thomas High School After" src="https://user-images.githubusercontent.com/99444856/172020258-45a83d6f-dcdf-45a6-b7aa-2132958e8681.png">
Above: THS School summary with 9th grade level grades removed

- THS's school was affected minorly, as well. By removing the 9th grade level grades, the percentage passing math, reading, and and the overall passing percentages changed by tenths of a decimal place. 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
<img width="997" alt="THS school placement BEFORE" src="https://user-images.githubusercontent.com/99444856/172020579-84ff7cea-1830-40f3-914f-2ad59a4a9e55.png">
Above: THS's school placement before
<img width="764" alt="THS school placement AFTER" src="https://user-images.githubusercontent.com/99444856/172020586-00f54880-1188-4190-80dc-28e0cea5ca3c.png">
Above: THS's school placement after removing the 9th grade level grades

How does replacing the ninth-grade scores affect the following:
  Math and reading scores by grade
  Scores by school spending
  Scores by school size
  Scores by school type
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
