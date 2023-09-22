# meet

## user stories 


### Achievement 1
As a user, I should be able to filter events by city so that I can see a list of events taking place in that city.

**SCENARIO 1**
<br>
When user hasn’t searched for a specific city, show upcoming events from all cities.

* Given user hasn’t searched for any city;
* When the user opens the app;
* Then the user should see a list of upcoming events.

**SCENARIO 2**
<br>
User should see a list of suggestions when they search for a city.

* Given the main page is open;
* When user starts typing in the city textbox;
* Then the user should receive a list of cities (suggestions) that match what they’ve typed.

**SCENARIO 3**
<br>
User can select a city from the suggested list.

*Given user was typing “Berlin” in the city textbox AND the list of suggested cities is showing;
*When the user selects a city (e.g., “Berlin, Germany”) from the list;
*Then their city should be changed to that city (i.e., “Berlin, Germany”) AND the user should receive a list of upcoming events in that city.

### **Achievement 2**
As a user, I would like to be able to show/hide event details so that I can see more/less information about an event.

**SCENARIO 1**
<br>
When user has selected an event they should be able to show more event details

* Given event selected
* When the event page is open
* Then the user should have an option to show more event details 


**SCENARIO 2**
<br>
When the user has viewed event details they should be able to hide the information

* Given has viewed the details 
* When the more event details page is open 
* Then the user be able to hide the details and go back to the main event page

### **Achievement 3**
As a user, I would like to be able to specify the number of events I want to view in the app so that I can see more or fewer events in the events list at once.

**SCENARIO 1**
<br>
When user is viewing all events they should be able to specify how many events they want to see per page 

* Given the user is scrolling through events
* When the event page list page is open
* Then the user should have an option to select how many events they want to see per page  

### **Achievement 4**
As a user, I would like to be able to use the app when offline so that I can see the events I viewed the last time I was online.

**SCENARIO 1**
<br>
When user is offline they should be able to see the events list they visited on last visit

* Given the user is offline 
* When the application is open
* Then the user should have an option to see events viewed history

**SCENARIO 2**
<br>
When user is offline they should be able to see the event pages they visited on last visit

* Given the user is offline 
* When the user is in the history of events viewed section 
* Then the user should be able to open event pages and see event details

### **Achievement 5**
As a user, I would like to be able to add the app shortcut to my home screen so that I can open the app faster.

**SCENARIO 1**
<br>
When the user is in the native operating system they should be able to add a shortcut to the app to the homescreen or desktop

* Given the user is on their device 
* When the application is open 
* Then the user should have an option to add a shortcut to see the application on their homescreen

### **Achievement 6**
As a user, I would like to be able to see a chart showing the upcoming events in each city so that I know what events are organized in which city.

**SCENARIO 1**
<br>
When the user is in application they should be able to see all upcoming events in each city displayed in a charted visual 

* Given the user is looking at all events (i.e. no city has been selected)  
* When the application is in the chart view
* Then the user should see an aggregation of the number of events in each city 
