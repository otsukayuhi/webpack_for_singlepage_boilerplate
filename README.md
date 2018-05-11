# webpack_for_singlepage_boilerplate

## node.js version
v8.11.1

## start
1. npm install
2. enjoy !

## how to use
### Webpack
- Babel
- Sass (Scss) and CSS background image URL Encode.

### EJS
- "_*.ejs" file is no transpile.

### npm scripts
```webpack:serve```  
"webpack-dev-server" start up.

```webpack:build```  
Webpack build assets.

```webpack:watch```  
Webpack build assets and watch files.

```ejs:build```  
"*.ejs" file is transpile.

```ejs:clean```  
"dist/**/_*.html" file remove.

```ejs:watch```  
"ejs:build" task run.

```start```  
"ejs:watch" task and "webpack:serve" task run.

### plugins and Library
- "jquery": "^3.3.1"
- "vue": "^2.5.16"
- "picturefill": "^3.0.2"
- "sanitize.css": "^5.0.0"