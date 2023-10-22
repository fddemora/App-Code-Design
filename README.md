# App-Code-Design
SNHU final project

<br>

<b>Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?</b>

I had basically took the requirements or functionality that app should demonstrate, and built those requirements into a user interface. The challenge had been how to create the user interface that met both the requirements and UI design principles. Would this functionality via the UI work for the a user? If not, then I moved on to consider alternatives to the UI design. Thus, building the user interface was a simple task, the challenge was considering the users needs.  

<br>

<b>What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?</b>

Utilizing the navigation bar at the bottom of the app screen and using buttons is what helped my UI appear as user friendly as possible. For instance, the add functionality is at the bottom of the main screen. The screen is then routed to a new page where the data gets entered. The user journey in the app was also considered. After the user enters the data and clicks to submit, the app routes the user back to the main screen with the updated UI, displayed the recent changes from the user. This is also reflected on the database side. 
<br>

<b>How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?</b><br>

Since this was my first mobile project via Android Studio, I decided to keep the Java language API as simple as possible. This was reflected most on the UI side, where I used activities and intents versus fragments and other app layouts. I also implemented a architecture of a model view controller, where the model had access to the app's database, and the view's controller would access the model for any database updates. The main activity would also have the most control for application, so there is a lot of interaction between the main controller and the model. Another strategy was for the model to access the database via API's that removed any potential for SQL injections, thus removing any possible security incidents. Finally, there was some database designs planning as well involved with the application logic, where only a particular user's records are shared. If this wasn't done, all of the records in the database would be shown to the user. 

<b>How did you test to ensure your code was functional? Why is this process important and what did it reveal?</b><br>

Any succesful application is most likely due to intial user feedback. Unfortunately, I didn't have the opportunity as of now to do a user acceptance test. Most of the tests done in the application has been focused on the application logic. Is this functionality working? If not, why not and where is the problem coming from? Thus, I used a lot of my debugging skills through out the project. 

<b>Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge? </b><br>

I would have to innovate when considering new functionalities to the application. For example, I first considered the login functionality of the application. I planned the logic and how it should work and then implemented accordingly. Afterwards, I planned how the main activity would work with the main activity. I decided that there should be a different database table from the login's table in order to match and display the users data to the main activity, and so I planned and implemented the logic accordingly as well. I kept this pattern through out the development phase.
<br>

<b>In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?</b> <br>
I am excited about the application done so far because I have tested all the functionalities to make sure it works as it is supposed to. However, I also am aware of where the application would fail. For instance, there is minimal data validation in the add activity, so it may not behave as it should if someone were to try to break it. 







