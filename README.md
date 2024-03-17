
# MLOps Lab : Analysis of Movie Dataset

## WorkFlow
* Data Preprocessing
* EDA
* Model Building
* Conclusion 


### Data Preprocessing

The preprocessing steps involved in the analysis of the movie dataset include data loading, handling missing values, data type conversion, and data cleaning. The dataset was loaded using pandas, and initial exploratory steps were taken to understand the structure and content of the data. The dataset comprises 608 movie titles, Missing values were handled, and specific columns such as 'Budget (mill)' and 'Gross(mill)' were cleaned by removing commas and converting them to float data type. Additionally, the year of release was extracted from the 'Release Date' column, and the dataset was filtered based on top studios and genres. The preprocessed data was then saved in a new file for further analysis.

### EDA
The EDA involved a comprehensive exploration of the dataset using various visualizations and statistical analyses. This included the generation of distribution plots for movie release days, IMDb ratings, and budget, as well as box plots and bar plots for analyses such as average runtime by genre, average profit by genre, and average budget by genre. Furthermore, visualizations were created to depict the top directors based on IMDb ratings and average ratings, top studios, and the distribution of movie runtimes. A SweetViz report was also generated to provide a comprehensive overview of the dataset.
#### Distribution of Movies Released by Day of the Week :
The chart illustrates the distribution of movies released based on the day of the week. It is evident that Friday has the highest number of movie releases, followed by Wednesday and Thursday, while Tuesday, Saturday, and Sunday have fewer movie releases compared to the weekdays. 
![App Screenshot](/reports/figures/released_day.png)


### Distribution of IMDb Rating
The IMDb Rating distribution plot shows a mostly normal distribution, centered around the 6.5 to 7.5 rating range. This indicates that the majority of the movies in the dataset have received relatively high ratings on IMDb.
![App Screenshot](/reports/figures/rating_distribution.png)

### Box Plot of Budget
The box plot visualizes the distribution of movie budgets within the dataset. It highlights the median, quartiles, and any potential outliers in the budget data. 
![App Screenshot](/reports/figures/budget_plot.png)

### Movie Budget Distribution
The plot shows the distribution of movie budgets across different genres: with Action movies being the higest followed by Animation, comedy and drama movies, Adventure movies are less frequent and appear in the mid to high budget ranges, with a small number in the $200-250 million range.
![App Screenshot](/reports/figures/movie_budget.png)

### Released Year
![App Screenshot](/reports/figures/year.png)

### Top Directors Based on IMDb Ratings
![App Screenshot](/reports/figures/top10_direct.png)

### Distribution of Movie Runtimes
The plot shows the frequency distribution of movie runtimes in minutes. A bell-shaped curve overlaid on the histogram suggests that the distribution of movie runtimes is approximately normal. The peak of the distribution appears to be around 100 to 110 minutes, indicating that most movies have a runtime within this range. The tails of the distribution show that there are fewer movies with very short or very long runtimes.
![App Screenshot](/reports/figures/runtime.png)

### Average Runtime by Genre
The plot visualizes the average length of movies across different genres. It shows that crime movies have the longest average runtime, closely followed by biography, thriller, and sci-fi genres. On the shorter end of the spectrum, animation and horror genres have the shortest average runtimes. 
![App Screenshot](/reports/figures/runtime_genre.png)

### Average Profit by Genre
The bar chart displays the average profit in millions of dollars for the top five movie genres: 
Sci-fi shows the highest average profit. Fantasy follows closely behind sci-fi. Adventure and Animation genres also perform well, chart suggests that genres with high levels of special effects and broad appeal, such as sci-fi and fantasy, tend to generate higher profits.
![App Screenshot](/reports/figures/avg_profit.png)

### Average Budget by Genre
The plot compares the average movie production budgets across five different genres. Sci-fi has the highest average budget, slightly above \$120 million.Action follows closely, with an average budget around \$110 million. Adventure and Animation genres have similar average budgets, both near $100 million. Fantasy has the lowest average budget among the top five, just under \$100 million.
![App Screenshot](/reports/figures/avg_budget.png)

### Domestic Gross % by Genre
The box plot showcases the distribution of domestic gross percentage by genre, providing valuable insights into the revenue contribution of each genre. The data indicates that the genres "Action" and "Comedy" have the highest domestic gross percentages, suggesting their popularity among domestic audiences. On the other hand, "Drama" and "Animation" also command a considerable share of the domestic gross percentage.

![App Screenshot](/reports/figures/box.png)

