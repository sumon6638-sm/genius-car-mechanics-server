one time:
1. heroku account open
2. Heroku software install

Every Project:
1. git init
2. .gitingnore (node_modules, .env)
3. push everything to git
4. make sure you have this script: "start": "node index.js",
5. make sure: put process.env.PORT infront of your port number
6. heroku login
7. heroku create (only one time for a project)
8. git push heroku main


--------update--------
1. save everything check locally
2. git add ., git commit -m '', git push
3. git push heroku main