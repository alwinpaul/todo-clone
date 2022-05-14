# About this project

# **** Todo Clone ****

The idea is to create a simple todo app. This app will be for Desktop, tablets and mobile view.

It will be a single page app.

## Flow

1.  Login screen
2. homepage

### Login screen:
	a) login via username password
	b) Login via google auth, implemented with firebase API

### Homepage:
	to list all the tasks for the day.

## Features to have:
1. Add/remove a task
2. Select priority (High, Medium, Low)
3. Add due date and time
4. Mark as done
5. Start task button, to show the timer since task has started.
6. Put task on hold
7. Add a note to the task. (use case: when user puts the task on hold, he can add a note as to whit is on hold and will be picked up later. not restricted to on hold). Can add multiple notes, which will be displayed on expanding the task card to reveal more information about the task.
8. Initial cards will be collapsed.
9. Show calendar, on selected a date show task for the day. (similar to one in below design)
10. Group tasks by projects
11. Backlog of tasks
12. Overdue tasks, move to backlog


## Design Inspiration:
https://dribbble.com/shots/15637013-Teamwork-Dashboard-concept-redesign?utm_source=Clipboard_Shot&utm_campaign=guffqa&utm_content=Teamwork%20-%20Dashboard%20concept%20redesign&utm_medium=Social_Share&utm_source=Clipboard_Shot&utm_campaign=guffqa&utm_content=Teamwork%20-%20Dashboard%20concept%20redesign&utm_medium=Social_Share


## Stack -Phase 1

Frontend:
React + redux

Backend:
Firebase (static API)

API:
REST/Graphql


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
