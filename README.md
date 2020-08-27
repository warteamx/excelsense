# DESCRIPTION
Project created as part of a job interview at Excelsense.

Deployed at GAE: https://excelsense.ey.r.appspot.com/
Github Repository: https://github.com/martinrebo/excelsense

## Uses: 
- create-react-app / React Hooks
- Node.js Express.js 
- Rest API
- css modules

## Instructions: 

### (Local)
- npm install
- npm run build
- node (nodemon) server.js

### (Deploy Google App Engine)
- https://cloud.google.com/appengine/docs/standard/nodejs/building-app/deploying-web-service



### TASK
 Endpoints:
Assets: https://6y458uslg3.execute-api.eu-west-3.amazonaws.com/elixos/assets
Entities: https://6y458uslg3.execute-api.eu-west-3.amazonaws.com/elixos/entities

### Description:
Using React.js and Node.js, you are asked to create an application to display in a grid view
(portal) the assets and its related entities. Also, for the entities, you are asked to create a
pop-up context menu (right-click).

### Details:
● The application must have 2 pages/routes. The landing page displaying the assets,
and the entities page.
● The grid view must be a component and the use of external grid/portal frameworks is
not allowed; we want to see how you create/structure components.
● Each portal must have a header row with the object keys of the assets/entities
(t_street_name, t_number, t_city, etc).
● To navigate from the assets page to the entities page, add a button to each row of
data of the entities grid.
● The pop-up context menu must have only 1 option-choice, named test, which will
print the id of the “right-clicked” entity into the console log.
● Have an “empty” row, where you can type and create new rows.
● Use git repository to track the evolution of the project.

### Extra Info:
● We will evaluate the functionality and aesthetic of the app and if the code is
well-structured and commented.
● There is no authentication/user control needed.
● Any extra development and personal ideas for the project will be welcome.
● The data provided has been generated automatically. Do not worry if it does not
make any sense.




This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

- node server.js



