# Project Name

> Do you know the Dewey Decimal System? Conan the Librarian does!  This application will help you organize and keep track of your book collection and books you want to collect.  Organize by author, title, or dewey decimal, and download a list of your bookshelf to organize your personal collection.

## Team

  - __Product Owner__: Michelle Lockett 
  - __Scrum Master__: Chris Poole
  - __Development Team Members__: Jeramiah Cerda, Chris Poole, Michelle Lockett

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

> Create your own mysql database locally.  Create a file config/cleardb.js with the following format:

const CLEARDB = {
 host: 'your-host-url-here',
 database: 'name-of-your-database-here',
 uname: 'your-username-here',
 pword: 'your-password-here'
};
module.exports = CLEARDB;

> Set up a google API key.  Create a file config/google.js with the following format:

const API_KEY = `your-googleBooks-API here`;
module.exports = API_KEY;

Add your entire config folder to .gitignore

From the root directory, npm start

## Requirements

- Node 0.10.x
- Mysql
- Sequelize
- Angularjs
- Express

## Development

### Installing Dependencies

From within the root directory:

```
npm install

```

### Roadmap

View the project roadmap [here](LINK_TO_PROJECT_ISSUES)


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

