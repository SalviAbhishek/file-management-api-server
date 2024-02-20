# File Management Api Server

[Live Link](https://file-management-server.onrender.com/)

## Installation

```sh
cd file-management-api-server
npm i
npm start
```

Now import the postman collection with json named "file-management-server"
and check all the apis


## Plugins

| Plugin                         | README                                                       |
| ------------------------------ | ------------------------------------------------------------ |
| bcryptjs                       | https://www.npmjs.com/package/bcryptjs                       |
| cors                           | https://www.npmjs.com/package/cors                           |
| express                        | https://www.npmjs.com/package/express                        |
| express-session                | https://www.npmjs.com/package/express-session                |
| joi                            | https://www.npmjs.com/package/joi                            |
| jsonwebtoken                   | https://www.npmjs.com/package/jsonwebtoken                   |
| mongoose                       | https://www.npmjs.com/package/mongoose                       |
| mongoose-aggregate-paginate-v2 | https://www.npmjs.com/package/mongoose-aggregate-paginate-v2 |
| multer                         | https://www.npmjs.com/package/multer                         |
| passport                       | https://www.npmjs.com/package/passport                       |
| passport-local                 | https://www.npmjs.com/package/multer                         |

## Folder Structure

- we have "function" folder for functionality part
- "routes" folder separately for mentioning the routes we gonna use
- "models" folder for mongodb collections
- "utilities" folder for the keys, mongo connections and collections names
- "middlewares" folder for middleware like authenticator which authenticates the user apis

## Deployment

- firstly i was looking for the heroku but they have shutted their free plan so i came across a new platform called render which allows me host the express app as a service for free of cost where it is directly connected to my github repo

## License

MIT

[git-repo-url]: https://github.com/joemccann/dillinger.git
