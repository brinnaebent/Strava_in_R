# Strava_in_R
In progress Running Analysis from the Strava API in R

**Please note that this is in progress and will be updated**

**You will need:**
1. Oath app_id, client_id, and secret from Strava
2. Google Maps API key

**Output:**
1. Dataframe of all activities
2. Dataframe of detailed information of one activity (chosen via user input by date of running activity)
3. Summary Plots (HR and Speed over time currently)
4. Activity Panel (Shows details of a single running activity)

**Notes:**
1. This is configured for Running Activity ONLY. If you want to use this for cycling data, you will have to remove some code with comment: #This allows us to just get the running data (hiking, workouts, cycling data all have different numrows values)
2. *rStrava* and *ggmap* libraries in use



**Activity Panel for Single Activity:**
![ActivityPanel](https://github.com/brinnaebent/Strava_in_R/blob/master/Output_Images/SingleActivityPanel.JPG)

**Summary Plots:**
![ActivityPanel](https://github.com/brinnaebent/Strava_in_R/blob/master/Output_Images/SummaryHR.JPG)
![ActivityPanel](https://github.com/brinnaebent/Strava_in_R/blob/master/Output_Images/SummarySpeed.JPG)
