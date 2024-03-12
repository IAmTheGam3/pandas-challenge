# Description
The most obvious thing to notice is that Charter schools completely outperform District schools by relatively large margins. looking at the percentage passing stats alone, Charter schools are out performing the District schools in math, reading and overall passing by almost 30, 16, and 40% respectively. One thing that could easily explain this would be that Charter Schools are noticibly smaller than their District school counterparts. What this means is that there is more ready access to faculty for help on schoolwork.

For both Charter and District schools reading is the better topic than Math. But the difference is much more pronounced in District schools. There is almost a 20% difference between Reading and Math passing rates.

Perhaps one of the more shocking results would be the 'Scores by School Spending'. The graph shows a decline in passing the more money that is spent per student.
There are two limitations to this dataset that I can see right off the bat. The first is that we do not know where these schools are located. That would be a huge factor to consider because we don't know if these schools are in the inner cities or the suburbs. Typically schools in the suburbs are seen as better than an inner city school usually because of the incomes/attitudes of the families that are able to be there for the kids and motivate them in their studies. Such attributes are tragically lacking for many inner city students. The second limitation that I can see is the students themselves. We do not know what kind of disabilities that they may have. For all we know the districts could be funneling the kids with disabilites into these schools causing the scores to be dragged down. These 2 limitations alone could explain why our 'Scores by School Spending' stat is not useful. We don't know the condition of one student vs. another. If we had 2 students who had the same abilities (or disabilities) this stat might actually be inversed. But for now, we do not know.

Taking the raw data, we would walk away concluding that Charter Schools are unequivocally better than District schools, spending more money per student will lower the passing rates, and school students on average are better at reading than math. However, some of our conclusions made from the data might not be a universal truth. Taking into account things like the family situation, location and mental state might give us a different conclusion.

# Dependencies
pandas
pathlib

# Files
schools_complete.csv
students_complete.csv
PyCitySchools_solution.ipynd

# Sources
.nunique() was a line of code I found on https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.nunique.html
.setindex() was a line I found from https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.value_counts.html
school_spending_df['Per Student Budget'] = school_spending_df['Per Student Budget'].replace('[\$,]', '', regex=True).astype(float) was a line of code that SlackBot had written for me when I asked for help on what to write here
