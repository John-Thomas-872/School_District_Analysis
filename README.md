# School_District_Analysis
## Overview - Explain the purpose of this analysis.
The school board for a certain school district has notified Maria and her supervisor that there is evidence of academic dishonesty in a .csv file named students_complete.csv. This file provides the school board with the student's ID number, name, gender, grade, school name, score in reading and their score in math. The evidence points to the scores being altered in Math and Reading for 9th grade students at Thomas High School. The school board is unaware of the extent of the academic dishonesty, so they have reached out to Maria, the chief data scientist for the school district for help. She is responsible for analyzing information from a variety of sources and in a variety of formats. Maria has reached out for assistance in determining the extent of the academic dishonesty as well as analyzing data on student funding and students standardized test scores. Maria needs help agrigating the students data and showcase trends in schools perfomance. This infomration will be given directily to the school board and superintendent to help make decisions about the schools budget and priorities. 

## Results - Using bulleted lists and images of DataFrames as support, address the following questions.
-How is the district summary affected?.

        # Calculate the Average Scores using the "clean_student_data".
        average_reading_score = school_data_complete_df["reading_score"].mean()
        average_math_score = school_data_complete_df["math_score"].mean()

-How is the school summary affected?

-How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

-How does replacing the ninth-grade scores affect the following:

    -Math and reading scores by grade

    -Scores by school spending

    -Scores by school size

    -Scores by school type


## Summary - Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
