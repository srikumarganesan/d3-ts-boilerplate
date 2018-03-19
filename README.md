# d3-ts-boilerplate
d3-ts-boilerplate can be used to develop D3 visualizations. This project is bundled using
webpack and supports code written in Typescript

# Folder Structure
The TS files are taken from src/ts directory for transpiling. D3 types are added as part of
npm and are imported in the typescript file using import statement. The css files needed
should be placed in the src/css directory and should be included in the app.ts 
file so that they will be bundled.

# Initial Setup
After extracting the project, Please run 'npm install'.

# Development Server
After 'npm install', please execute the command 'npm run build' to launch the development 
server. The server listens at port 8080

# Production build
To generate a production build please execute the command 'npm run build:prod'