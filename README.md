# School_District_Analysis

## Potential Tampering

Academic honesty and integrity is important especially for public schools who receive federal funding. The school board has tasked us with looking to see if there is tampering and how bad the academic dishonesty is. They believe that Thomas High School has altered reading and math records. If this is true they could be at risk for loosing funding for not adhering to state-testing standards.

## Findings of Analysis

- The district summary is only affected very minimally with variances being less than 1 percent. We can tell the school board that overall the district still maintains the state-testing standards.

![Altered_Tests]("https://github.com/Luis-Acevedo/School_District_Analysis/blob/main/Resources/Photos/Altered_Tests.png")
- The school summary however is drastically affected. We can confidently report that the school has altered their test data to display passing scores 20% over where they should be. When we look at the actual numbers we see their passing averages are far lower than expected. 

![Original_Tests]("https://github.com/Luis-Acevedo/School_District_Analysis/blob/main/Resources/Photos/Original_Tests.png")
- By replacing the 9th graders testing results with higher results the school was able to become one of the top in the district. By misrepresenting their data this high school has misrepresented themselves and compromised the state-testing standards. 

- Replacing the 9th grade scores affects our data in different ways. 
    * Math and reading scores are hard to calculate with the data missing for 9th grade. 

    * Scores didn't change based on school spending. Values were the same both before and after.

    * Score by school stayed consistent when NaN was placed for 9th graders.

    * And the scores by school type didn't change either. 

## Conclusion

The four variables we see change when updating our analysis are decreases in average math score, and in all three areas of percentage pass rate. This means that instead of 93% pass rate for math the school is only at a 66% pass rate. The same can be said for reading and overall pass rate. 