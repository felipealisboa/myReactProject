STARTING React

1. start a React project with the command prompt: create-react-app <name of your project> --scripts-version 1.1.5

2. open package.json to changing and add the Port using the lines:
"start": "PORT=3001 react-scripts start",
"start-pc": "set PORT=3001&& react-scripts start",

3. open the terminal and start the server: npm run start-pc

STARTING Json Server

1. copy the db.json into your project folder

2. start Json server with the command prompt: json-server --watch <name of your db>.json
