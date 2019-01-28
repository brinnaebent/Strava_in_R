# Strava_in_R
In progress Running Analysis from the Strava API in R. 

This is the bones of an analysis I am trying to implement in an RShiny Web App (thus inputs are denoted as such)

For those unfamiliar with [Strava](https://www.strava.com/), Strava is a platform for looking at your data from activities measured with fitness watches/pods/wearables. I have replicated their basic analysis here, which includes plots of pace, distance, elevation, and position overlayed on a map of the activity. Strava does not have easily accessible summary data (HR over time, speed over time, etc), so this is what I am focusing my analysis on. You can see a couple examples of this in the uploaded code. I am working on additional analysis, and will update this code at that time.

**Please note that this is in progress and will be updated**

**You will need:**
1. Oath app_id, client_id, and secret from Strava (I will be writing a blog post on HOW to do this)
2. Google Maps API key

**Output:**
1. Dataframe of all activities
2. Dataframe of detailed information of one activity (chosen via user input by date of running activity)
3. Summary Plots (HR and Speed over time currently)
4. Activity Panel (Shows details of a single running activity)

**Notes:**
1. This is configured for Running Activity ONLY. If you want to use this for cycling data, you will have to remove some code with comment: #This allows us to just get the running data (hiking, workouts, cycling data all have different numrows values)
2. *rStrava* and *ggmap* libraries in use

**Resources:**
1. [To Learn R from Scratch](https://github.com/swirldev/swirl_courses)
2. [rStrava](https://github.com/fawda123/rStrava)
3. [ggmap](https://github.com/dkahle/ggmap)
4. [Future Development in Visualizations](https://medium.com/@vovabilonenko/strava-activities-map-6cbce0380ec1)



**Activity Panel for Single Activity:**
![ActivityPanel](https://github.com/brinnaebent/Strava_in_R/blob/master/Output_Images/SingleActivityPanel.JPG)

**Summary Plots:**
![ActivityPanel](https://github.com/brinnaebent/Strava_in_R/blob/master/Output_Images/SummaryHR.JPG)
![ActivityPanel](https://github.com/brinnaebent/Strava_in_R/blob/master/Output_Images/SummarySpeed.JPG)
