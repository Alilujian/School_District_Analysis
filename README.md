# School_District_Analysis
PyCitySchools with Pandas

## Overview
In this project, we have create a district and school information summary. The school district found that the test scores for ninth grade studetns in Thomas High School were incorrect, so they decided to update the data to find the correct grade information. In this case, we will replace the ninth grade math and reading scores for Thomas High School students.\
The ninth grade reading and math scores will be replaced as "NAN". There are a total number of 461 students affected. We will create a new summary sheet for the score replacements.

## Results
### School District Summary
![District_summary](results/District_summary.png)

### School Summary
![School_Summary](results/School_Summary.png)

### Top Five Performing Schools
![Top_School](results/Top_School.png)

### Bottom Five Performing Schools
![Bottom_School](results/Bottom_School.png)

### Average Math Scores by Grade
![Math_score](results/math_score.png)

### Average Reading Scores by Grade
![Reading_score](results/reading_score.png)

### School Spending
![Spending](results/Spending.png)

### School Size
![School_size](results/School_size.png)

### School Type
![School_type](results/School_type.png)

### Result Summary
* In the district summary, average math score dropped by 0.1%, the reading score, percentage of passing math, reading and both stay the same.
* In the school summary, only the score replacement only affect the result of Thomas High School. The average math score dropped by 0.06, and the average reading score increased by the 0.05. The percentage passing of math, reading and overall have drop slighly about 0.1%.
* The top five performing schools are still the same. The Thomas High School data has slightly changed as mentioned above.
* The lowest five performing schools remain the same.
* Grade ninth average score for Thomas High Shcool has been replaced by "NaN".
* According to the school spending summary, in the $630 - 644 speidng range, there were 6% decrease in percentage passing math, and a 7% drop in percentage passing reading. The overall passing percentage has dropped by about 6% as well.
* From the school size summary, the replacement did not affect the average math and reading scores. The passing percentages for medium-sized schools has dropped by 6% in math, reading and overall passing.
* From the school type summary, the grade change did not affect the average math and reading scores. The passing percentages for charter school has dropped. Before the data change, the charter school has 94% passing math, 97% passing reading, and 90% overall passing. After the replacement, the charter school has 90% passing math, 93% passing reading, and 87% overall passing.
## Summary
In general, the replacement of incorrect grade lead to the decrease in passing percentage. The change is not significant to impact the school ranking compare to other schools in the same district. However, the data replacement does impact the performance when considering the shcool spending, size, and school type.
