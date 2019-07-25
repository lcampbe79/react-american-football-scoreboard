- [ ]  Hold each team's current score in a state value


- [ ]  Render each team's current score that is in state to the DOM.


- [ ]  Be able to click the different buttons to increment the appropriate team's score by the correct amount

### STEP 1 & 2 - Adding Team Scores to the Component's State

- [X] Import the `useState` hook

- [X] Set up the state values for the Lions team score using the state hook

```js
const [value, setValue] = useState(); // Give these better names, and decide whether you want to pass an initial score into the state hook as the initialValue
```

- [X] Set up the state value for the Tigers team score using a second state hook call

### STEP 3 - Render the Scores to the DOM

- [X] The scores in the JSX are currently hardcoded to 32 points each. Remove the hardcoded values

- [X] Render the state values from what we just set up in steps 1 and 2

- [X] Play around with different initial values to test if they are rendering on the DOM correctly

### STEP 4 - Add Click Functionality to Increment the Scores

- [X] Add the `onClick` handler to each function

- [X]  Determine how much you will need to increment the score for each button
  - [X] A touchdown is worth 7 points (assume the following extra point is made)
  - [X] A field goal is worth 3 points
- [X]Inside the click handlers on each button, use the setter functions for each team to increment the appropriate team's score by the correct amount.
