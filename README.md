# Clean-and-analyze-social-media-usage-data-with-Python

# Twitter Tweets EDA

## Overview
This project performs **Exploratory Data Analysis (EDA)** on a dataset of Twitter tweets to uncover insights related to tweet categories, their frequency, and user engagement (likes and reposts).

## Dataset
The dataset consists of Twitter tweets classified into various categories, including Food, Culture, Health, Music, and others. Each tweet contains metadata such as likes, reposts, and category tags.

## Objective
- Identify which categories are most frequently tweeted.
- Analyze average likes and reposts for different categories.
- Determine which topics generate the most engagement.

## Methodology
1. **Data Cleaning**: Removed missing or irrelevant data.
2. **Category-wise Analysis**: Counted the number of tweets in each category.
3. **Engagement Metrics**: Calculated the average likes and reposts per category.
4. **Visualization**: Used plots to represent key findings.

## Key Insights
- **Most Tweeted Categories**: The highest number of tweets belonged to the **Food & Culture** category.
- **Engagement Trends**:
  - Although "Food & Culture" had the most tweets, its engagement in terms of likes and reposts was moderate.
  - Categories like **Health** and **Music** had fewer tweets but received **higher average likes and reposts**, indicating strong audience interaction.

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/twitter-tweets-eda.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   python analysis.py
   ```

## Future Work
- Expand the dataset to include more tweets and categories.
- Perform sentiment analysis on tweets to understand emotional trends.
- Explore temporal trends (e.g., how engagement changes over time).

## Contributing
Feel free to submit pull requests for improvements or new features!


