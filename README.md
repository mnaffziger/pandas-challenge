# pandas-challenge

Module 4 homework assignment: pandas

Sourced code outside of original thought:
    Most code was retrieved from the starter code supplied with this challenge assignment
    Other code was utilized from classmates from the class Slack channel, and noted when used
    Lastly, I utilized stackoverflow for utilization of a lambda function to work through the nexted groupby/conditionals: 
        https://stackoverflow.com/questions/890128/how-are-lambdas-useful/890188#890188



# Written Report:

## District Analysis
Overall, a large majority of the district's school students are passing their math or reading exams, 75% and 86% respectfully.  However, only 65% of all district students are passing both their math and reading exams. In addition, math scores are generally lower than the reading scores.

## School Analysis

### *Analysis by grade level:*
* For each school, the average scores are rather consistant across the grade level for math and reading. 
* Average math scores are still lower than average reading scores

### *Analysis by school spending:*
* Charter schools have a smaller budget (per student) than district schools
* District schools spend more perstudent than charter schools
* Spending more per student did not correspond to higher overall passing rates
### *Analysis by school size:*
* Schools that have 2000 or less students have higher overall passing rates
* The largest charter school has less students than the smallest district school
### *Analysis by school type:*
* Charter school have a drastically higher overall passing rate (90%) than district schools(54%)

## Discussion/Conclusion
The data analysis represented here clearly suggests two things:
1. Schools with less students perform better in assessments
2. Charter schools are better at utilizing their resources (budget) in educating their students- as evidenced in a drastically higher overall passing rates compared to distric schools

Though these trends appear clear, they should be analyzed furthur before reporting this information to governing bodies/stakeholers.  For instance, when the average math and reading scores were calculated, the student population was not directly considered.  These geometric means were considered at equal weight- eventhough the charter schools routinely have lower student couonts than the distric schools.

In addition, demographics are not included in the original student/school csv files.  There is no data citing how many teachers a school has per grade, or how many students are in a classroom.  This data supports the generally held practice that smaller class sizes lead to better student performance/learning.  However this information is only inferred because of the smaller charter school student body.

In addition to basic school demographics, this data does not reflect any admission requirements for the charter schools:
- Is the incomming class chosen from a lottery of applicants?
- Is an entrance exam/aptitude test score required to gain enrollment?
- Is admission based on the region directly surrounding the school?

Many of these factors place undue hardships on students/families leaving the only option as an overcrwoded district school, and culls highly performing students into the charter school system- which can disappropriates resources from district schools.


