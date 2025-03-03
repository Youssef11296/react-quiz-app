# Overview

This project is a simple web application built and created by React and Redux.

# How It Works

This project is a simple mcq exam app that allows the user to answer each question.
The user have to login first to be allowed to start the exam.
The app puts seven question to the user provided with 4 options.
Every qiuestion have 3 wrong answer and a single correct answer.
The user have to select the correct answer, or at select any answer of the fourth options to jump to the next question of the exam.

# Main Techs & Dependencies

- React JS

- React Router Dom

- React Hook Form

- Redux

- TypeScript

- Sass

- Material UI

# Project Structure

- The src directory that is the main directory in the root:
- The src consists of main directories such as

  - compnents: contains main components of the project such as

    - Header, LoginForm, QuestionItem, QuestionsList and RedirectedMessage
      Good to mention that these components are the main blocks of every page in the app.
      Basicaly every single page or screen consists of one component or more

  - screens: contains the main pages of the app every screen consists of one or more component, and   the screens directory consists of three directory each one is a screen or a page of the application such as
    
    - ExamScreen: the user can nvigate to it from the header nav by clicking the Exam link
    
    - ResultScreen: the user can nvigate to it from the header nav by clicking the Result link
    
    - LoginScreen: the first screen that appears to the user where he has to fill all field of the form to start the exam and the user can nvigate to it as well to logout from the header nav by clicking the Login or Logout link

  - store: contains the redux actions, reducers and the direct index file that contains and export the root redux store

  - utils: conntains the data that the app depend on such as questions json file

  - sass: contains the global styles

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
