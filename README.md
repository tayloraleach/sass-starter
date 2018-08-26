# Starting point for a basic website using Gulp and Sass.

Get going with gulp & sass as a starting point. Autoprefixer and browserSync installed as well. Nothing is done with scripts or images.

## Usage

1. `npm install` to download all the things
2. `gulp watch` to watch your code for changes
3. ???
4. profit

## SASS Compiling Rules

- All sass files live inside the /scss directory
- It will compile two files: print.scss & style.scss
- You can change this inside the gulpfile.js on line 1
- Generally, we tend to use `@import` to include additional files. As shown in the default style.scss
- All compiled files will live inside the app/css directory, under the same filename
- The default files will compile as app/css/style.css and app/css/print.css

## Also

- All other files (JS, HTML, etc) are free to live in the app folder
- Generally, you will upload only the contents of the "app" folder to the server
- Autoprefixer adds browser prefixes only after compiling success of SCSS
- .gitignore is set up for OSX, Windows, and Node
- On every save of every file, the browser will be refreshed automatically
- We watch only HTML, JS and SCSS files for reload
- Manual page reload is required for changes to images paths and such
