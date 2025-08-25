📊 YouTube US Trending Video Data Analysis
Author: G.V. Shivanjan

Date: June 2025

🎯 Objective
The primary goal of this project is to perform an in-depth exploratory data analysis (EDA) on trending YouTube video data from the United States. This analysis aims to uncover key insights into viewer preferences, video performance, and audience engagement metrics. The findings can be valuable for content creators, marketers, and YouTube strategists.

💾 Dataset Information
Dataset: USvideos.csv (sourced from Kaggle's Trending YouTube Video Statistics).

Note: Due to its large size, the dataset is not included in this repository. You can access it via the following link:

https://drive.google.com/drive/folders/1snYI1LusrJTToS35CBYD3jy4D8FS7lAq?usp=drive\_link

Content: This dataset contains daily statistics for trending YouTube videos, including:

video\_id

title

channel\_title

category\_id

publish\_time

tags

views

likes

dislikes

comment\_count

And other relevant metadata.

🚀 Steps Followed
Data Loading \& Initial Inspection: Loaded the USvideos.csv dataset and performed initial checks on its structure, shape, and data types.

Data Cleaning:

Handled missing values (specifically in the description column) by dropping rows.

Cleaned and standardized column names (converted to lowercase, replaced spaces with underscores).

Data Transformation \& Feature Engineering:

Converted publish\_time to datetime objects.

Extracted new time-based features: upload\_year, upload\_month, upload\_day, upload\_hour, weekdays, and a boolean flag is\_weekend.

Exploratory Data Analysis (EDA):

Analyzed the distribution of trending videos by category.

Identified the top 10 channels with the most trending videos.

Compared views, likes, dislikes, and comment counts for top and bottom-viewed videos.

Examined the distribution of video uploads across weekdays vs. weekends.

Investigated the correlation between key engagement metrics (views, likes, dislikes, comment\_count) using a heatmap.

Visualizations: Utilized matplotlib and seaborn to create informative plots, including:

Bar plots for category distribution and top channels.

Grouped bar charts for comparing metrics across videos.

Pie chart for weekday vs. weekend uploads.

Heatmap for correlation analysis.

Insights \& Recommendations: Derived actionable insights based on the visual analysis and provided recommendations for content creators and marketers.

💡 Key Insights
Content Dominance: Categories like Entertainment and Music consistently feature the highest number of trending videos, indicating strong audience preference in these genres.

Engagement Correlation: There is a high correlation between views and likes, suggesting that popular videos generally receive positive engagement.

Niche Audience Engagement: Some videos, despite having relatively low view counts, exhibit high like-to-dislike ratios, pointing to a highly engaged niche audience.

Channel Consistency: A few specific channels repeatedly appear in the trending lists, highlighting the importance of consistent content creation and audience loyalty.

Visual Effectiveness: Bar plots were found to be more effective than line plots for comparing discrete, unrelated metrics in this dataset.

📈 Visualizations
Here are some of the key visualizations generated during the analysis:

Distribution of Trending Videos by Category
Top 10 Trending YouTube Channels
Top 10 Most Viewed vs. Bottom 10 Least Viewed Videos (Grouped Metrics)
Weekday vs. Weekend Uploads
Correlation Between Key Metrics
🛠️ Tools \& Libraries Used
Python

Jupyter Notebook

Pandas: For data manipulation and analysis.

Matplotlib: For creating static, animated, and interactive visualizations.

Seaborn: For statistical data visualization.

Pillow (PIL): For image processing (though not heavily utilized in the core analysis).

os module: For file system operations (e.g., saving plots).

🚀 Future Improvements
Interactive Dashboard: Develop an interactive dashboard using tools like Power BI or Tableau to allow users to explore the data dynamically.

Natural Language Processing (NLP): Apply NLP techniques to analyze video titles, descriptions, and tags to identify emerging trends, sentiment, or popular keywords.

Machine Learning Models: Train predictive models to forecast a video's trending potential based on its initial metrics and content characteristics.

Cross-Country Comparison: Extend the analysis to include YouTube trending data from other countries to compare global trends and regional preferences.

📧 Contact
Feel free to connect with me on www.linkedin.com/in/gv-shivanjan or reach out via email at shivanjan192@gmail.com for any questions or collaborations!

