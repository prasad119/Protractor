# Protractor
    											Protractor installation process
download node.js from the following link:32 bit
https://nodejs.org/dist/v4.2.4/node-v4.2.4-x86.msi
-->install node.js in your system
Test it!
Make sure you have Node and NPM installed by running simple commands to see what version of each is installed and to run a simple test program:
Test Node. To see if Node is installed, open the Windows Command Prompt, Powershell or a similar command line tool, and type node -v. This should print a version number, so you’ll see something like this v0.10.35.

Test NPM. To see if NPM is installed, type npm -v in Terminal. This should print NPM’s version number so you’ll see something like this 1.4.28

Create a test file and run it. A simple way to test that node.js works is to create a JavaScript file: name it hello.js, and just add the code console.log('Node is installed!');. To run the code simply open your command line program, navigate to the folder where you save the file and type node hello.js. This will start Node and run the code in the hello.js file. You should see the output Node is installed!.
Note: Refer  following URL for Node.js:
http://blog.teamtreehouse.com/install-node-js-npm-windows
now node.js installed successfully



Install Protractor:

Setup
Use npm to install Protractor globally with: 
npm install -g protractor
This will install two command line tools, protractor and webdriver-manager. Try running protractor --version to make sure it's working. 
The webdriver-manager is a helper tool to easily get an instance of a Selenium Server running. Use it to download the necessary binaries with: 
webdriver-manager update
Now start up a server with: 
webdriver-manager start
This will start up a Selenium Server and will output a bunch of info logs. Your Protractor test will send requests to this server to control a local browser. You can see information about the status of the server at http://localhost:4444/wd/hub. 

Refer  following URL for Protractor installation
https://angular.github.io/protractor/#/
