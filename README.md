# Hocho
AngularJS 1.X API client generator from Swagger JSON specification

# Description
This package generates a AngularJS 1.X TypeScript classes from a Swagger v2.0 specification file. The code is generated using Mustache templates.

# How to get it working

## Installation

`npm install hocho`

or  

`git clone https://github.com/Ian5015/hocho`  
`cd hocho`  
`npm install`  
`npm run build`  

## Usage

From command line, run:
```
hocho -s [yopur/path/to/swagger.json]
```

or
```
hocho -u [url/of/your/swagger.json]
```

## Example usage:

This command will generate API client described in swagger.json file to ./out folder
```
hocho -s ./tests/apis/swagger.json -o ./out
```

or from repository directory run:
```
node ./src/hocho -s ./tests/apis/swagger.json -o ./out
```

## Note:
This project was inspired by [swagger-js-codegen](https://github.com/wcandillon/swagger-js-codegen) project.
