# School_District_Analysis

Analysis of school district data for Maria and her supervisor, using Pandas and Numpy in Jupyter Notebook (Python).

# Challenge

After meeting with Maria and the school superintendent, I have decided the best action is to:
  1. Replace the ninth-grade math and reading scores from Thomas High School.
  2. Keep all other data associated with the ninth-grade students and Thomas High School intact.
  
## District Summary

After recalculating the district summary DataFrame, the total number of schools, students, etc., remain unchanged. This is good, as we didn't want these to change. Average scores are only slightly lower, but pass percentages have fallen by ~1%.

## School Summary

The recalculated school summary DataFrame has all schools other than Thomas High School unchanged. Again, this is what we want and expect. Thomas High School's totals and budget calculations similarly match. However, Thomas High School's averages have changed slightly, and the percentage of students passing has fallen dramatically, from the 90s to the 60s.

## High and Low-Performing Schools

Removing the suspicious grades has moved Thomas High School out of its position as the second-highest performing school. It is no longer in the top five by overall passing percentage, but has fallen to the middle of the pack.

## Scores by Grade

Thomas High School's Grade 9 averages for reading and math appeared high, so their exclusion likely lowered the average across all schools' Grade 9 scores.

## Scores by School Spending

While the changes haven't affected the average reading and math scores of any spending range, the passing percentages of schools spending $630-644 per student have fallen by 6-7%. This makes sense, as Thomas High School falls into this range.

## Scores by School Size

Only the passing percentages for Medium (1000-2000 student) schools have fallen by 6%. This is consistent with Thomas High School's removal, as it is a Medium size school.

## Scores by School Type

The passing percentages for charter schools have fallen by 3-4%. Thomas High School was a charter school.

## Conclusion

The new DataFrames, especially when compared to the older data including Thomas High School's Grade 9 scores, should help Maria and school administrators. The changes from removing the suspicious scores aren't proof enough, but do appear biased towards Thomas High School having shifted grades in order to inflate passing percentages. Not only that, but we don't see any changes in data that can't be explained by Thomas High School's exclusion. This is important too, since it reassures us that we changed only the intended data, nothing more.
