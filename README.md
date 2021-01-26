# School_District_Analysis
The purpose of this analysis was to assist a school board official to analyze reading and math test results for a school district comprised of 15 schools, then to observe and comment on overall changes in results when an entire class is removed from the sample due to concerns over academic dishonesty. 

# Results: 

How is the district summary affected? 
Pre-replacement of values was as follows
Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15	           39170	         24649428	        78.985371	        81.87784	           74.980853	    85.805463	           65.172326
Post-replacement of values
Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	  15	          39,170	      $24,649,428.00	     78.93	             81.9	                 74.8	           85.7	              64.9

We can see that the THS sample of Freshman was removed from the sample because our total counts of reading and math scores is reduced:
Student ID       39170
student_name     39170
gender           39170
grade            39170
school_name      39170
reading_score    38709
math_score       38709

Following removal of ninth grade samples from THS, average reading and average math changed as follows:
Reading- 81.85579580976001 approx .02% change
Math- 78.93053295099331  approx .05% change
Overall passing reduced by about .27% with THS Freshmen removed

How is the school summary affected? I would say on these numbers, stark changes are not noted. The reason that THS stands out is that it's a high average math and reading school with a relatively low percentage of overall passing rate. This may be explainable that there are a few people driving up the average with implausibly high scores suggestive of cheating. 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
School                Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Thomas High School	Charter	1635	               $1,043,130.00	      $638.00	              83.35	              83.90	             66.91	           69.66	           65.08

How does replacing the ninth-grade scores affect the following:

HS_passing_math/1174*100
93.18568994889267
THS_passing_reading/1174*100
97.01873935264055
passing_math_reading_Thomas_count/1174*100
90.63032367972743

Math and reading avg. scores by grade
      Math              9th    10th           11th       12th
Thomas High School	    NaN	  83.087886	     83.498795	 83.497041


Scores by school spending


Scores by school size

Scores by school type

Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

