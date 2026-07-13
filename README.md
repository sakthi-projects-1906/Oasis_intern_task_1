Project Structure

Project_1_EDA_Retail_Sales/
├── README.md (this file)
├── Project_1_EDA_Retail_Sales.ipynb
└── retail_sales_dataset.csv (input data)


🚀 How to Run

Prerequisites

bashPython 3.7+
Jupyter Notebook

Install Dependencies

bashpip install pandas numpy matplotlib seaborn jupyter

Run the Notebook


Clone/Download the project


bash   git clone <repository-url>
   cd Project_1_EDA_Retail_Sales


Launch Jupyter


bash   jupyter notebook


Open the notebook

Click on Project_1_EDA_Retail_Sales.ipynb
Run cells sequentially (Shift + Enter)



View outputs

Charts and statistics display inline
All analysis is documented in markdown cells






📥 Data Source


Dataset: Retail Sales Dataset
Platform: Kaggle
URL: https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset
License: Check Kaggle dataset page for terms


Note: You'll need to download the CSV file and place it in the same directory as the notebook.


🛠️ Technologies Used

TechnologyPurposePython 3Programming languagePandasData manipulation, aggregation, groupby operationsNumPyNumerical computations, array operationsMatplotlibStatic visualizations (line, bar, scatter plots)SeabornStatistical visualizations (heatmaps, box plots)JupyterInteractive notebook environment


📊 Key Visualizations

1. Monthly Sales Trend

Line chart showing sales progression across 12 months with clear trend visibility.

2. Day-of-Week Sales Pattern

Bar chart revealing which days see highest sales (e.g., weekends vs. weekdays).

3. Revenue by Gender

Pie chart and box plot showing spending distribution between male and female customers.

4. Revenue by Age Group

Bar chart breaking down total and average revenue by age segment.

5. Product Category Performance

Comparison of revenue, transaction count, and AOV across Beauty, Clothing, Electronics.

6. Gender × Category Heatmap

Heatmap showing revenue intersection of customer gender and product category.

7. Age vs Spending Scatter

Scatter plot (by category) showing relationship between age and transaction amount.

8. Spending Distribution

Histogram with KDE showing transaction amount distribution (e.g., right-skewed).


📈 Results Summary

MetricValueTotal Transactions1,000Total RevenueCalculated from dataAverage Transaction ValueCalculated from dataUnique CustomersCalculated from dataAnalysis Time Period12 months (2023-2024)Charts Generated8+ visualizationsKey Insights5+ actionable findings


🎓 Learning Outcomes

By completing this project, you'll master:

✅ Data Exploration


Loading and inspecting CSV files
Understanding data structure and types
Identifying missing values and duplicates


✅ Statistical Analysis


Descriptive statistics (mean, median, mode, std dev)
Correlation analysis
Distribution analysis


✅ Time Series Analysis


Grouping by time periods (month, day, quarter)
Trend identification
Seasonal pattern detection


✅ Customer Analytics


Segmentation (age, gender)
Purchase behavior analysis
Demographic insights


✅ Data Visualization


Line plots for trends
Bar charts for comparisons
Heatmaps for cross-analysis
Histograms for distributions
Scatter plots for relationships


✅ Business Insights


Translating data into actionable recommendations
Identifying revenue drivers
Spotting opportunities for improvement



🔗 Related Concepts


Exploratory Data Analysis (EDA) — Best practices for data investigation
Pandas Groupby — Aggregating data by multiple dimensions
Time Series Data — Analyzing temporal patterns
Statistical Thinking — Interpreting distributions and correlations
Data Visualization — Communicating insights effectively



⚠️ Notes


This dataset is synthetic/educational — suitable for learning but not production
All analysis assumes data quality; real-world data would require more aggressive cleaning
Time period is full year (2023-2024); patterns may vary year-to-year
Recommendations should be validated with domain expertise and external data



🤝 How to Contribute

Found an insight we missed? Want to enhance the analysis?


Fork the repository
Create a feature branch (git checkout -b feature/new-analysis)
Add your analysis to a new section
Commit and push
Open a Pull Request



📚 Further Reading


Pandas Documentation: pandas.pydata.org
Matplotlib Guide: matplotlib.org/stable/tutorials
Seaborn Tutorial: seaborn.pydata.org/tutorial
Time Series Analysis: statsmodels.org



📝 Metadata

ItemValueProject NameEDA on Retail Sales DataProject Number1 (Oasis Infobyte)Completion DateJuly 2026Status✅ CompleteDifficulty LevelBeginnerData Size1,000 rowsNotebook Runtime~5-10 minutes (full execution)


✉️ Support


Questions? Refer to notebook markdown explanations
Dataset issues? Check Kaggle dataset page
Library errors? Verify dependencies with pip list



Made with ❤️ as part of Oasis Infobyte Data Science Internship

🌟 If this project helped you, please star the repository!
