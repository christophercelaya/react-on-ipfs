# Hosting a react-app on IFPS deplyed with Fleek
This project was bootstrapped with [Create React App]

# Hosting
https://fleek.co


# Creating a React Application
### `npx create-react-app my-app`
### `cd my-app`
### `npm start`

Go to http://localhost:3000 in your browser to see the application deployed successfully.

# Fleek Build Settings
- Base directory: Not set
- Build command: npm install && npm run build
- Publish directory: build

# Specify Docker Image
Docker Image name (e.g. node:lts) 
### fleek/create-react-app:node-16

# Changes in .json
This is to make sure the page will also work on the IPFS gateway for urls in /ipfs/HASH formatting.


## Available Scripts
In the project directory, you can run:

### `npm start`
This runs the app in the development mode.\

### `npm test`
Launches the test runner in the interactive watch mode.\

### `npm run build`
Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes.\

### `npm run eject`
**Note: this is a one-way operation. Once you `eject`, you can't go back!**
If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.
Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.
You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
