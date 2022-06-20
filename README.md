# erply_api_automation
This repo holds automated test cases generated via postaman and executed using newman

Pre requistes to execute API tests

node js package newman is being used to run postman collections json in CLI
To istalll configure nemwna  please run below commands

npm i newman  - to install newman package
npm i newman-reporter-html  - Installs newman reporters

To execute api tests , in the root directory execute below commands

#headless mode without logs
newman run erply_postman_collection.json -r html 

#headless mode with logs
newman run erply_postman_collection.json 
