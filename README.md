# pwa-homework
A budget balancing app designed to teach me how to create apps that work while offline
<br>

## Setup
**Option 1: Heroku** <br>
 This app can be explored on Heroku, however, there are no user accounts so private information should not be stored there.
 Go to https://pwajokeapp.herokuapp.com/ to explore the app on Heroku.  
 <br>
**Option2: Install Locally** <br>
This app can be installed locally and run on a private computer. To do this first go to https://github.com/GormTheWyrm/pwa-homework. Clone that repo onto your local machine. <br>
<br>
This can be done by running the command "git clone https://github.com/GormTheWyrm/pwa-homework" on gitbash or a similar git tool. <br> 
<br>
The app requires express.js, node.js, mongoose.js and morgan and thus must be opened in node.js. Open the root pwa-homework folder in the terminal and run these commands (in this order): <br>
1. npm init -y
2. npm i <br>

I use visual studio code for this part fo the installation but other programs are available. <br>

This app also requires mongoDB so setup and intallation of a mongoDB server is required. Consult your IT department or the mongoDB website and support team for more info on that process.

Once setup is complete, start the server by running: <br>
    ```npm start```
in the terminal. The app can now be accessed by going to ```http://localhost:3000/``` in a web browser. The app has not been tested for compatibility on Internet Explorer.


## functionality

This app allows the user to add or subtract money from a simple balance. It could be used as a simple budgeting tool. <br>
<br>
To use, simply type the name and amount of the transaction in the correct boxes and then hit the relavent ```add funds``` or ```subtract funds``` button. This will add or subtract the amount entered from the balance. <br>
<br>
The app will store the changes made in the mongoDB database while online and in the IndexedDB browser storage if the app goes offline. Upon returning online the app should update the database and clear the values from the IndexedDB browser storage. 

## Contributors
This application was mostly designed by Trilogy Education Services. I just connected the Indexed DB code as part of a class assignment.


