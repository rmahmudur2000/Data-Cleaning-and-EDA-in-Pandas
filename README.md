# Stock Market Project Using Pandas and Tableau 

**Situation**

I embarked on a project to create an interactive stock market analysis dashboard. The goal was to analyze historical stock prices and trading volumes of six major tech companies: Apple, Facebook, Google, Nvidia, Tesla, and Twitter. I aimed to leverage my skills in data manipulation with Python and data visualization with Tableau to create a comprehensive and user-friendly tool.

**Task**

My task was to analyze a large dataset from Google, which contained information on 6000 companies, and focus on historical stock prices and trading volumes up to April 1st, 2020. I needed to calculate important metrics, create various visualizations, and design an intuitive dashboard that would allow users to easily explore and compare the stock performance of these companies.

**Action**

**1.	Data Preparation with Python:**

**Data Manipulation:** Using pandas in a Jupyter notebook, I cleaned and filtered the dataset to focus on the six target companies. I calculated key metrics such as moving averages, price changes, and volume changes.

**Exporting Data:** Once the data was prepared, I exported it for use in Tableau.

2.	**Visualization and Dashboard Creation with Tableau:**

**Visualizations:** I created multiple visualizations, including:

A line chart for trading volumes.

A detailed table for close prices and volumes.

A line chart for moving averages and open prices.

A histogram representing price changes.

**Interactive Elements:** I added parameters for date range selection and created key performance indicators (KPIs) and highlighters to enable easy comparison between companies.

**Design and Formatting:** I paid careful attention to the visual appeal of the dashboard. This involved adding custom colors, adjusting axis titles, and formatting numbers. I also incorporated company logos and created text sheets to display important metrics such as the last day's trading details, total volume, and price extremes.

**Complex Features:** I developed a detailed price and volume table with conditional formatting, using calculated fields to display the last day's data and adding arrows to indicate price and volume changes.

**Final Touches:** I focused on the overall design and layout, ensuring that all elements were properly arranged and sized for optimal viewing. I set the dashboard to presentation mode for a polished final product.

**Result**

Based on the dashboard I've created, I can derive several insights about the stock market data for the six major tech companies.

**Price Trends (Highest, Lowest, and Moving Averages)**

I have visualized the highest and lowest prices in the period, which highlights the peak and trough of stock prices for each company over the selected timeframe. This helps me identify periods of significant volatility or stability in these stocks. Additionally, I’ve included a moving average of the open price, which smooths out the daily price fluctuations and allows me to see longer-term trends. This helps me detect momentum shifts or potential reversals in the market, providing a clearer view of the underlying trend.

**Volume Analysis**

By analyzing the trading volume through the "Volume" and "Detailed Volume Table" worksheets, I can gauge investor interest in these stocks. High trading volumes typically indicate strong market sentiment, while lower volumes might suggest a lack of conviction among traders. By comparing volume data alongside price movements, I can assess whether price changes are supported by strong trading activity, which is crucial for understanding the strength of these trends.

**Price Percent Change**

The "Price Percent Change" worksheet provides a snapshot of the percentage change in stock prices over the selected period. This allows me to quickly compare the performance of each company and identify which stocks have been the most or least volatile. This comparative analysis helps me understand which stocks are experiencing significant gains or losses and could be indicative of underlying market conditions or company-specific news.

**Last Day and Last Day Total Volume**

I focus on the most recent trading day through the "Last Day" and "Last Day Total Volume" worksheets. These views give me insights into how these stocks performed in the latest session, which is useful for identifying short-term trends or unusual trading activity. This is particularly helpful for making quick decisions based on the latest market movements.

**Total Volume in the Period**

The "Total Volume in the Period" worksheet aggregates trading volume over the entire period, giving me a cumulative perspective on market interest. This data is valuable for identifying periods of heightened trading activity, which may correlate with major news events, earnings reports, or broader market trends.

**Detailed Price Table**

The "Detailed Price Table" provides a granular view of the price data, allowing me to analyze daily or intraday price movements in detail. This level of analysis helps me identify patterns such as support and resistance levels, which are important for understanding potential future price movements.

**General Analysis**
By comparing the same metrics across different companies, I can assess their market behavior and investor sentiment. For instance, if one company consistently shows higher trading volumes and price increases, it suggests stronger investor confidence in that stock compared to others. I also consider the historical context of the data, such as major market events or earnings reports, which could have influenced stock performance.

Exploring correlations between metrics, like price percent changes and volume, further enriches my analysis. For example, if I see prices rising along with increasing volumes, it indicates a strong upward trend. Conversely, if prices rise but volumes decline, it might signal weakening momentum, prompting me to be cautious.

These insights help me better understand the stock market dynamics for these tech companies and enable me to make more informed decisions based on the data I've visualized.

This project demonstrated my ability to effectively combine data manipulation and visualization skills, resulting in a tool that aids in informed decision-making regarding stock market investments. The interactive features and clear visualizations made it user-friendly and insightful for exploring stock market dynamics.

# Data-Cleaning-and-EDA-in-Pandas

**Data Cleaning**
Utilized essential data cleaning techniques in Pandas, including handling duplicates, standardizing formats, and managing missing values.

Highlights

📊 Imported data using read_excel to work with Excel files.

🧹 Removed duplicates easily with drop_duplicates for cleaner datasets.

🗑️ Droped unnecessary columns to streamline data analysis.

✂️ Splited columns for better organization, e.g., separating addresses into distinct fields.

🔄 Standardized data formats, such as phone numbers and customer statuses.

🚫 Filtered out uncontactable entries based on specified criteria.

📈 Reseted index for a clean final output before sharing data.

Key Insights

📂 Importing data from Excel makes it accessible for analysis and cleaning in Pandas, a crucial first step.

🧽 Dropping duplicates early on prevents skewing results and ensures data integrity.

🗃️ Removing unnecessary columns is vital for focusing on relevant information, enhancing analysis efficiency.

🔍 Splitting and organizing data into multiple columns, such as addresses, improves readability and usability for end-users.

🔧 Standardizing formats, especially for phone numbers, is essential for consistency and prevents errors in further data processing.

❌ Filtering out uncontactable customers optimizes outreach efforts and maximizes resource allocation.

✅ Resetting the index provides a clean, user-friendly dataset, enhancing clarity for stakeholders and end-users.


**Exploritory Data Analysis and Visualizations** 

Exploratory Data Analysis (EDA) using Pandas involves understanding data patterns, relationships, and cleaning up errors or missing values.

Highlights

📊 EDA focuses on identifying data patterns and relationships.

🔍 Visualization helps in comprehending complex data.

📈 Descriptive statistics provide quick insights into data attributes.

🚨 Identifying missing values is crucial for data integrity.

🌍 Grouping data by features like continents reveals growth trends.

📉 Correlation analysis highlights relationships between variables.

📉 Box plots are effective for detecting outliers in datasets.

Key Insights

🔑 EDA is foundational for effective data analysis, guiding subsequent cleaning and analysis processes. It sets the stage for deeper insights.

📊 Visualization aids in understanding data distributions and relationships, making it easier to spot anomalies and trends.

🛠️ Using functions like describe() and info() gives a quick overview of dataset characteristics, crucial for initial assessments.

🧩 Identifying and addressing missing values is essential; poor handling can skew analysis results and lead to incorrect conclusions.

🌍 Grouping data (e.g., by continent) allows for targeted insights into specific demographics, helping to identify growth patterns.

📉 Correlation analysis helps assess how different variables relate, guiding focus areas for deeper investigation.

📊 Box plots are a powerful tool for spotting outliers, which may signify data quality issues or significant observations requiring further exploration.
