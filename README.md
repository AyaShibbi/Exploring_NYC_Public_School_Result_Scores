# Exploring_NYC_Public_School_Result_Scores
Analyze NYC public school test scores using data manipulation and summary statistics to identify top-performing schools and boroughs. This project enhances skills in data filtering, sorting, aggregation, and statistical analysis, which are crucial techniques for anyone interested in data science and educational analytics.


This project uses data manipulation and summary statistics to analyze standardized test performance across New York City's public schools. By examining the data, the aim is to identify top-performing schools, explore how academic performance varies by borough, and highlight the city's top ten schools based on combined SAT scores. This analysis is crucial for understanding educational outcomes and disparities across the city.


# *Objective:
- Best Math Schools: Discover which schools achieve the highest math scores, focusing on those reaching at least 80% of the maximum possible score of 800.
- Top 10 Schools by SAT: Calculate and rank the top 10 schools based on their total SAT scores, encompassing math, reading, and writing sections.
- Borough SAT Performance: Analyze the SAT performance across different boroughs, identifying the borough with the largest variation in scores and understanding its educational landscape.


# *Project approach:
*1. Finding Schools with the Best Math Results:*
- Identify schools where the average math score is 80% or higher.
- Save results in a pandas DataFrame named best_math_schools, sorted by average_math.

*2. Identifying the Top 10 Performing Schools by SAT:*
- Create a total_SAT column summing the scores across math, reading, and writing.
- Extract and sort the top 10 schools into a DataFrame named top_10_schools.

*3. Locating the Borough with the Largest Standard Deviation in SAT Scores:*
- Group the data by borough, calculating the number of schools, average SAT, and standard deviation.
- Identify and save the borough with the largest variation in a DataFrame called largest_std_dev.


# *Skills and Techniques Developed:
- Data Filtering & Sorting: Improve your ability to filter and sort data efficiently using pandas, a key skill in data manipulation.
- Aggregation & Grouping: Learn advanced techniques for grouping data and calculating aggregated statistics, crucial for deriving meaningful insights.
- Statistical Analysis: Hone your statistical analysis skills by calculating and interpreting summary statistics, such as mean and standard deviation, to evaluate trends in educational performance.
