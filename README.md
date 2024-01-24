# 05 Third-Party APIs: Work Day Scheduler

## Your Task

Create a simple calendar application that allows a user to save events for each hour of a typical working day (9am&ndash;5pm) by modifying starter code. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

You'll need to use the [Day.js](https://day.js.org/en/) library to work with date and time. Be sure to read the documentation carefully and concentrate on using Day.js in the browser.

## User Story

```md
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```md
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours of 9am&ndash;5pm
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

The following animation demonstrates the application functionality:

<!-- @TODO: create ticket to review/update image) -->
![A user clicks on slots on the color-coded calendar and edits the events.](./Assets/05-third-party-apis-homework-demo.gif)

#HTML

1. A main header.
2. Div element within container fluid
3. List of time blocks with 24hr to 12hr conversion
4. Text input fields
5. Save buttons
6. Font families
7. Bootstrap component
8. Jquery links

## CSS

1. HTML attributes and classes

##JavaScript

1. Tells engine to load HTML and CSS first.
2. Displays current time and date.
3. Get nearby values.
4. Takes change from sibling HTML description attribute.
5. Takes change from parent HTML ID attribute.
6. Sets items to local storage.
7. Loads saved data from local storage for each hour created. Should follow HTML 24h to 12 h conversion.
8. Gets current number of hours.
9. Use of Day.js
10. Loops over time blocks.
11. Checks if time is past, present, future. Clicks into HTML/CSS given classes of past, present, future.
12. Re-runs function.



- - -
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
