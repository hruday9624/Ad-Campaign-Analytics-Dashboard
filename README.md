# Ad-Campaign-Analytics-Dashboard

The Ad Campaign Analytics Dashboard is a data science project that provides users with insights into the performance of their ad campaigns. By analyzing data on impressions, clicks, video starts, and other key metrics, the dashboard allows users to measure the effectiveness of their campaigns and make data-driven decisions to optimize their results.

Table of Contents

1. Background
2. Installation
3. Usage
4. Files
5. Data
6. Methodology
7. Results
8. Contributing
9. License

### Background

- The Ad Campaign Analytics Dashboard is a data science project aimed at providing insights into the performance of a particular ad campaign. The project leverages data from a 42-day campaign and provides key metrics such as impressions, clicks, video starts, and video completions, among others.
- The main objective of this project is to help marketing teams optimize their ad campaigns by identifying the best-performing segments and trends. By doing so, they can improve their return on investment (ROI) and achieve better campaign results.
- The project uses a combination of Excel and Python to analyze the data and visualize the results in an interactive dashboard. This dashboard provides a user-friendly interface for exploring the data and uncovering key insights.
- Through this project, we hope to demonstrate the power of data analytics in improving ad campaign performance and provide a framework for other marketing teams to use in their own campaigns.

### Installation

To run this project, you'll need Python 3 and several Python libraries, including pandas, numpy, matplotlib, and seaborn. You can install these libraries using pip:

```python
pip install pandas numpy matplotlib seaborn
```

### Usage

To use this project, simply run the Jupyter notebook dental-analytics.ipynb. This notebook contains all the code for loading and analyzing the data, as well as generating visualizations.

### Files

1. Ad-Insights-Dashboard.xlsx: This is an Excel dashboard file. It contains visualizations, charts and reports that can help in analyzing the ad campaign data and gaining insights from it.

2. ad_campaign_analytics.ipynb: This is a Jupyter Notebook file that contains the Python code for the analysis of the ad campaign data. The notebook is divided into different sections based on the analysis performed on the data. The sections may include data cleaning, exploratory data analysis, data visualization, and statistical analysis. This notebook will help in replicating the analysis and generating new insights from the ad campaign data.

### Data

- The data used in this project has 37448 rows and 15 columns for ad campaign analytics is a collection of advertising data for a campaign that ran for 42 days. The data contains information about ad impressions, clicks, and video interactions for various ad segments. The dataset also includes information about the creative categories, media, operating systems, and site categories associated with each ad segment.
- There are a total of 2603 unique impressions and 79 clicks received during the campaign, with 70 different types of creative IDs and 40 creatives grouped under 9 creative categories. The data also includes information about 6 color categories for the creatives, 2 types each for media and creative format, and 3 types for the operating systems.
- The data provides a comprehensive overview of the performance of the ad campaign, which is useful for understanding which segments performed best and which ones could be improved in future campaigns. Through the analysis of this data, insights about the best and worst performing segments, interesting trends, and recommendations for future campaigns can be made. 

Here is a brief description of the data: 

- Date: The date on which the ad was displayed.
- CreativeID: A unique identifier for the creative used in the ad.
- CreativeName: The name or title of the creative used in the ad.
- MediaFormat: The format of the media used in the creative, such as image, video, or audio.
- CreativeCategory: The category of the creative, such as food and beverage, automotive, or electronics.
- DominantColour: The dominant color used in the creative.
- CreativeFormat: The format of the creative, such as display or video.
- Impressions: The number of times the ad was displayed.
- Clicks: The number of times the ad was clicked.
- VideoStarts: The number of times a video ad was started.
- VideoCompletions: The number of times a video ad was played to completion.
- OperatingSystem: The operating system of the device used to display the ad.
- DayofWeek: The day of the week on which the ad was displayed.
- Site: The name of the website or app on which the ad was displayed.
- SiteCategory: The category of the website or app on which the ad was displayed.

### Methodology

The methodology used in this project involves a combination of data exploration, data preprocessing, and data analysis techniques.

- First, we explored the dataset to gain a better understanding of its structure, variables, and possible relationships between them. We visualized the data using various plots and charts, including scatter plots, histograms, and box plots.
- After preprocessing the data, we conducted an in-depth analysis using statistical and machine learning techniques to uncover insights and patterns in the data. We used Python and various libraries such as NumPy, Pandas, and Scikit-Learn to implement the analysis.

Finally, we summarized our findings and insights in the form of visualizations, tables, and charts. These insights can be used to make data-driven decisions and improve the effectiveness of ad campaigns.

### Results

1. We have 42 days’ worth of data with 2603 unique impressions and 79 clicks received.
2. There are 70 different types of creatives IDs and 40 creatives grouped under 9 creative categories.
3. There are 6 color categories for the creatives and 2 types each for media and creative format, and 3 types for the operating systems.
4. The highest number of impressions for an ad was 28,873 with 167 clicks on May 21 2018 Monday, and the site was 'Business Times' under the Site category as 'News'.
5. The least performing ad was observed on Apr 26 2018 Thursday, with only 1 impression and no clicks and no video starts and video completions registered. The site hosting this ad was 'Sitting Pretty' under the Site category as 'Lifestyle'.
6. On May 16 2018 Wednesday, the ad with the creative name 'YogaBunny' in Sports creative category with Mobile Inter-scroller grabbed the highest number of videos starting with 3849, while the ad with the creative name 'Artful Dodger' in the Art creative category with Mobile Inter-scroller grabbed the least number of video starts with 0 video starts and video completions.
7. On May 16 2018 Wednesday, the ad with the creative name 'Face Fails' in Sports creative category with Mobile Interscroller grabbed the highest number of video completions with 1680, while the ad with the creative name 'Artful Dodger' in Art creative category with Mobile Interscroller grabbed the least number of video completions with 0 video starts and video completions.
8. News is the site category with the highest interacted site category recorded, followed by Sports and Fashion/Lifestyle. Entertainment remains the least interacted site category.
9. iOS has more interaction compared to Android os, and the top 2 performing sites are 'Progressive News' & 'The City Daily', while the last 2 performing sites are 'SportsSpam' & 'GossipNews'.
10. Lifestyle stands to be the highest performer, while News and Sports stand at the last position.
11. Overall, iOS is dominant in terms of Impressions across the day of the week.

### Recomendation 

Based on the data analysis, here are some recommendations:

- Focus on the high-performing ads that received a large number of impressions and clicks, especially the ad that had 28,873 impressions and 167 clicks on May 21, 2018, on the 'Business Times' site under the News category.
- Consider optimizing the performance of the ads in the Lifestyle and News categories as they had the highest and second-highest number of interactions, respectively.
- Evaluate the performance of the ads in the Sports and Fashion/Lifestyle categories and identify opportunities for improvement.
- Pay attention to the operating system preferences of the users and focus more on iOS, as it had more interactions compared to Android.
- Identify the top-performing sites like 'Progressive News' and 'The City Daily' and try to secure more ad placements on these sites.
- Consider making changes to the least performing sites like 'SportsSpam' and 'GossipNews' or remove them from the ad campaign to optimize budget.
- Review the performance of different creatives and identify the ones that performed best, such as 'YogaBunny' in Sports creative category and 'Face Fails' in Sports creative category with Mobile Inter-scroller, which had the highest number of video starts and completions, respectively.
- Improve the performance of the ads that had zero video starts and completions, such as 'Artful Dodger' in Art creative category with Mobile Inter-scroller.
- Monitor the day of the week and time of day when the ads receive the most interactions, and consider optimizing the ad placements accordingly.

### Contributing

If you would like to contribute to this project, please submit a pull request or open an issue. We welcome contributions of all kinds, including bug fixes, feature requests, and data analysis insights.

### License

This project is licensed under the MIT License. See LICENSE for more information.
