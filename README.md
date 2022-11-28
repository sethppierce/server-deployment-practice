# LAB - Class 01

## Project: Server Deployment Practice

### Author: Seth Pierce

### Problem Domain

 Create a web server using CI and CD and get used to the general process of building and deploying servers.

### Links and Resources

- [ci/cd](https://github.com/sethppierce/server-deployment-practice/actions) (GitHub Actions)
- [prod deployment](https://server-deployment-practice-tek3.onrender.com/) (when applicable)
- [dev deployment](https://server-deployment-practice-dev.onrender.com/) (when applicable)

### Setup

#### `.env` requirements (where applicable)

- PORT: 3001

#### How to initialize/run your application (where applicable)

- nodemon

#### Features / Routes

- Feature One: Deploy to Dev
- GET: `/` - route to hit
- Feature Two: Deploy to Prod
- GET: `/bad` - route to hit

#### Tests

- How do you run tests?
  - npm test
- Any tests of note?
  - handles root path
  - handles invalid requests
  - handles errors

#### UML

![UML](./lab01-uml.png)
