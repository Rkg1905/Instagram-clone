# Instagram-clone
Instagam clone web application using MERN

[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://www.instagram.com/rakesh.gupta1905/)

##Show some :heart: and :star: the repo to support the project.

This repository is still under development and I will continue to add more features to it.

[![click here to use this instagram clone]](https://instagram-clone1905-2.herokuapp.com/)
![gif](Instagram-clone-full.gif)

## Features

1. sign/ signup
2. forgot password
3. can watch others profile
4. create post
5. comment, like, dislike on post
6. search users using user id
7. subscribe and unsubscribe users
8. can delete own post from home


## Requirement

Reactjs
Nodejs
Expressjs
MongoDB
(atleast at begineer level)

## dependencies 

On server side
    "bcrypt": "^5.0.0",
    "express": "^4.17.1",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^5.11.8",
    "nodemailer": "^6.4.17",
    "nodemailer-sendgrid-transport": "^0.2.0"
    
    
On Client side
    "materialize-css": "^1.0.0-rc.2",
    "react": "^17.0.1",
    "react-dom": "^17.0.1",
    "react-router-dom": "^5.2.0",
    "react-scripts": "4.0.1",
    "web-vitals": "^0.2.4"

## Getting Started
If you are working on locally on your computor
follow these steps
1. download the repository
2. open the command line, reach to destination file and type
  npm start
2. create a dev.js file inside config directory
3. copy and paste these code in dev.js
module.exports={
    MONGOURI:"mongodb+srv://<username>:<cluster_password>@cluster0.l8a7n.mongodb.net/<dbname>?retryWrites=true&w=majority",
    jwt_secret:"asvinlfknarifnoa",
    SENDGRID_API:"<login to sendgrid>",
    EMAIL:"http:localhost:3000"
}
  
  
  
  In above code, you have to add mongodb atlas and create a sendmail api on https://sendgrid.com/
  walk through youtube, for the reference.
  still you won't get it. then ping me on instagram (https://www.instagram.com/rakesh.gupta1905/)

## Upcoming features

* messaging
* video/ gif support
* can share post
* High security
* more reliable and beatiful UI
* custom camera


## Questions
if you have any querries related to any thing, you can ping me on Instagram (https://www.instagram.com/rakesh.gupta1905/)

## How to contribute
1. Fork the the project
2. Create your feature branch (git checkout -b my-new-feature)
3. Make required changes and commit (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request


## License
Copyright (c) 2021, Rkg1905
    
    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



