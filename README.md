# PostmanCollections

This is a sample server Petstore server.
https://petstore.swagger.io

Create report:

    Install newman: 
    
    - download and install Node.js from: https://nodejs.org/en/download/prebuilt-installer/current 
    
    - open the terminal and install Newman: 
        sudo npm install -g newman
        newman --version 
        
    -  get a report in the terminal using Newman:
        newman run <path to postman_collection.json>

    - insatll newman-reporter-htmlextra: 
        sudo npm install -g newman-reporter-htmlextra
    
    - create report:
        newman run <path to postman_collection.json> --reporters htmlextra --reporter-htmlextra-export <path to report folder> 
