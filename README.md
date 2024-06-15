# Problem Statement
Develop a React To-Do List component allowing task addition, removal, and completion marking. Validate task input, display tasks dynamically, and offer optional sorting, filtering, and localStorage integration. Submit code on Git with brief testing guidance.

# Testing Guidance for To-Do List Application
To ensure the quality and functionality of the To-Do List application, follow these testing guidelines:

  1. Unit Testing:
   - Components: Test each React component separately using a testing library like Jest with React Testing Library.
       - Verify the rendering of components like the task input, buttons, task list, and filter/sort controls.
       - Check state changes (e.g., adding, removing, completing tasks).
     
  2. Functional Testing:
   - Adding Tasks:
       - Enter a task in the input field and click the "Add" button.
       - Verify that the task appears in the list and the input field is cleared.
   - Removing Tasks:
       - Add a few tasks, then click the "Remove" button next to a task.
       - Ensure the task is removed from the list.
   - Marking Tasks as Complete:
       - Add tasks and click the "Complete" button next to a task.
       - Verify that the task is marked as completed (e.g., background color changes).
       - Click "Undo" to unmark the task and verify the state change.
     
  3. Validation Testing:
   - Empty Task Input:
       - Try adding an empty task.
       - Ensure no task is added and proper validation messages are displayed if implemented.
   - Duplicate Tasks:
       - Add the same task multiple times.
       - Check how duplicates are handled, if applicable.
         
  4. Filtering and Sorting Testing:
   - Filter Tasks:
       - Add tasks and mark some as complete.
       - Use the filter options (All, Completed, Incomplete) and verify that the task list displays correctly according to the selected filter.
   - Sort Tasks:
       - Add tasks in random order.
       - Change the sort order (Ascending, Descending) and ensure tasks are sorted alphabetically based on the selected order.
         
  5. LocalStorage Testing:
   - Data Persistence:
       - Add, complete, and remove tasks.
       - Refresh the browser and ensure the tasks persist as expected (tasks should be retrieved from localStorage).
       - Clear localStorage and verify the application handles the absence of tasks correctly.
         
  6. UI/UX Testing:
   - Responsive Design:
       - Test the application on different screen sizes (mobile, tablet, desktop).
       - Ensure the layout is responsive and elements are displayed correctly.
   - Visual Appearance:
       - Verify the background image, color scheme, and overall visual appearance across different devices and browsers.
       - Check hover effects on buttons and the visual distinction between completed and incomplete tasks.
         
  7. Performance Testing:
   - Task Load:
       - Add a large number of tasks and verify the application's performance.
       - Ensure there is no significant lag or delay in rendering tasks.
         
  8. Cross-Browser Testing:
   - Compatibility:
       - Test the application on different browsers (Chrome, Firefox, Safari, Edge).
       - Ensure consistent behavior and appearance across all supported browsers.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
