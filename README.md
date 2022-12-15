# API Calculator challenge

REST API using Express.

## Installation

Use the package manager to install the dependencies.

```bash
npm i
```

## Usage

To test the query we must execute the following command:

```bash
npm start
```

This will execute the nodemon dependency that will allow us to have a server attentive to changes.

# Technical requirements:
﻿You will need to create a single POST endpoint that receives a mathematical expression and returns the result using the calculator specification explained below.

## Calculator Requirements:

-Build an inline calculator capable of understanding math terms.
For example, if I enter the education 10 * (2 + 5) * 10 it should return 700.

## Functional requirements:
The only operations available will be + - * /.
You can assume that you will always have a well-formed equation with at least 1 term.

![ok](https://github.com/vchacin/Calculator-API/tree/main/src/Ok.png)

The only term separator will be the (). We WON'T use § or [ as term division.

![error](https://github.com/vchacin/Calculator-API/tree/main/src/Error.png)