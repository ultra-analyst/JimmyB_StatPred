Predicting Jimmy Butler's Season Averages: Lets Go Heat!!
As a die-hard Miami Heat fan, I set out to create a project that combines my love for basketball with data science. Jimmy Butler, the best player on the team, plays a crucial role in the Heat's performance. By predicting his season averages, we can get valuable insights into how the team is likely to perform.

Project Overview
This project aims to predict Jimmy Butler's season averages for points (PTS), assists (AST), and rebounds (TRB) using historical game data and machine learning. Here’s how I did it:

Data Collection: Scraped Jimmy Butler's game logs from Basketball Reference for the past ten seasons (2014-2023).
Data Processing: Calculated season averages for PTS, AST, and TRB using pandas.
Model Training: Trained Lasso regression models to predict season averages.
Dashboard Development: Built an interactive Streamlit dashboard to display predictions and historical data.
Deployment: Made the dashboard accessible via the internet using ngrok.
Data Collection
I used BeautifulSoup and requests to collect detailed game logs for Jimmy Butler from Basketball Reference. This data included points, assists, rebounds, minutes played, and more for each game.

Data Processing
Using pandas, I processed the game logs to calculate season averages for PTS, AST, and TRB. This involved converting game statistics to numeric values and handling missing data.

Model Training
I trained three Lasso regression models for PTS, AST, and TRB. Lasso regression was chosen for its ability to handle multicollinearity and perform feature selection. The models used features like field goal attempts (FGA), three-point attempts (3PA), free throw attempts (FTA), minutes played (MP), and the corresponding statistics for the other two targets.

Dashboard Development
The interactive dashboard, built with Streamlit, displays predicted season averages and historical data. It includes a navigation sidebar and a sporty background image to enhance the user experience.

Deployment
To make the dashboard accessible, I used ngrok to create a secure tunnel to my local environment. This allows users to access the Streamlit app via a unique URL.

Conclusion
This project provides valuable insights into Jimmy Butler's performance and, by extension, the Miami Heat's potential performance. It's a dynamic way to keep track of Butler's contributions throughout the season.
