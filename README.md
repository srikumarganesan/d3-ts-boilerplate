# d3-boilerplate
d3-boilerplate can be used to develop D3 visualizations. This project is bundled using
webpack and supports code written in ES6

# Folder Structure
The JS files are taken from src/js directory for transpiling. D3 is added as a plugin in 
the webpack.config.js file and is available in the js files. The css files needed should 
be placed in the src/css directory and should be included in the app.js file so that they
will be bundled.

# Initial Setup
After extracting the project, Please run 'npm install'.

# Development Server
After 'npm install', please execute the command 'npm run build' to launch the development 
server. The server listens at port 8080

# Production build
To generate a production build please execute the command 'npm run build:prod'