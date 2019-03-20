# Eventuality
This is a calendar that is meant to be shared with friends and family. It stores important dates. It displays the weather. It has the ability to schedule local concerts and sporting events. Click [HERE]( https://savycodr.github.io/co-calendar/) to see the application.

## Instructions

* First create a login. Sign up by entering a username and password. This will create a calendar that is unique to you. Next login to the application.

* You may enter your schedule using the Add Events form. Your schedule will appear on the calendar.

* You may perform a search for events in your city by using the Event Search form. A carousel of events will appear that displays the results of your search. You can click on the More Info button to buy tickets. You can click on the Add to Cal button to add the event to your calendar.
 
## Technology

* This application uses JQuery and Javascript to dynamically update the DOM. It listens to a Firebase database. When a new child is added, the calendar is updated. It also dynamically creates a carousel of cards displaying the results of a query to an API.

* The application uses Firebase autentication.

* When a Event Search is performed, a AJAX call is placed to the Ticketmaster API. The results come back in JSON format.

* The framework uses Materialize's CSS and Javascript libraries.

* The user's scheduled events are stored in a Firebase database.

* A call to Weather Open Map API allows us to dynamically display the weather in the calendar.

* Uses Moment javascript libraries to format dates.


## Future Enhancements

* We need a node to store the user's location to display their local weather.

* We need a group node so that many user's can share the same calendar. We would like to color code the schedule by user.

* Want the capability to remove scheduled events from the calendar.
