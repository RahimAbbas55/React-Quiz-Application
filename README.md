# Project Overview:

This is a project built in React framework. This application serves as a quiz app which will allow users to give a quiz related to the popular framework known as "React" and test their knowledge. The API from where the questions are fetched are from a dummy API made using the npm package "json-server". To access this project, simply clone the repository on your machine's terminal or just download the ZIP file of the code. 

# Functionalities: 

-> There are total of 15 questions that are fetched using the help of "json-server" node package.

-> The user can select the appropriate answer from the 4 choices. Once an option is selected, it can't be changed.

-> Upon clicking on "Next", the next question will be displayed on the screen.

-> Once all questions are answered, your total score is calculated and displayed on the screen.

-> There is also a time limit of 7 minutes for the quiz. If the time limit is reached and some questions are left unanswered, the quiz will be finished automatically.

# Miscellaneous:

-> There is a progress bar that shows you progression along with your acquired score out of total score.

-> This project is built totally using the "**useReducer** & **useEffect**" hook. Use Reducer is used for efficient state management and useEffect is used for making API calls. You can find the related documentation here. [React Hooks](https://legacy.reactjs.org/docs/hooks-reference.html)

# Project Images:

### Homepage:

<img width="1386" alt="Screenshot 2024-07-09 at 5 21 38 PM" src="https://github.com/RahimAbbas55/React-Quiz-Application/assets/101935846/26b2477b-f707-4654-ac80-67ce60bd43d9">

### Question Pages:

<img width="1368" alt="Screenshot 2024-07-09 at 5 21 49 PM" src="https://github.com/RahimAbbas55/React-Quiz-Application/assets/101935846/f18c2c85-656a-410a-9bc8-4aafa26666bf">

<img width="1383" alt="Screenshot 2024-07-09 at 5 22 14 PM" src="https://github.com/RahimAbbas55/React-Quiz-Application/assets/101935846/f1c3dc3c-94cc-4815-aa06-eb9bea78887a">

### Quiz Finish Page:

<img width="1387" alt="Screenshot 2024-07-09 at 5 22 35 PM" src="https://github.com/RahimAbbas55/React-Quiz-Application/assets/101935846/cf4efd79-41a9-4f16-b791-4e0a0761c266">


### NOTE: To get better understanding of "json-server", you can visit the site [JSON-SERVER](https://www.npmjs.com/package/json-server).


# Final Remarks:

-> If you want a seamless experience with the project, simply download the project.

-> Open the project in your IDE.

-> Open terminal, write the following command **npm** **instal** **json-server**.(Make sure your have latest version of node installed.)

-> Once the json-server is download, open 2 terminal screen in your IDE

-> Write the following command in one terminal "**npm** **start**" to start the React app & "**npm** **server** **run**" to start your dummy API on your local machine.

-> Refresh your React app page and enjoy!

Feel free to use the project and in case of any queries or confusion related to the project, reach me out. 

Happy Coding😊

# <- If you are unfamiliar with how to start React projects->
## Getting Started with Create React App

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
