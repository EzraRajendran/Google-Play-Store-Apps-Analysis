# Google Play Store App Dataset Analysis

## Overview
This project focuses on the analysis and visualization of the **Google Play Store App Dataset** using **Power BI**. The dataset has been imported from **MySQL** and analyzed to provide insights into app ratings, user reviews, pricing strategies, and download trends across different app categories. Power BI dashboards are used to present interactive visualizations for better decision-making.

## Data Source
The dataset used in this project was sourced from **MySQL**. The key tables and features extracted for the analysis include:
- **App Name**: The name of the app.
- **Category**: The category to which the app belongs.
- **Rating**: Average user rating.
- **Reviews**: Total number of user reviews.
- **Installs**: Number of app installations.
- **Price**: The price of the app (free or paid).
- **Size**: The size of the app in megabytes.
- **Content Rating**: The age group suitable for the app.
- **Genres**: App genres and sub-genres.
- **Last Updated**: The last date the app was updated.

The data was queried from the **MySQL database** and imported into **Power BI** for further analysis.

## Power BI Visualizations
After importing the data, the following **Power BI** visualizations were created:
1. **App Rating Distribution**: A bar chart visualizing the distribution of app ratings across different categories.
2. **Top Categories by Installs**: A column chart showing the most popular app categories based on the number of installs.
3. **Price vs. Installs**: A scatter plot showing the relationship between app pricing and the number of installs.
4. **Review Analysis**: A line graph analyzing the correlation between user reviews and app ratings over time.
5. **Word Cloud of App Categories**: A word cloud highlighting the most frequent app categories.
6. **App Size vs. Rating**: A bubble chart comparing the size of apps to their average rating.
7. **Revenue Analysis for Paid Apps**: A pie chart analyzing revenue contributions from paid apps.

## How to Use This Power BI Dashboard
1. **Connect to MySQL**: Make sure that your MySQL database is accessible from Power BI. Import the Google Play Store dataset through the **Get Data > MySQL Database** option in Power BI.
2. **Open the Power BI Report**: Use the `.pbix` file available in the repository.
3. **Explore the Dashboards**: Use interactive slicers and filters to analyze data according to your needs.
4. **Customize**: Feel free to customize the report based on specific data insights or queries from MySQL.

## Requirements
- **Power BI Desktop** (latest version).
- A connection to the **MySQL database**.
- MySQL connector for Power BI (installed via Power BI's Get Data > MySQL).

## Installation and Setup
1. Clone this repository:
   ```
   git clone https://github.com/EzraRajendran/Google-Play-Store-Apps-Analysis.git
   ```
2. Connect Power BI to your MySQL database to retrieve the dataset.
3. Open the Power BI report file (`Google_Play_Store_Analysis.pbix`) in Power BI Desktop.
4. Refresh the data from the MySQL database and interact with the visuals.

Let me know if you need further changes!

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## Contributors
- Ezra Rajendran (Data Visualization and Analysis) [Your LinkedIn Profile](https://www.linkedin.com/in/ezra-rajendran-788380218)
