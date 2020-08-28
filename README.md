# Investigate-Movie-Dataset
In this project we will analyze a data set from a film maker prospective, trying to answer the main questions related to how to create a successful movie. We will focus not in popularity, voting but in profitability.  In the project will be used the adjusted columns 'budget_adj' and 'revenue_adj' to calculate new column 'profit_adj' and to analyze most profitable genres, production companies, directors, budgets and release months.  As columns, as ‘genres’, 'director' and 'production_companies', contain multiple values separated by pipe (|) characters, we will spit them and use the first value as the main one. For example column 'director' we will use the first director on the list and analyze just the 'first_director' category. The same we will do with columns 'production_companies' and 'genres' we will use just first in the list company and genre and analyze as the 'main_production_company' and 'main_genre' for particular movies.
