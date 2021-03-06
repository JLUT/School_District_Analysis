**OVERVIEW OF THE PROJECT**

In this project I have given a school district data about their school's budget ,reading and math scores of each student in different schools. First I did some  data clean up and sorting of the data so that I could more easily analyze the data. With this anslysis I could show the data trends and school preformance of each school, so that the district could take decisions, as needed.

**Results**

In this challenge we replaced 9th grade math and reading score by NaN which represents a "Not a number" value, for 461 student records. This looks like a significant number but these score replacements didnot alter data summaries greatly overall. Also we have calculated the % passing math, % passing reading and overall passing % of Thomas High School just for the 10th, 11th and 12th grade students and replaced this data for the overall Thomas High School in our main data frame. 



When assessing average scores and passing percentages among the 15 high schools in the school district, the average math score dropped 0.1 point, the average reading score stayed the same, the percentage passing math dropped 0.2%, the percentage passing reading dropped 0.3%, and the overall passing percent dropped 0.1%.


**Pic - District Summary Original**

<img width="604" alt="District summary orginal" src="https://user-images.githubusercontent.com/71113701/97110581-f58dea00-16a7-11eb-8871-92fa03aa2c49.png">


Pic - District Summary after removing data

<img width="616" alt="District summary after removing data" src="https://user-images.githubusercontent.com/71113701/97110628-3980ef00-16a8-11eb-9b81-56d4b1ba22d0.png">


**School Summary**

When assessing school summaries and performing schools, the score replacements did affect the ranking of the top five performing schools. Thomas High School ranked second place in the top five performing schools with a 91% overall passing. After replacing both math and reading scores, Thomas High School was taken out of the top five category since they now display a 65% overall passing. 

Pic - School Summary Original

<img width="1075" alt="School performance original" src="https://user-images.githubusercontent.com/71113701/97112153-b1531780-16b0-11eb-9d34-12015777d741.png">

Pic - Top schools after removing data

<img width="1105" alt="After Removing 9th grade data" src="https://user-images.githubusercontent.com/71113701/97110761-07bc5800-16a9-11eb-9474-761f96775f6d.png">






**Average Math score by grade**

<img width="522" alt="Math Score by grade" src="https://user-images.githubusercontent.com/71113701/97110805-3afee700-16a9-11eb-9043-4f3ab6e2f3fd.png">


**Average Reading score by grade**

<img width="565" alt="Reading score by grade" src="https://user-images.githubusercontent.com/71113701/97110834-5669f200-16a9-11eb-8403-7609332e2aca.png">


Another plus side from this data replacement is that it did not change the math and reading scores by grade. Granted, both the average math and reading score summaries were stratisfied by school and grade level. As shown above, the summary tables display "NaN" for ninth grade at Thomas High School whereas the remaining data remained intact.





**School spending summary Original**

<img width="788" alt="School Spending summary Original" src="https://user-images.githubusercontent.com/71113701/97110859-7d282880-16a9-11eb-97a5-8e8f4714f4fb.png">

School spending summary after removing data


<img width="795" alt="School spending summary after removing data" src="https://user-images.githubusercontent.com/71113701/97110895-a648b900-16a9-11eb-8da8-09c84f9928ca.png">


When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores. However, this data change did impact the spending ranges for passing percentages. According to the summary above, there were minor decrease in % passing math, % passing reading, and % overall passing in the $630-644 spending range.






**School Size Summary Original**

<img width="827" alt="School size Original" src="https://user-images.githubusercontent.com/71113701/97110942-f293f900-16a9-11eb-82b1-3e78c20bf256.png">


School Size summary after removing data

<img width="815" alt="School size after removing data" src="https://user-images.githubusercontent.com/71113701/97110964-122b2180-16aa-11eb-856b-4ccf6f168a62.png">



When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped slightly (only decimal point differences)



**Total School Type Summary Original**

<img width="756" alt="School Type Original" src="https://user-images.githubusercontent.com/71113701/97111011-58808080-16aa-11eb-9c87-caef632f9b23.png">

Total School Type Summary after removing data

<img width="803" alt="School type after removing data" src="https://user-images.githubusercontent.com/71113701/97111061-ab5a3800-16aa-11eb-812c-bf9f0cd17b8f.png">


In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a minimal reduction in charter school's passing percentages only. On the plus side, these rates are still far superior when compared to district schools.




** Summary **


After removing the ninth-grade math and reading scores from Thomas High School, it affacts summary tables by slightly reducing the average scores and enomous decreasing for the passing percentage rate, including both math and reading passing percentage as well as overall passing percentage.


Charter schools performed better than district schools. The average charter math and reading scores showed a respective 5 point and 3 point edge over the district schools, resulting in a math passing rate over 25 percentage points higher, and a reading passing rate over 15 points higher.

Smaller schools--measured by total students, total budget, or, most surprisingly, budget per student--had better math and reading test scores than larger schools. 

One argument against directly attributing better scores to school size: the charter schools' better scores do not vary by school size. The district schools' scores vary little by school size as well.










 




