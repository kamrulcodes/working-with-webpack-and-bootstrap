Working with Webpack and Bootstrap
==================================

Intro:
------

To work with webpack we need  

1. Terminal or a good command line tool.
	If you are in windows you need to install gitbash or cmder with gitbash.
	VSCode also has a good default terminal. Installing gitbash is also necessary though.
	To use Gitbash with VSCode terminal:
		* Go to File -> Preferences -> Settings
		* Add the line bellow:
			"terminal.integrated.shell.windows":  "C:\\Program Files\\Git\\bin\\bash.exe"

2. nodejs specifically npm . 
	To check whether node or npm is installed or not write the following two commands in terminal -
		* node --version
		* npm --version

3. package.json file.
	inside the project folder npm init command creates this file.

4. webpack.config.js file.
	This is the configuration file for webpack.

Bootstrap-webpack installation workflow:

1. create project folder.
2. open the folder in vscode.
3. npm init.
4. Install webpack and webpack-dev-server:  
	`npm install webpack webpack-dev-server --save-dev`
5. Install required loaders & plugins:  
	`npm install sass-loader node-sass css-loader extract-text-webpack-plugin babel-core babel-loader babel-preset-latest --save-dev`
6. Edit package.json file like bellow:

7. create webpack.config.js file.

9.  import css, scss and js files from app.js files and continue...
