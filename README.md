A web scraping and data science project focused on analyzing financial data from the cryptocurrency market sector, the aim is to build a dataset, adhere to best practices in data processing, and creating a test model to identify top tier crypto assets based on market capitalization

Web Scraping: I collected financial data from Yahoo Finance, a common and reliable source for financial data.

Data Storage and Preprocessing: The scraped data was saved and I performed preprocessing steps, including feature engineering. This step involves cleaning the data, handling missing values(but no missing values was in this data), and deriving new features from the existing ones to enhance the analysis.

Data Visualization: I visualized the data by plotting a scatter plot based on market capitalization and volume. This step helps in understanding the distribution and relationship between these variables.

Handling Outliers: Recognizing the presence of outliers in the data, I applied a log transformation to address this issue. Log transformation is a common technique used to stabilize variance and make the data more suitable for analysis, particularly when dealing with skewed distributions or outliers.

Model Development: I developed a test model with adjustable parameters to identify top-tier cryptocurrency assets based on liquidity (volume) and market capitalization. This model likely involved setting thresholds or criteria for what makes a "top-tier" asset based on these factors.
