# Online-Purchase-Prediction Using Python
Predicting Online Purchase Intent: A Comprehensive Study of Consumer Behavior


Introduction Online consumer behavior is influenced by numerous factors, including website usage patterns, session attributes, and user characteristics. This dataset provides tracking data on user interactions with an online store, with the primary goal of predicting whether a user makes a purchase during a session.

Dataset Description The dataset contains detailed information on user sessions, including both behavioral and contextual features. It consists of 18 variables and 12330 counts, describing user activity, website metrics, and session outcomes, specifically:

Administrative: The number of pages related to website administration visited by the user. 

Administrative_Duration: The time spent on administrative pages during the session (in seconds).

Informational: The number of informational pages visited. 

Informational_Duration: The time spent on informational pages (in seconds). 

ProductRelated: The number of pages related to product browsing. 

ProductRelated_Duration: The time spent on product-related pages (in seconds). 

BounceRates: The percentage of visitors who leave the site after viewing only one page. 

ExitRates: The average percentage of visitors who exit from a specific page. 

PageValues: The monetary value of a page, calculated based on the number of conversions generated. 

SpecialDay: A value ranging from 0 to 1, indicating the closeness of the session date to a special day (e.g., Mother’s Day). 

Categorical Variables:

Month: The month during which the session occurred. 

OperatingSystems: The operating system used by the user. 

Browser: The browser used during the session. 

Region: The geographic region of the user. 

TrafficType: The source of traffic for the session (e.g., direct, referral, ad campaigns). 

VisitorType: Indicates whether the user is a new or returning visitor. 

Weekend: A logical variable indicating whether the session occurred on a weekend (TRUE/FALSE). 


Revenue (Response Variable): A binary outcome indicating whether a purchase was made during the session (1 = TRUE, 0 = FALSE).

Summary of Data Characteristics

The dataset includes both numerical and categorical variables, with Revenue as the binary response variable. Behavioral metrics like BounceRates and ExitRates can provide insights into user engagement and session quality. Contextual variables like SpecialDay and Month reflect temporal aspects that may influence purchasing decisions.



Data source is Kaggle named as "sales_06_FY2020-21 copy"
