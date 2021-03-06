# nodejs_Tuttorials

Link To Download The Node-JS:
------------------------------

https://nodejs.org/en/download/

STEPS :
------------

1.) $ mkdir app_name
2.) $ cd app_name 

3.) $ npm init --> creates package.json

4.) $ npm install express-generator -g --> Use the application generator tool, express-generator, to quickly create an application                                                  skeleton.
5.) $ npm express --view=pug app_name --> the following creates an Express app named myapp. 
                                      The app will be created in a folder named myapp in the current working directory 
                                      and the view engine will be set to Pug.
                                      
6.) set DEBUG=myapp:* & npm start --> Use this command to test wether everything is working.

7.) http://localhost:3000/ --> Open this on browser to check wether everything is working good.

INSTALL nodemon TO SIMPLYFY YOUR WORK:
-----------------------------------------------

Just use nodemon instead of node to run your code, 
and now your process will automatically restart when your code changes.
To install, get node.js, then from your terminal run:

npm install -g nodemon

Features

*Automatic restarting of application.
*Detects default file extension to monitor.
*Default support for node & coffeescript, but easy to run any executable (such as python, make, etc).
*Ignoring specific files or directories.
*Watch specific directories.
*Works with server applications or one time run utilities and REPLs.
*Requirable in node apps.
*Open source and available on github.

Use below command to start the server:
