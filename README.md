# React GraphQL MERNG Stack

Social media app using ReactJS GraphQL with Apollo Server and MongoDB

## Getting Started

These instructions will give you a copy of the project up and running on
your local machine for development and testing purposes. See deployment
for notes on deploying the project on a live system.

### Prerequisites

Requirements for the software and other tools to build, test and push 
- [NodeJS v14](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)

### Installing

Clone this repo:

    git clone https://github.com/hoanghoa12345/react-graphql-merng-stack.git

Create `config.js` file
```js
module.exports = {
  MONGODB: 'mongodb://localhost:27017/merng',
  SECRET_KEY: 'some-very-secert-key',
};
```

Run this command to install dependencies

    yarn

And run dev server

    yarn start

Open Development Server

![image](https://user-images.githubusercontent.com/44923253/153714350-5db1103d-d8c6-48a7-a12a-790f19afcd5d.png)


## Built With

  - [ReactJS](https://reactjs.org/) - Front End Framework
  - [GraphQL](https://graphql.org/) - Query language for API


