# full stack web development starter template

## client - frontend development

npm run setup - installs bower and npm modules

npm run wire - wire up front end dependencies

npm run start - watch live development server

npm run build - build static final files

npm run server - webserver see build static files

## Global npm install

    sudo npm install -g bower gulp browserify

    sudo npm install -g beefy livereload clean-css-cli


## Optional Global npm install

    sudo npm install -g buble uglify-js

## Optional transform

    "client": "beefy --port 8005 ./client/script/main.js:js/bundle.js --cwd ./client/preview -- --transform jadeify",

## To use on Windows -

The npm modules such as gulp are not installed to the path.

If gulp has been installed globally, you can use the process below:

    1. Create an environmental variable called NODE_PATH

    2. Set it to: %AppData%\npm\node_modules

