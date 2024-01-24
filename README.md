# Dilan's Travel Blog Analysis

## Aim of the Project

This project aims to conduct a comprehensive analysis and interpretation of the main business metrics for Dilan's travel blog. By delving into the raw user activity data, we will create a funnel to understand the blog's user behavior. Key aspects of the analysis include subscriber and revenue regression with forecasting, ultimately providing actionable suggestions for the business.

## Data Set Overview

In this repository, you will find the raw user activity data from Dilan's blog spanning from January 1, 2018, to March 31, 2018. The dataset comprises approximately 600,000 rows, capturing various user interactions. The dataset is available in CSV format, with a semicolon (`;`) serving as the field separator.

### Data Columns

1. **Date and Time:** The first column represents the date and time of the event in the format `YYYY-MM-DD HH:MM:SS`.

2. **Event Type:** The second column indicates the type of event, categorized into three types: `read`, `subscribe`, and `buy`.

    - For `read` events:
        - First-time reader fields: `country`, `user_id`, `source`, `topic`
        - Returning reader fields: `country`, `user_id`, `topic`
        
    - For `subscribe` events:
        - One additional column: `user_id`
        
    - For `buy` events:
        - Two additional columns: `user_id` and `price` of the purchased product.

### Examples

- First-time reader: `2018-03-30 23:59:56;read;country_5;2458361283;Reddit;Asia`
- Returning reader: `2018-03-31 05:04:50;read;country_4;2458361208;Africa`
- Subscriber: `2018-03-30 23:48:48;subscribe;2458173588`
- Purchase: `2018-03-30 23:11:30;buy;2458339835;80`

### Additional Details

- The dataset is a single, unsegmented file, eliminating the need for automation and data refreshing.
- The country column has 8 different values (country_1 to country_8).
- The source column has 3 different values (Reddit, AdWords, SEO).
- The topic column includes 6 different values (Africa, Europe, South America, North America, Australia, Asia).
- The course price column includes two values (8 and 80).

## Google Data Studio Riport


## Suggestions

Let's uncover valuable insights to enhance Dilan's travel blog business!
