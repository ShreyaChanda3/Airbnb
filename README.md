# Airbnb Superhost Analysis

This project analyzes Airbnb listings in Barcelona to identify the factors that contribute to a host becoming a Superhost. The analysis uses data provided by Inside Airbnb, including detailed review and calendar data from September 2022.

## Introduction

Barcelona welcomes more than 27 million visitors each year. With a daily charge of $167 and monthly earnings of $2691 for Barcelona's short-term Airbnb properties, the average occupancy rate is 78%. Listings are created when hosts put their properties on the Airbnb system and are available for guests to stay. Listings include all the information that describes the properties like price, description, and location.

## Motivation

The main objective of this case study is to help new customers using Airbnb to create transparency for the factors determining a host to become a Superhost. The goal is to improve areas that can help a host become a Superhost by analyzing different attributes and finding their importance level to narrow down the focus on them.

## Literature Review

The “Superhost” badge is awarded to hosts who receive good reviews, which impacts an accommodation's review volume and ratings. A Superhost may have more visibility, earning potential, and exclusive rewards for their outstanding hospitality.

## Theory and Hypotheses

- **Null Hypothesis:** There is no effect of ratings or other variables on a host being a Superhost.
- **Alternate Hypothesis:** There is an effect of ratings or other variables on a host being a Superhost.

## Data Source

The data used in this analysis is sourced from [Inside Airbnb](https://insideairbnb.com/barcelona/).

## About the Data

- **Listings:** Detailed listings data about hosts, Airbnb houses, and prices. Attributes include `id`, `name`, `host_id`, `host_name`, `room_type`, and `price`.
- **Reviews:** Detailed reviews given by guests. Key attributes include `number_of_reviews`, `last_review`, and `reviews_per_month`.
- **Location:** Details about Airbnb locations in Barcelona city. Attributes include `neighbourhood_group`, `neighbourhood`, `longitude`, and `latitude`.
- **Ratings**

## Data Cleaning

Data cleaning involved checking for null values and removing unnecessary attributes.

## Visualization

Various visualizations were created to explore the data, such as correlation matrices and logistic regression models.

## Results

- One unit increase in the review scores rating increases the odds of a host being a Superhost by a factor of 33.71, holding other variables constant.
- Review scores, beds, bathrooms, host response rate, host response time, number of reviews, and reviews per month have odds ratios of 1, indicating no change.
- The null hypothesis is rejected in favor of the alternate hypothesis.

## Conclusion

The analysis indicates that the highest correlation to a host being a Superhost is their review scores rating. By focusing on attributes like reviews, ratings, and response testing ratios, hosts can improve their performance and likelihood of becoming a Superhost.

## References

- Xie, K., & Mao, Z. (2017). The impacts of quality and quantity attributes of Airbnb hosts on listing performance. *International Journal of Contemporary Hospitality Management, 29*(9), 2240-2260. [Link](https://doi.org/10.1108/IJCHM-07-2016-0345)
- Guttentag, D. (2019). Progress on Airbnb: a literature review. *Journal of Hospitality and Tourism Technology, 10*(4), 814-844. [Link](https://doi.org/10.1108/JHTT-08-2018-0075)
- Zervas, G., Proserpio, D., & Byers, J. (2015). A first look at online reputation on Airbnb, where every stay is above average. [Link](https://ssrn.com/abstract=2554500)
