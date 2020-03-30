# Work-Day-Scheduler

This is a basic work day scheduler, that is intended to be used to outline the daily to dos of someone's everyday work schedule. This was created using HTML, CSS, and JQuery.

The functionality of this application gives it the ability to tell and update the current date, save whatever changes are made to the schedule via local storage and have the content remain their even afte leaving and returning to the application.

Using moment.js I was able to define a code to retrieve the local time and append it to my html using the .text option of JQuery.

By defining an array using ID's I incorporated into my html and defining a function for that array that takes in the text content of  the array saves and retrieves it from local storage and appends it into the textarea content via the planner id, I was able to give the application the ability to save text content after the save button is clicked.