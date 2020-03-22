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
