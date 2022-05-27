# PWA Text Editor
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
This text editor application takes an existing text editor app and implemented methods for getting and storing data to an IndexedDB database. With the use of "idb", which is a lightweight wrapper around the IndexedDB API. This application is deployed through Heroku.
Deployed link: https://fierce-sands-51003.herokuapp.com/

## Installation
To clone the repo to your local machine, please run this command in the terminal
```
git clone
``` 
To use this application, run this command in the terminal to install all dependencies from the root directory
```
npm install
```
To start the application, run this command from the root directory
```
npm run start
```

To install the application, click on the install button shown on the webpage

<img src="assets/installbtn.png" width=100px>

## GIFs Demo

### Install application
<img src="assets/manifest.gif" width=900px>

### Storing and retrieving content from IndexedDB with no errors
<img src="assets/getPutText.gif" width=900px>

## Technology Used
| Library/Packages|
| ------------- |
| ![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)| 
| ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)|
| ![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)|

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) 2022 Kristy Guo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
