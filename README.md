# School_District_Analysis

BEFORE DATA CLEANUP

Average Math Score = 79.0
Average Reading Score = 81.9
% Passing Math 75
% Passing Reading 86
% Overall Passing 65
AFTER DATA CLEANUP

Average Math Score = 78.9
Average Reading Score = 81.9
% Passing Math 74.8
% Passing Reading 85.7
% Overall Passing 64.9
OBSERVATION: Slight change in Math Score, including % Passing district averages, Comparing the two dataframes above, the average show the difference when the 9th grade student Math and Reading scores from Thomas High Schools were excluded from the District Summary.


How is the school summary affected?
BEFORE DATA CLEANUP

Thomas High School's % Overall Passing was 91, placing second
How does replacing the ninth-grade scores affect the following:
Analysis Below:

Math and reading scores by grade

Math and Reading Scores from Thomas High School 9th Grade set to "nan" and equivalent to 0.
Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).
Doing that, the only significantly score affected was minimal in a very small in quantity.
Student count() Before THS Cleanup was: 1635
Student count() After THS Cleanup was: 1174
Scores by school spending

Thomas HS is in the spending bucket "$630-644"
Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).
Doing that, the only significantly score affected was minimal in a very small in quantity.
Student count() Before THS Cleanup was: 1635
Student count() After THS Cleanup was: 1174


Summary: Summarize the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks changes, changes that are reflected in the funding for each student (Difference each students funding is ~ $200)
