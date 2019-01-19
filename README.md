# TodoList App
![Heroku](https://heroku-badge.herokuapp.com/?app=todotaskapp-reactjs)


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This App is the first in the series of small project that I will build during the learning process of the react. These mini projects will be fully functional. I will also deploy these on different platforms like the heroku or the netlify.

## Run locally
To run this app locally on the browser, type the following command: `npm run start`

Open the browser and type [localhost:3000](http://localhost:3000)

## Functionality
This is a very basic Todo App. User can create the todo tasks and on completion of the task can delete them from the list. As of now, they are not stored in the database but will implement this in future.

## Deployment
Following mini project has been deployed on Heroku. Follow are the steps

    .   Install the Heroku CLI : `sudo snap install --classic heroku`
    .   Check for the installation : `heroku --version`
    .   Install in heroku using the cli: `heroku login`
    .   Go to ur app root directory which means u should be inside ur app
    .   Now make sure u commit all the code on the git
    .   Now run this command: ` heroku create <name_of_app> --buildpack mars/create-react-app`
    .   It will create a git repo for u and will give u the link of the app
    .   Now run this command : `git remote add heroku <git repo link generated from above command>`
    .   Now lets push the code to git heroku : `git push heroku master`
    .   It will deploy the code by CLI only
    .   Run `heroku open` to open the app
## Snapshots
![Demo Gif](gif/to-do-app.gif)

`Checkout the project at : https://todotaskapp-reactjs.herokuapp.com/`