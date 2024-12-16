# Using Survival Analysis for Better MLB Player Evaluation

This repository contains the work of a group project completed for ISyE 6740: Computational Data Analytics (Machine Learning) at Georgia Institute of Technology. A team of classmates and I evaulated MLB players performance statistics' and monetary value. Below is a brief overview of the project as well as my personal contributions to the gorup work. 

Major League Baseball (MLB) teams are constantly looking for new ways to gain a competitive advantage. One such way is using analytics to improve player valuation and acquisition. Inspired by the pioneering Moneyball approach, this project introduces a novel approach combining survival analysis and machine learning to better predict player decline and incorporate this decline information into valuation. Using data from the Lahman Baseball Database (1871-2023), we developed a Random Survival Forest model to predict individual player's survival and hazard functions. From these functions, we then predicted performance decline events, achieving 88.15\% accuracy for position players and 84.06\% accuracy for pitchers within a one-year margin. Building on these insights, we implemented two Random Forest Regressors for salary prediction - one using traditional statistics and another incorporating survival analysis features. Our results show that current salaries are not properly accounting for player decline and that older players are being overvalued. Overall, we show that using a survival analysis-centric approach can give MLB decision makers more information on potential player acquisitions and current roster members. 

More details about the project can be read in the Final Report File. 

My contributions to the project included:
- defining the "decline event"
    - desgined and implemented a clear definition for when a specific player experiences a decline in performance 
- survival analysis code for both pitchers and position players
    - used Random Suvival Forest to accurately predict which year a player is going to experience their decline and their          hazard function
- documented and reported the above coding work in the powerpoint presentation and final report
