#About

Node Package's Statistics API

Our functions will provide statistics of node package.

This is a Node.js API wrapper for the NPM API and Registry.

# Installation

Install via NPM

```js

npm install npm-stat-api --save

```

# Example

i. Get Stats of Package

```js

var npm = require('npm-stat-api');

// Parameters:
// 1. Package Name
// 2. Start Date
// 3. End Date
npm.stat('nutrient-database','2016-07-20','2017-07-20', function(err, response){
	console.log(JSON.stringify(response));
});

```

ii. Get Details of Package

```js

var npm = require('npm-stat-api');

// Parameters:
// 1. Package name
npm.details('nutrient-database', function(err, response){
	console.log(JSON.stringify(response));
});


# Any issue or want more features? Contact me!

This module has been tested under limited scenarios. If you find any issue please feel free to report via one of the below platforms:

Github: <a href="https://github.com/harshdoshi999/npm-stat-api/issues">npm-stat-api</a> | 
Email: harshdoshi999@gmail.com | 
Skype: harshxxx3
