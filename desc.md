# Problem Description:

You have been tasked with creating a basic counter in a React application. The counter should display an initial value of 0 and have two buttons: one to increment the value and one to decrement it. When the "Increment" button is pressed, the counter value should increase by 1, and when the "Decrement" button is pressed, the counter value should decrease by 1. You need to implement this functionality using React components and state management.

# Solution Approach:

To create a basic counter in React, you can follow these steps:

Set up a React application if you haven't already.

Create a functional component called Counter that will represent the counter and its buttons.

Use the useState hook to manage the counter value in the component's state. Initialize it with the initial value of 0.

Create two buttons: one for incrementing and one for decrementing the counter value.

Implement event handlers for the buttons that update the state based on the button clicked (i.e., increment or decrement).

Display the current counter value on the screen.

# test cases

Descriptive Test Cases:

Initial Render:

When the Counter component is initially rendered, the counter value should be displayed as "Counter: 0".
Increment Button Click:

Click the "Increment" button.
Verify that the counter value increases by 1 (e.g., "Counter: 1").
Decrement Button Click:

Click the "Decrement" button.
Verify that the counter value decreases by 1 (e.g., "Counter: 0").
Multiple Increment and Decrement Clicks:

Click the "Increment" button multiple times.
Verify that the counter value increases accordingly.
Click the "Decrement" button multiple times.
Verify that the counter value decreases accordingly.