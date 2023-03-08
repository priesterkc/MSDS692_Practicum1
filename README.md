# MSDS692_Practicum1
MSDS 692 - Practicum 1 project (Spring 2023) on anime score predictions

## Background

The data used in this project was sourced from the Anime Analytics Gigasheet, which was scrapped from MyAnimeList. Based on informational data fields for anime, I wanted to build a machine learning model to predict the average user score for an anime and understand the traits that contribute to users highly rating a series. This would be useful for Western distribution companies to get an idea of how well an anime will potentially be perceived by an audience, to know if it is beneficial to invest in licensing a series.

## Key Insights

- 24,012 rows and 31 columns in original dataset reduced to 12,829 rows and 8 columns
- Anime series are typically broadcasted on television
- Most are original story works but manga is the highest adaptation source
- Majority of series do not have a demographic categorization and are suitable for people of all ages
- Comedy is the most frequent genre but is commonly paired with another genre type
- Toei Animation production studio dominates the industry with its famous and long-lasting series
- MyAnimeList ranking is determined by mean score from users, while popularity is determined by number of users that added a series to their Watch list
    - Gintama (several seasons and supplemetary material) make up 35% of top 20 ranked series
    - Fullmetal Alchemist: Brotherhood is in top 5 of both user score and popularity rankings
- Scikit-Learn linear regression model and Keras Sequential neural network performed as well as random guessing on training data assessment, and constant inaccuracy on test data
- Further improvements needed for future experimentation
    - Improve data quality (text user reviews and plot synopsis)
    - Other numerical output machine learning algorithm
    - Continue tweaking neural network parameters

## References and project material

[Original dataset on Anime Analytics Gigasheet](https://www.gigasheet.com/data-community/anime-analytics)

[Anime Score Project video presentation](https://drive.google.com/file/d/1Y2BA2WXf-MMXo3dcEjYLJuezeBBL4ueX/view?usp=share_link)

[Data visualizations on Tableau Public](https://public.tableau.com/app/profile/kenisha/viz/MAL_anime_score_predictions/studios)

[Project code on Github](https://github.com/priesterkc/MSDS692_Practicum1)
