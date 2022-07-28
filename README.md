# Name: City Weather

# Structure

## Files and Folders
- scripts
    - app.js (for all our DOM manipulation).
    - forecast.js (interacting with weather api and getting data).
- index.html
- styles.css

## Tools and Libs
- Bootstrap
- Accuweather API

# Process

- Create HTML and CSS template (using CSS and Bootstrap for styling).
- Interact with Accuweather API.
    - get city api call.
    - get weather api call.
- implement functions in app.js
- update the UI according to data received.
- Encapsulate api call functions in forecast class.

# Side notes
- Object Shorthand Notation
- Destructuring
    - allows us to take an object and take properties of that object and store them in the variable of that property. e.g:
    ```javascript
    const{ cityInfo, weather } = data;
    ```
