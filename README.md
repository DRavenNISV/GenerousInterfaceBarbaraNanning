# Generous Interface Barbara Nanning
A prototype of a generous interface visualizing information related to the works of Barbara Nanning.

## Installation

The following applications will need to be installed in order to be able to run the prototype.

* [Stardog](http://www.stardog.com/)
* [Firebase](https://firebase.google.com/)

## Running the Firebase Hosting Service 
Based on the [Tool Installation Guide](https://docs.google.com/document/d/1kIlm7j4_SyxA3upn5uokUhQF-7f-qjAkkGtFW_H4lJk/edit#) for the VU-Course Project Interactive Multimedia

* Set up an account at https://firebase.google.com/ and create a new project in https://console.firebase.google.com.
* Go to https://nodejs.org/en/download/ and download the file corresponding to your operating system.
* After finishing the installation, open cmd/terminal and check version with command: node -v
* In the cmd/terminal, type: npm install -g firebase-tools
* Open cmd/terminal in the directory of your application.
* Use command: firebase init and input Y followed by Enter.
* Use arrow keys to get to ‘Hosting’ and press Space to select it. Hit Enter to continue.
* Select “Existing Project” when prompted.
* Use arrow keys to get to the project you made earlier in the Firebase console and hit Enter.
* When asked about which folder to use as public directory, hit Enter (any files you put in the public folder that will be created, are the files that get deployed/hosted by Firebase - **move the source code here**).
* When asked to configure as single-page app, input N and hit Enter.
* In cmd/terminal, input firebase serve. This launches a server on your local machine. You can now access your application in your browser by going to http://localhost:5000.
* After making changes to your project locally, use firebase deploy to publish the application to the server. You can now access the application on the web (http://myproject-XY.firebaseapp.com).

## Running the Application

The following things need to be done in order to run the application:

* Serve or Deploy the Firebase Application based on the source code available in this repository (excluding the .owl file) as stated above.
* Install Stardog and run a Stardog Server (Windows: stardog-admin.bat server start --disable-security / Mac/Linux stardog-admin server start --disable-security)
* Create a Stardog Database based on the provided ontology (.owl file). **Important** Make sure the endpoint of this database corresponds with the endpoint specified in the index.html file.   
* Access the application on http://localhost:5000.

## Built With

* [Stardog](http://www.stardog.com/) 
* [Protege](https://protege.stanford.edu/) 
* [TagCloud](https://github.com/mcc108/TagCloud) - Used to create the interactive TagCloud element

## Acknowledgements

* Barbara Nanning
* The Netherlands Institute for Sound and Vision
* [Cong Min](https://github.com/mcc108)
