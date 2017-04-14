# Electralize
Electralize is a fast way to start beautiful 
Electron application using Materialize css.

## Setup

### Clone the repository
```sh
git clone https://github.com/Electralize.git
```

### Install dependencies
```sh
npm install
```

### Launch the application
```sh
npm start
```

## Building an app with Electralize

### Main.js
This is what would usually be your browser
in a normal web application. Change the window size
or bind event on resizing and such in this file.
*Note : You can't access DOM elements in* **main.js**. 

### Index.html
This is your normal index.html file. Use it like your would
normally do, like to place elements in the DOM, render
templates, import headers, etc.

### App.js
This is where you do your application logic : 
Bind events on DOM elements, do HTTP requests, etc.
You can import any other javascript file, either with
the *script* tag, in **index.html** or with *require* :
```html
<script src="./js/app.js"></script>
```
or
```javascript
var app = require('./js/app.js');
```

### CSS
If you want to import you own stylesheets, you
need to include them in the **index.js** file :
```html
 <link rel="stylesheet" href="./css/styles.css">
```
