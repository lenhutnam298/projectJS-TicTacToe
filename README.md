# Series Project JS

## Tic Tac Toe with Minimax Algorithm

## How to run this project

First of all, you must have nodejs in your system

Open the foler, start Window Powershell

Install additional packages

```
npm install http-server --save-dev
```

```
npm install concurrently --save-dev
```

Go to the package.json file, add this script at last position

```
"scripts": {
    "start": "npm run open",
    "open": "concurrently \"http-server -a localhost -p 1234\" \"open http://localhost:1234/build\""
 }
 ```
 
 Clear command in Window Powershell and type
 ```
 start index.html
 ```
 
 ## Explanation about Minimax Algorithm
 
