# The purpose of package.json

The main purpose of package.json is that it lists all project dependencies and scripts, acting as a blueprint so others can install exactly whatever the application needs

# Not including node_modules

node_modules shouldn't be included because depending on the project, the size of that folder can get massive. When all the necessary files can be downloaded with a properly tracked package.json one can simply run npm install

# npm install

npm install is important because it helps rebuild the project and match dependencies listed in the package.json file