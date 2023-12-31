![HEART Framework](https://github.com/BrandtOgden/CSC305Team225/blob/e0cef99368e84f92abbd12c116b0d24f6afde9ef/src/HEART%20Framework.jpg)

Metrics   
**1. Net Promoter Score (Sam):** Our NPS will involve a survey which will rate from 1-10 how likely the user is to recommend our app.  This will allow us to gauge the current average level of user satisfaction.

**2. Daily Active Users (James):** When a user logs into their account for the first time in a day, the Firebase database could be updated from Thunkable to reflect this action. Using this data, we can organize it such that we can observe trends to determine how well our app is performing.    

**3. Churn Rate (Jackson):** When a user logs in, a Thunkable observer block in the Login Screen would fire, sending a signal to Firebase with the current date/time. Firebase would update the relevant database backend with the new data point, which will be made available with others in the next Google Analytics report upon request. A possible graph representing these data points might be a line graph, where the data is categorized into hours or days. The graph would show the number of new logins, not total logins.

**4. Number of Downloads (Henry):**  We can retrieve these metrics by accessing the developer panel in the google play store and iOS store which will show us the amount of downloads on each platform and give us insight as to how well our app is doing. 

**5. Time on App Per Day (Brandt):** Firebase Analytics already has a built in function for computing the average time that users on the app are engaged. It does so by determining how long all of the users of the app are actually focused on the app (if the app is in the foreground not background) and dividing that by the total number of users. This would give us a good idea of how long people are using our app and in what ways the things we add to the app affect user engagement. It would also be very easy to implement as it's already built into Firebase Analytics so all we would have to do is set up the SDK for Android Studio.  
