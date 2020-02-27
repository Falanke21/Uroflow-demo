# Uroflow
A hybrid mobile app designed for off-clinical urinal testing.

## Development requirements
 
 - To be able to run this application in general, a few software needs to be installed prior to run the application:
     - Node.js: Download link and instructions can be found on website:
         > https://nodejs.org/en/
     - npm: npm is distributed together with by Node.js
         - Download both package from the above link
         > Detailed step can be found on: https://www.npmjs.com/get-npm
     - expo cli & expo client app: expo cli holds a platform for React Native applications. It allows you to develop and test on your own mobile devices on iOS or Android apps from the same JavaScript code. expo client app is the mobile app that supports expo cli. You don't need expo client app if you want to use Android and iOS simulators. Both download can be found using this link: 
        > https://docs.expo.io/versions/latest/get-started/installation/
     - PostgreSQL database server: Installer and instructions can be found on official website:
         > https://www.postgresql.org/download/

 - Once have above softwares installed on the machine, obtained the code from the repositories from GitHub link; then just a few steps to be able to run the application:
     - Now open a terminal window
     - cd into the project folder from machine's root folder
     - cd into folder called **'api'** by run:
     ``` sh
         cd api
     ```
     - Run following command to have required packages installed for server side:
     ``` sh
         npm install
     ``` 
     - Then after package successfully installed, run following command to start the database server:
     ``` sh
         npm start
     ```

     - Now open up a new terminal window, also cd into project folder, then change into **'sickkids_uroflow'** folder:
     ``` sh
         cd sickkids_uroflow
     ```
     - Run following command to have required packages installed for front-end side:
     ``` sh
         npm install
     ``` 
     - Again, run:
     ``` sh
         npm start
     ```
    to start running this application.

    
    - **Important note: The temporary server url is in ./sickkids_uroflow/config.json. If you wish to run on localhost server, pleast delete the url field in config.json.**

    > A predefined user has already been created for log in credential:
         > Email: frank@gmail.com
         > Password: 123456

- Once the application is up and running, a webpage will popup with a QR Code ready to be scanned:
    - Install **Expo Client** App on your mobile device, and then scan the code will open up the application on your mobile device.

- Now you can play around with this application just as how you would interact with the application as needed!
