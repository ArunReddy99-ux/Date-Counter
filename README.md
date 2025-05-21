# Day Counter
A simple React application that allows users to increment or decrement a day counter and see the resulting date, starting from June 21, 2027. Users can adjust the step size for incrementing/decrementing and reset the counter at any time.

## Features
Adjustable Step: Change how many days to increment or decrement using a slider. 
Direct Count Input: Enter a specific count value directly. 
Increment/Decrement Buttons: Increase or decrease the count by the current step. 
Date Display: Shows the calculated date based on the count. 
Reset: Reset the counter and step to their initial values. 
## Implementation Overview
State Management: Uses React's useReducer hook to manage the state, which includes the current count and step. 
Reducer Logic: Handles actions for incrementing, decrementing, setting the count, setting the step, and resetting. 
Date Calculation: The displayed date is calculated by adding the current count to a fixed base date (June 21, 2027). 
## User Interface:
A slider allows users to set the step value (0–10). 
Buttons and an input field let users adjust the count. 
The resulting date is displayed in a readable format.  
A reset button restores the initial state.  
## Project Structure
App.js: Main app component.  
DateCounter.js: Contains the day counter logic and UI.  
index.js: Entry point for React.  
index.css: Basic styling.  
