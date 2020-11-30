React Getting Started

To use React in production, you need NPM and Node.js

## Install NMP and Node.js

# Setting up a React Environment
## Install create-react-app
npm install -g create-react-app

## Create a React Application
npx create-react-app demo-table 

## Run the React Application
Navigate to you project - cd demo-table
Run this command to run the React application
npm start


Set up mock API for testing UI
https://www.pluralsight.com/guides/react-mock-api
1. Create director 
mkdir json-mock-api
2. Navigate to your project's root directory.
cd json-mock-api
3. Create package.json
4. Install dependencies needed to create the mock API
npm install json-server --save
5. Create data for mock API
Create an src folder, and then within it, create a db.json file. Your file structure should look something like this:
json-mock-api/    
    node_modules/
    src/   
    	db.json
    package.json

The db.json file will act as your data source
6. Start your API
json-server --watch src/db.json
or
$ npx json-server --watch src/db.json
7. You should see your API running with an endpoint, http:/localhost:3000/employees

