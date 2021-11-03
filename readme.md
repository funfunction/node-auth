


# Technology Used
- node.js
- Authentication
- JWT
- MongoDB
- Mongoose


# Instructions

- replace MongoDB connection string with your own connection string in ./app/config/db.config

```npm i```

```npm run start```

- the backend service will be available on port 8081



# Deployment

if you wish to deploy to Heroku, this set of commands will deploy it:

```git config --local remote.heroku.url https://git.heroku.com/NODEAPPNAMEUNIQUE.git```

```git config --local remote.heroku.fetch +refs/heads/*:refs/remotes/heroku/*```

```heroku create NODEAPPNAMEUNIQUE```

```heroku git:remote -a NODEAPPNAMEUNIQUE```

```git push heroku master```

