# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling when dealing with user inputs.

The `bug.js` file shows a route that fetches a user by ID. It attempts to parse the ID as an integer but fails to handle cases where the ID is not a number, leading to potential crashes or unexpected behavior. 

The `bugSolution.js` file demonstrates the correct approach, which involves using `isNaN` to check if the ID is a number and providing appropriate error handling for invalid inputs.