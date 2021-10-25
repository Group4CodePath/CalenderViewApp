# CalenderViewApp
Description
[Calendar is a time management app that allows a user to set reminders and view them.]

App Evaluation
[Evaluation of your app across the following attributes]

Category:Productivity
Mobile:Android 
Story:Calendar is helpful to keep organization a main priority in your day to day 
Market: For everybody looking to plan out there days of the week
Habit:Can be used everyday to stay on schedule
Scope: Easy to use, Click and plan a event on the day you choose

Product Spec
1. User Stories (Required and Optional)
Required Must-have Stories

[Search Options - look at different days and search what they have scheduled for each day]
[CRUD(create,read,update, and delete) functionatility so that the users have full control over their schedule]
…
Optional Nice-to-have Stories

[Sensors - It would be nice to have a sensor that can tell when the user is not on task and can send a notification to them to get back on track]
[Audio - It would be cool if to conect to the alarms on the phone and have the phone actually ring and vibrate to notify the user that it is time to get to work]
[Maps - It would be nice to have a option for the user to set appointments on the app as well and be able to save the location in the app so when its time to go they can just open the app and click on the location and directions open in google maps so they save time on having to search up directions]
…
2. Screen Archetypes
[Login/Register - User signs up or logs into their account]
[Stream - User can scroll through calendar as month or a specific days]
[Detail - Will contain lists of what user has to do for that day]
…
3. Navigation
Tab Navigation (Tab to Screen)

[Home/Login]
[Sign Up ]
[Full Calendar Screen]
[Specific Day Screen]
[Update Screen]
[Add Screen]

Flow Navigation (Screen to Screen)

[From login screen you will either go to signup page or straight to the calendar page]
[From the signup page you will go straight to the calendar page]
[The calendar page will be the home page and to get to a specific day to insert items just click on one of the days]
[The specific days will have a list that contains the todo items. IT will also have buttons Add, Update, and back]
[Back will take you to the calendar page so you can select another day]
[Update will take you to a page with the specific task selected to upate already filled in so the user can change this information and save it by clicking the update button]
[Add will take you to a page that is blank so the user can create a new todo item and add it to the list by hitting the add button]
[The cancel button on both the add and update botton will delete and changes made on the page and take the user back to the todo list]
…
Wireframes
(https://i.imgur.com/rih7LmA.jpg)
![](https://i.imgur.com/6pMn2O6.jpg)

Schema
[This section will be completed in Unit 9]

Models

Property	   /  Type	      /       Description


userId	   /    String	    /       Username/email for account to login their calendar


title	     /    String      /    Name of event


description	 /  String	     /     Description of event by user


createdAt   / 	 DateTime	     /    Date/time event was created


updatedAt  /	   DateTime	     /    Date/time event is updated


startDate	  /   DateTime	    /     When event begins


endDate	    /   DateTime	    /     When event ends


delteItem	 /    DateTime	    /     Item is cleared off of to-do list and calendar

[Schema Models.pdf](https://github.com/Group4CodePath/CalenderViewApp/files/7410378/Schema.Models.pdf)




Networking

•	Home Feed Screen
   o	(Read/GET) Log in or sign up user
   
•	Calendar Screen
   o	(Read/GET) View each month of the calendar
   
•	To-do List Screen
   o	(Read/GET) View existing events and information created and entered by user for the specific day the user selected
   o	(Update/PUT) Mark events as complete 
   o	(Delete) Clear existing events
   
•	Add Screen
   o	(Create/POST) Create a new event for users to post on to-do list
   o	(Update/PUT) Update information for existing events 

