# Getting Started

Once complete delete the ReadME from your project folder

## Install node-sass as a dev dependency in project directory

[node-sass](https://www.npmjs.com/package/node-sass)

or run the code:

```
npm install node-sass --save-dev
```

### Add Script to package.json

```
"scripts": {
                        Input file    Output file
   "sass": "node-sass sass/main.scss css/style.css -w"
}
```
* 
* Add `-w` suffix will watch for changes then update and compile your css file with every change detected on main.scss
* This means that you want to import everything to main.scss before adding any styles so that all changes on other scss files will be changed on main.scss

#### cd into the directory where package.json is located:

```
npm run sass
```

* Remember that package.json will start looking out from the directory that it is in.
