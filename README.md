# PyCitySchools

Prepared by Corey Lawson-Enos

## Summary
PyCitySchools: Pandas script that compares summary district and school size, budget, and type information against student test performance in math and reading. Subject represents a school district of fifteen high schools: approximately 39,000 students, and $25 million budget. 

## Technologies
Pandas, NumPy, Jupyter Notebook

## Additional Analysis
District-wide test performance shown at 75% for math proficiency, 86% for reading, and 65% overall for both math and reaching achievement. Of note:
* Several of the highest-performing high schools fall on the lower side of spending per student scale; conversely, schools with the lowest test score averages show higher spend. Summary spend information also substantiates this trend, showing that test score averages actually decrease as spend increases (see spend table below).
* Smaller and mid-size schools are performing much more favorably than the largest in the district.
* School type--whether charter or district--appears to have direct impact on student performance, with charter schools topping at 90% overall passing, and district schools performing significantly below them at only 54%.

![alt text](https://github.com/clawson13/pandas-challenge/blob/main/PyCitySchools/images/scores_by_spend.jpg?raw=true)

![alt text](https://github.com/clawson13/pandas-challenge/blob/main/PyCitySchools/images/scores_by_size.jpg?raw=true)

![alt text](https://github.com/clawson13/pandas-challenge/blob/main/PyCitySchools/images/scores_by_type.jpg?raw=true)
