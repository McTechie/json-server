# json-server :globe_with_meridians:
A simple server created using <code>json-server</code> and <code>npm</code>, to help in the development phase of any website / web application.
* Steps to be followed:
  - Clone this repository into your local environment and move into the folder using the terminal.
  - Enter <code>json-server --watch db.json -d 2000 -p 3001</code> in the terminal to get the server up and running.
  - Enter <code>http://localhost:3001/</code> in any web browser of your liking to view your web application.
  
* Points to remember:
  - The code for your web application should be stored in the **public** folder.
    + ***Add your files to be served in this folder***.
  - The **db.json** file contains the data required for the web application in "json" format.
    + ***Edit the file appropriately to suit your application***.
  - The <code>-d</code> flag is used for a delay, and is followed by the time in milli-seconds.
  - The <code>-p</code> flag is used for the port on which your web application will be served, and is followed by the port number.
  - The url <code>http://localhost:3001/</code> should contain the port number as specified while starting the json-server.
