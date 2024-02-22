# Developer_callenge_dartmouth_courses

![Screenshot (32)](https://github.com/Rxbrooks15/Developer_callenge_dartmouth_courses/assets/112977778/bbd22451-dc40-4023-a60f-08fef2f71598)

**Objective:** Perform the needed data cleaning steps to visualize data from dartmouth_courses.csv in D3. Conduct a comprehensive data analysis and generate visual representations that encapsulate the essence of the dataset, without looking at the data.

**Process:** Produced 2 data visualizations for dartmouth courses from 2021 to 2022. After looking within the csv, I highlighted the few data columns of interest based on departments, Median GPA, and enrollments. Based on these variables, I noticed the high number of observations which could be summarized based on grouping methods. From the visualizations in the Developer Challenge from last year, there was chart reductivity but not much story telling. In this visualization I looked to determine how the number of students enrolled in a department affects the median GPA of the department. I wanted to combine this hypothesis with the idea that STEM majors typically will have departments where the GPA is significantly lower than the average GPA compared to majors within language and the creative arts. In the end I would have points representing the number of enrollments (X-axis) and GPA of each department (Y-axis). 

**Conclusion:** After producing the data visualization I noted that GRK, JAPN, MALS, THEA, SART, PORT, FRIT, CRWT, MUS, and CHIN were the departments with the highest GPAs while PHYS, PSYC, TUCK, INTS, PBPL, EDUC, ASTR, GOVT, BIOL, ECON, and CHEM were the departments with the lowest median GPAs (Top 10 and bottom 10 respectively). This indicates that most high GPA departments include language and the arts while most "low" GPA departments are in STEM and social science/ GOV. 

https://github.com/Rxbrooks15/Developer_callenge_dartmouth_courses/assets/112977778/54eda38d-be3b-4900-99a0-333ee3bfcabf

**Challenges:**  I encountered challenges in effectively highlighting departments based on border colors and reorganizing the legend and the colors that corresponded with the department names. Additionally the tooltip gave me challenges as it was hard to round values (to the second decimal place ) within the tooltip based on information from the summarized dataset. I found it hard to decipher whether a regression model would have done better at highlighting the overall trend in the data (Diregarded model because it would be distracting from the main purpose of the visual).

**Second visualization includes all points from the dataset allowing for more of a story telling element.**

https://github.com/Rxbrooks15/Developer_callenge_dartmouth_courses/assets/112977778/1c7c0b3e-e991-4f4d-9cda-16fffea64647

**Conclusion_2:** Visualized all departments and provided key information to each data point showing **all departments grouped based on the same first letter of their name**

**Challenges_2:** The main challenge with this visualization was the brush tooltip interfering with the hover feature (Main issue involved the brush feature causing the cursor to act as a crosshair which interfered with the cursor being used for the hover feature). I had no idea how to combine the two features so instead produced another separate page for each feature so users could choose the graph they wanted to view based on the feature they were interested in using. I found it hard to color code the points so I grouped the points based on departments with the same first letter. If there was a column section based on the types of departments, for example, arts and performing arts, languages, engineering and humanities, I would have been able to group each department based on this category. Overall I wish there were more columns with maybe professor names or locations on campus based on the dartmouth map so I could potentially map the location of classes based on the coordinates of a Dartmouth map.


