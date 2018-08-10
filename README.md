# bAmazon
Node.js and MySQL exercise displaying inventory control... somewhat!!!

Check out the app in action [here](https://drive.google.com/file/d/1zwzRFIxe-ZZkSMubHAXIpbUz3Lg344R3/view) 

# Setup 
First clone this repo to your local directory.

Next, navigate to your repo in your command terminal, and enter:

npm install

This will ensure you have all the necessary NPM packages installed to run this generator.

Next, you will need to run the bamazonSchema.sql file in your SQL IDE of choice. Be sure to have your SQL server of choice running, such as MySQL.

You will likely be prompted for your credentials. Change the PORT or keep it the same... you decide. 

Open or paste the contents of the bamazonSchema.sql file in the IDE, and run the script, preferably function by function in order to check possible errors as you go along.

Next, navigate to the bamazonCustomer.js and bamazonManager.js, and in the connection variable (defined at the top of these files), enter in your password in the password property of the object in the ''.

You are now ready to shop or manage bAmazon.

# Overview
There are two apps, bamazonCustomer.js and bamazonManager.js. With the customer app; you can purchase items, while with the manager app you can check inventory, order, etc. 
