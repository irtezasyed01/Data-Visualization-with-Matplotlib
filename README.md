# Data-Visualization-with-Matplotlib

This project demonstrates various data visualization techniques using a relational database (RDBMS) and SQL queries for data extraction. The main objective is to visualize different aspects of the data, such as distribution, relationships, composition, and comparison, using Python libraries like matplotlib and pandas.

**Key Features**
Data Extraction with SQL:

Query the data stored in an SQLite database.
Perform operations like counting records, grouping data by age, and retrieving specific columns for analysis.

**Visualizing Data:**

**Histograms:** Display the distribution of ConvertedComp to observe the frequency of different compensation ranges.
Box Plots: Analyze the distribution of Age through a box plot, identifying the spread and outliers.
Scatter Plots: Visualize the relationship between Age and WorkWeekHrs to explore correlations.
Bubble Plots: Create a bubble plot to visualize WorkWeekHrs and CodeRevHrs, with bubble size representing the Age of respondents.
Comparative Analysis:

**Bar Charts:** Visualize the top programming languages and databases respondents desire to learn next year.
Stacked Charts: Compare median WorkWeekHrs and CodeRevHrs for respondents aged 30 to 35.
Line Charts: Plot the median ConvertedComp for different age groups, specifically between ages 45-60.
Compositional Analysis:

**Pie Charts:** Present the composition of the top 5 databases that respondents wish to learn next year.

**Data Source**
The data for this project was retrieved from an SQLite database file containing survey responses. The analysis was focused on features like Age, WorkWeekHrs, ConvertedComp, and programming/database preferences.

**Tools and Libraries Used:**
SQLite: To query the data and interact with the relational database.
Pandas: For data manipulation and SQL query execution.
Matplotlib: To generate visualizations such as histograms, scatter plots, and pie charts.
