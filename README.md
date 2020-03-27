<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]
[![Forks][forks-shield]][forks-url]
[![MIT License][license-shield]][license-url]

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
 
 Other way, you can open index.html in your browser for testing
 
 ## Explanation about Minimax Algorithm
 
 ## Update
 
 
<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/lenhutnam298/projectJS-TicTacToe?style=flat-square
[contributors-url]: https://github.com/lenhutnam298/projectJS-TicTacToe/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/lenhutnam298/projectJS-TicTacToe?style=flat-square
[forks-url]: https://github.com/lenhutnam298/projectJS-TicTacToe/network/members

[stars-shield]: https://img.shields.io/github/stars/lenhutnam298/projectJS-TicTacToe?style=flat-square
[stars-url]: https://github.com/lenhutnam298/projectJS-TicTacToe/stargazers

[license-shield]: https://img.shields.io/github/license/lenhutnam298/projectJS-TicTacToe?style=flat-square
[license-url]: https://github.com/lenhutnam298/projectJS-TicTacToe/blob/master/LICENSE