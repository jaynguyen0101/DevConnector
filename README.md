## Description

- A full-stack web application using (Node.js, Express, React, Redux and MongoDB along with ES6+) to help developers build their profile/portfolio, share posts and get help from other developers Responsive front-end design done with Bootstrap

## Technologies & Tools

* React

* Bootsrap

* MongoDB

* Node.JS

* HTML

* CSS 

# Quick Start 🚀

## Installation and Usage

### Requirements:

* Node.js installed

### Steps:
1. Clone repo on your local machine:
```
$ git clone https://github.com/phuongjay/DevConnector
```

2. Add a default.json file in config folder with the following

```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

3. Install server dependencies

```bash
npm install
```

4. Install client dependencies

```bash
cd client
npm install
```

5. Run both Express & React from root

```bash
npm run dev
```

Check in browser on [http://localhost:5000/](http://localhost:5000/)
