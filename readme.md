# NextGear
A toolkit for NextJs, providing a more complete framework for building web applications. 

While NextJs provides tools for frontend, server rendering, routing and api-endpoints, NextGear provides tools for authentication, authorization, database access, a CLI, validation, and more.

## Installation
NextGear plugs in to an existing NextJs project. To install, run the following command in the root of your NextJs project:

1. 
```
npm install nextgear

```

2. Add the following to the scripts section of your package.json file:

```
"scripts": {
    "gear": "node ./node_modules/nextgear/commandProcessor.js"
}
```

3. Install the NextGear structure into your application by running the following command:

```

npm run gear init

```
This generates a folder in the root of your project called "_nextgear", which contains the NextGear structure.

## Configuration
NextGear is configured by editing the file "_nextgear/config.json". This file contains the following sections:



## Usage
