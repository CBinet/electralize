# Electralize
**Electralize is a fast way to start beautiful Electron application using Materialize css.**

## Setup

### Install with git

Clone the repository
```sh
git clone https://github.com/CBinet/Electralize.git
```

Install dependencies
```sh
npm install
```

Launch the application
```sh
npm start
```

### Install with npm

Download the npm module
```sh
npm install electralize
```

Launch the application
```sh
npm start
```

## Building an app with Electralize

### Main.js
This is what would usually be your browser
in a normal web application. You can change the window size, 
bind events on resizing and such in this file. <br>
*Note : You can't access DOM elements in* **main.js**. 

### Index.html
This is your normal index.html file. Use it like your would
normally do, like to place elements in the DOM, render
templates, import headers, etc. Example, to add your own stylesheets : <br>
**index.html**
```html
 <link rel="stylesheet" href="./css/styles.css">
```

### App.js
This is where you do your application logic : 
Bind events on DOM elements, do HTTP requests, etc. <br>
You can import any other javascript file, either with
the html *script* tag in your **index.html** file or 
with the **require.js** library : <br>

**index.html**
```html
<script src="./js/app.js"></script> 
``` 
**require.js**
```javascript
var app = require('./js/app.js');
```


