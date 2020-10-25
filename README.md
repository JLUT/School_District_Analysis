** OVERVIEW OF THE PROJECT**

In this project I have given a school district data about their school's budget ,reading and math scores of each student in different schools. First I did some  data clean up and sorting of the data so that I could more easily analyze the data. With this anslysis I could show the data trends and school preformance of each school, so that the district could take decisions, as needed.

** Results **
In this challenge we replaced 9th grade math and reading score by NaN which represents a "Not a number" value, for 461 student records. This looks like a significant number but these score replacements didnot alter data summaries greatly overall. Also we have calculated the % passing math, % passing reading and overall passing % of Thomas High School just for the 10th, 11th and 12th grade students and replaced this data for the overall Thomas High School in our main data frame. 



When assessing average scores and passing percentages among the 15 high schools in the school district, the average math score dropped 0.1 point, the average reading score stayed the same, the percentage passing math dropped 0.2%, the percentage passing reading dropped 0.3%, and the overall passing percent dropped 0.1%.


Pic - District Summary Original

<img width="604" alt="District summary orginal" src="https://user-images.githubusercontent.com/71113701/97110581-f58dea00-16a7-11eb-8871-92fa03aa2c49.png">


Pic - District Summary after removing data

<img width="616" alt="District summary after removing data" src="https://user-images.githubusercontent.com/71113701/97110628-3980ef00-16a8-11eb-9b81-56d4b1ba22d0.png">


** School Summary **

When assessing school summaries and performing schools, the score replacements did affect the ranking of the top five performing schools. Thomas High School ranked second place in the top five performing schools with a 91% overall passing. After replacing both math and reading scores, Thomas High School was taken out of the top five category since they now display a 65% overall passing. 

Pic - School Summary Original

<img width="1107" alt="School performance original" src="https://user-images.githubusercontent.com/71113701/97110699-abf1cf00-16a8-11eb-8192-fe70f959198e.png">


Pic - Top schools after removing data

<img width="1105" alt="After Removing 9th grade data" src="https://user-images.githubusercontent.com/71113701/97110761-07bc5800-16a9-11eb-9474-761f96775f6d.png">






Average Math score by grade

<img width="522" alt="Math Score by grade" src="https://user-images.githubusercontent.com/71113701/97110805-3afee700-16a9-11eb-9043-4f3ab6e2f3fd.png">


Average Reading score by grade

<img width="565" alt="Reading score by grade" src="https://user-images.githubusercontent.com/71113701/97110834-5669f200-16a9-11eb-8403-7609332e2aca.png">


Another plus side from this data replacement is that it did not change the math and reading scores by grade. Granted, both the average math and reading score summaries were stratisfied by school and grade level. As shown above, the summary tables display "NaN" for ninth grade at Thomas High School whereas the remaining data remained intact.





School spending summary Original

<img width="788" alt="School Spending summary Original" src="https://user-images.githubusercontent.com/71113701/97110859-7d282880-16a9-11eb-97a5-8e8f4714f4fb.png">

School spending summary after removing data

Pic


When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores. However, this data change did impact the spending ranges for passing percentages. According to the summary above, there was a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 6% decrease in % overall passing in the $630-644 spending range.






School Size Summary Original

Pic

School Size summary after removing data

Pic


When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing).



Total School Type Summary

pic

In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.


** End of Results **

** Summary **

Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


** End of Challenge **





After removing the ninth-grade math and reading scores from Thomas High School, it affacts summary tables by slightly reducing the average scores and enomous decreasing for the passing percentage rate, including both math and reading passing percentage as well as overall passing percentage.



Two clear trends appear in the data:

Charter schools performed better than district schools. The average charter math and reading scores showed a respective 5 point and 3 point edge over the district schools, resulting in a math passing rate over 25 percentage points higher, and a reading passing rate over 15 points higher.
Smaller schools--measured by total students, total budget, or, most surprisingly, budget per student--had better math and reading test scores than larger schools. In each size analysis, the bottom two quintiles' schools' test scores were over 5 points better in math, and over 3 points better in reading than the larger schools. This translated into passing rates for math and reading 20 and 10 percentage points higher, respectively, in the two smallest-quintile schools.
One complicating wrinkle is that the charter schools are all smaller. Wilson High, the largest charter school, serves almost 500 fewer students than Ford High, the smallest district school.

One argument against directly attributing better scores to school size: the charter schools' better scores do not vary by school size. The district schools' scores vary little by school size as well.

The next challenge is to determine whether there is a systematic difference in the composition of the charter school student population versus the district school student population.










 




