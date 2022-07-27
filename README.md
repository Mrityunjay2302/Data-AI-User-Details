# React Assignment

In this assignment, you have to create a react application which provides following functionalities:

1: list users in a table </br>
2: search for a user </br>
3: sort columns of table </br>
4: pagination of users list </br>
5: detail page for each user on a separate route </br>
6: Attention to detail and meeting all requirements is important in the project. Completing it in less time will not give you any preference.

## Task Overview

App functions:

1: Table: The main screen should list all users in the table </br>
  &nbsp; i: columns to show: first_name, last_name, age, web and email</br>
  &nbsp; ii: clicking on first name should open Details page on a separate route</br>
  &nbsp; iii: website links (web) should open in a new browser tab</br>
2: Search: Allow to search using first_name or last_name</br>
3: Pagination: Data should be paginated</br>
4: Sort: All columns should be sortable in both ascending and descending order</br>
5: Detail: Detail page should show all fields of user</br>
   &nbsp; i: Clicking on back navigates back to Users table page</br>
6: Routing: Table and Detail pages should be on their respective routes:</br>
   &nbsp; i: Route for Table page should be /users</br>
   &nbsp; ii: Route for Detail page should /users/<id> (e.g: /users/2, if id of user is 2)
   
   ## API endpoint
   https://datapeace-storage.s3-us-west-2.amazonaws.com/dummy_data/users.json
  
  ## Instructions
  Use react for this assignment.</br>
 1: IMPORTANT: Pagination, search and sorting should be implemented manually in the frontend only. DO NOT use 3rd party library or inbuilt feature for these.</br>
 2: Data should be fetched from the api provided (and not stored in source code)</br>
 3: yarn start (or npm run start if using npm) should start the app</br>
 4: yarn bulid (or npm run build if using npm) should build the app</br>
 5: repo should not contain irrelevant folders/files like node_modules, build directories etc.</br>
 6: Follow the wireframes provided closely</br>
 7: Follow these steps for submission:</br>
&nbsp; i: Fork the repository</br>
&nbsp; ii: Create issues and work on them in their respective branches</br>
&nbsp; iii: Complete the tasks while following all instructions</br>
&nbsp; iv: Create MRs and merge into main branch</br>
&nbsp; v: When done, Test if all task requirements are met and instructions followed</br>
&nbsp; vi: Push code to github</br>
&nbsp; vii: Deploy and host the app 

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
