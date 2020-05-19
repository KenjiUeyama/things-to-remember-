# Deploying an App with a Database to Heroku

### Before you deploy
- Connect your app to mongoDB atlas
1. cd to the project folder
2. Track your codebase in a Git repository 
  - git add .
  - git commit -m "Initial Commit"
  
3. Add a Heroku Git remote
- heroku login
- heroku create

4. Add a Profile
- create a file called Procfile
- web: node app.js in Procfile

5. install dotenv-extended
- npm i dotenv-extended

6. git push heroku master

// TO simply heroku simple static
https://gist.github.com/wh1tney/2ad13aa5fbdd83f6a489 

https://devcenter.heroku.com/articles/preparing-a-codebase-for-heroku-deployment

(https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12386014#questions)
