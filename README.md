# Ola-vs-UBER-Data-Analysis-Project-

About this Dataset Uber and Ola Play Store Reviews Dataset Description: This dataset contains Play Store reviews for two prominent car services, Uber and Ola. It provides valuable insights into user experiences, feedback, and sentiments towards these ride-sharing apps. The dataset includes various attributes such as review ID, user name, review title, review description, rating, thumbs up count, review date, developer response, developer response date, app version, language code, and country code. The dataset is a valuable resource for analyzing user sentiments, trends, and contributing factors that impact user satisfaction.  Columns: review_id: A unique identifier for each review. user_name: The username associated with the review. review_title: The title of the review. review_description: The main content of the review provided by the user. rating: The user's rating for the app (e.g., on a scale of 1 to 5). thumbs_up: The count of thumbs up given by other users for this review. review_date: The date when the review was posted. developer_response: Any response provided by the app developer to the review. developer_response_date: The date of the developer's response. appVersion: The version of the app when the review was submitted. language_code: The code representing the language of the review. country_code: The code representing the country of the user. Preprocessing Steps: Missing Values Handling: Rows with missing values in essential columns were dropped to ensure data integrity. Text Cleaning: Text data in review_title and review_description were converted to lowercase, and special characters, punctuation, and extra white spaces were removed. Rating Normalization: Ratings were scaled to a consistent 0-10 scale for better comparability. Date Parsing: Dates in review_date and developer_response_date were parsed into a standardized format. Categorical Encoding: Categorical variables (appVersion, language_code, country_code) were one-hot encoded for analysis. Sentiment Analysis: Sentiment analysis was performed on review_description to categorize reviews as positive, negative, or neutral. Feature Engineering: A new feature indicating the presence of developer responses was created for further analysis. Citations: Google Play Store. (https://play.google.com/store/apps/details?id=com.ubercab&hl=en_IN&gl=US&pli=1) Google Play Store. (https://play.google.com/store/apps/details?id=com.olacabs.customer&hl=en_IN&gl=US) App Store. (https://play.google.com/store/apps/details?id=com.ubercab&hl=en_IN&gl=US) App Store. (https://apps.apple.com/us/app/ola-cabs/id539179365?see-all=reviews) Potential Use Cases: Sentiment Analysis: Understand user sentiment towards Uber and Ola through sentiment analysis of reviews. Rating Analysis: Analyze the distribution of ratings and trends in user satisfaction. Top Contributors: Identify influential users based on review count and thumbs up count. Developer Response Impact: Investigate whether developer responses influence user satisfaction. Feature Request Analysis: Analyze recurring keywords to identify common feature requests. Geographical I
