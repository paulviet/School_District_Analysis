# School_District_Analysis
CU-VIRT-DATA-PT-02-2021-U-B-TTH
School District Analysis Module 04

## **Overview of the school district analysis**

The Purpose of this Analysis is to compare measurements between the type of schools, District and Charter and the performance in Reading and Mathematics skills and school size.

## Resources

- Data Source:   [students_complete.csv](Resources/students_complete.csv)  [schools_complete.csv](Resources/schools_complete.csv) 
- Jupyter file : [PyCitySchools_Challenge.ipynb](PyCitySchools_Challenge.ipynb)
- Software: Jupyter Notebook Server 6.1.4, Python 3.7.9 

## School District Results

- Thomas High School ninth grader test data were removed from evaluation due to alterations
- 9th grader exclusion resulted in 461 student scores exclude from evaluation.
- The budget for Thomas High School 9th graders was not affect by the scoring 
- The Report measured 15 school Districts with an allocation of 39,170 students with an average  expenditure of $629.30 per a student.

|      | Total Schools | Total Students | Total Budget   | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ---- | ------------- | -------------- | -------------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| 0    | 15            | 39,170         | $24,649,428.00 | 78.9               | 81.9                  | 74.8           | 85.7              | 64.9              |

|                           | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ------------------------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| Student Population Ranges |                    |                       |                |                   |                   |
| Small 200-1399            | 83.8               | 83.9                  | 94             | 96                | 90                |
| Medium 1400-2599          | 83.3               | 83.9                  | 94             | 97                | 91                |
| Large 2600-3799           | 76.8               | 81.0                  | 67             | 80                | 54                |
| X-Large 3800-5000         | 77.1               | 80.9                  | 66             | 81                | 54                |

- Smaller and Medium schools tended to outperform Larger schools in general in both individual and combined subjects in regards to passing, however their averages scores were very close. This suggested that there is a huge deviation from those students attending smaller schools who had excellent grades to above passing and fewer whom were at or below the failing mark

  |             | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
  | ----------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
  | School Type |                    |                       |                |                   |                   |
  | Charter     | 83.5               | 83.9                  | 94             | 97                | 90                |
  | District    | 77.0               | 81.0                  | 67             | 81                | 54                |

-   The averages between Charter schools and District schools were also close, however Charter schools reflected grade averages and passing percentages of smaller and medium sized schools, while District school resembled numbers close to larger schools.

  |                        | School Type  | % Overall  Passing | Student  Population Ranges |
  | ---------------------- | ------------ | ------------------ | -------------------------- |
  | Cabrera High School    | Charter      | 91.334769          | Medium  1400-2599          |
  | Thomas High School     | Charter      | 90.630324          | Medium  1400-2599          |
  | Griffin High School    | Charter      | 90.599455          | Medium  1400-2599          |
  | Wilson High School     | Charter      | 90.582567          | Medium  1400-2599          |
  | Pena High School       | Charter      | 90.540541          | Small  200-1399            |
  | Wright High School     | Charter      | 90.333333          | Medium  1400-2599          |
  | Shelton High School    | Charter      | 89.892107          | Medium  1400-2599          |
  | Holden High School     | Charter      | 89.227166          | Small  200-1399            |
  | B**ailey High School** | **District** | **54.642283**      | **X-Large  3800-5000**     |
  | Ford High School       | District     | 54.289887          | Large  2600-3799           |
  | Johnson High School    | District     | 53.539172          | X-Large  3800-5000         |
  | Hernandez High School  | District     | 53.527508          | X-Large  3800-5000         |
  | Huang High School      | District     | 53.513884          | Large  2600-3799           |
  | Figueroa High School   | District     | 53.204476          | Large  2600-3799           |
  | Rodriguez High School  | District     | 52.988247          | X-Large  3800-5000         |

- Charter schools are Higher Performing than District schools. Looking further into just School Type, overall passing percentages, and Student Population, it appears that nearly half of the students in district schools are failing while the opposite is true of Charter Schools. Since no Charter School is larger than  2600 students, it is also suggested that either the schools are selective or that smaller class sizes help students with passing classes.  and Low Performing Schools

  | Math Scores          | 9th  | 10th | 11th | 12th |
  | -------------------- | ---- | ---- | ---- | ---- |
  | Bailey High School   | 77.1 | 77.0 | 77.5 | 76.5 |
  | Cabrera High School  | 83.1 | 83.2 | 82.8 | 83.3 |
  | Figueroa High School | 76.4 | 76.5 | 76.9 | 77.2 |
  | Ford High School     | 77.4 | 77.7 | 76.9 | 76.2 |
  | Griffin High School  | 82.0 | 84.2 | 83.8 | 83.4 |

  | Reading Scores       | 9th  | 10th | 11th | 12th |
  | -------------------- | ---- | ---- | ---- | ---- |
  | Bailey High School   | 81.3 | 80.9 | 80.9 | 80.9 |
  | Cabrera High School  | 83.7 | 84.3 | 83.8 | 84.3 |
  | Figueroa High School | 81.2 | 81.4 | 80.6 | 81.4 |
  | Ford High School     | 80.6 | 81.3 | 80.4 | 80.7 |
  | Griffin High School  | 83.4 | 83.7 | 84.3 | 84.0 |

- Scores between Grades did not vary much, which suggests that the schools and students grade consistently.
- Charter schools tended to spend less than District Schools, but the margin was different approximately $30 more or less than the average.


  ## Summary

  

- Major changes that were affected with the exclusion of the test data from , 461 student test data entire from the 9th grade class was excluded from the evaluation
- Overall Math and Passing dropped 1% (461/39,170 = 1%) which accounted for the dip in the sample.
- The Budged was unaffected as it was dependent on student headcount, as those students were counted in the population.
- Thomas High School itself saw approximate a increase of just over 25% less students passing (accounting for 1 out of 4 grade levels not counted in the the study, 461/1635 = 28.2%)
- Without the data from Thomas High School, it still statistically shows small to medium sized school outperform larger schools as it supports the Charter school model which is smaller class sizes are conducive to students Passing exams.