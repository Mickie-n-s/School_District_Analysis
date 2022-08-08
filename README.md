# School_District_Analysis

## Purpose
We were brought on to analyse the math and reading scores of a local school district in order to find potential trends in performance based on a number of metrics, including budget, number of students, and whether it is a charter or district school. In our analysis we found that the 9th grade class of one of the schools was rife with falsified records, so we needed to adjust the data to omit these erroneous datapoints. 

## Results

- Before adjusting, the below results showed the average scores and percent of students passing reading and math. Thomas High School students in the 9th grade were found to have cheated, so we needed to omit their results.
![](https://github.com/Mickie-n-s/School_District_Analysis/blob/main/Thomas%20High%20Before.png)
- Shown here are the adjusted results. As you can see, the 10th-12th graders of Thomas High have a much higher percentage of passing without the unpermissable data from the 9th grade.
![](https://github.com/Mickie-n-s/School_District_Analysis/blob/main/Thomas%20High%20After.png)
- This suggests that the 9th grade scores were significantly worse than those from the other grades. To examine that we analyzed each school, separated by grade level and subject. Broadly speaking, however, school's average scores were consistent between grade level, generally swinging by less than a percentage point over the three years. 
![](https://github.com/Mickie-n-s/School_District_Analysis/blob/main/All%20Schools%20By%20Grade%20Level.png)
- The district summary remained largely unchanged, aside from the normalization of Thomas High with the rest of the schools. 
- The school summary for Tomas was greatly changed, as nearly 1/4 of their data were umpermissable. This change brought them into line with some of the higher performing schools in the district as far as student performance is concerned. 
 
 
 ## Summary
 We replaced the math and reading scores of the entire 9th grade of Thomas High with null values, allowing us to analyze the rest of the data without any risk of interference. This dramatically changed the Thomas High average scores and pass rate, raising their passing percentage by nearly 30 points. This allowed us to more empirically consider what factors contribute to success among the schools in the district. For example, we can see that spending more money per student in fact has a genearlly inverse relationship with student performance, in spite of what one may expect. Further analysis into the allocation of this budget could ellucidate how much of that money is going directly to student contact and how much is taken up by administrative and community service requirements. 
 
 The strongest correlation to student success we were able to measure was school size, with smaller schools and presumably smaller classes leading to measurably higher performance, as seen below. 
 ![](https://github.com/Mickie-n-s/School_District_Analysis/blob/main/total%20students.png)
