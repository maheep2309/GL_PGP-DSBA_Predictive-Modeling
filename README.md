# GL_PGP-DSBA_Predictive-Modeling
This project builds a linear regression model to identify the key drivers of first-day content viewership on an OTT platform. It analyzes visitor traffic, marketing activity, seasonal effects, release timing, and content attributes to help ShowTime optimize viewership and improve content performance.

# Project Summary
This project analyzes first-day content viewership on ShowTime, an OTT platform, using an end-to-end statistical and machine-learning workflow. Starting with data exploration, it examines visitor trends, ad impressions, trailer engagement, release timing, genre, seasons, and the presence of major sports events.

Comprehensive preprocessing—handling data types, feature engineering, encoding categorical variables, and retaining genuine outliers—prepares the dataset for modeling. A linear regression model is then developed, refined through multicollinearity checks, p-value–based variable elimination, and assumptions testing (linearity, independence, normality, and homoscedasticity).

The final model performs well, explaining ~79% of the variance in viewership and generalizing effectively across train and test datasets. Key drivers include number of visitors, trailer views, day of release, seasonality, and whether a major sports event is occurring—while many genre categories and ad impressions show little impact.

The project concludes with actionable recommendations: increase user traffic, strengthen trailer promotion, optimize release days, adjust scheduling around sports events, and leverage seasonal peaks to maximize engagement. These insights enable ShowTime to design targeted marketing, boost viewership, and make data-backed content decisions.
