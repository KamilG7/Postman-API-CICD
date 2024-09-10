Postman Automated API Testing for Trello

########################################

1. Description
  Example Postman testing project. Subject is Trello website. Project utilizes capabilities of Chai library. Main functionalities of the site was tested.
  Project can be use as example for anyone who would like to built similiar testing suit.

2. TC Documentation
  You can find test case documentation in the "Documentation - TC" folder in main directory. All Test Cases I wrote and used for this project are explained in details.

3. Security
  Included KEY and Token are generated purly for test purpose on dummy account therfore do not cause security problem and are free to use.

4. Getting Started
   You can just copy project to your machine and run it as it is.
   You can also run project by Newman command in CMD:
   Newman run COLLECTION_PATH -e ENV_PATH

5. CI/CD
   Project was successfully integrated with Jenkins. To run project in jenkins you can use below commands:
   npm install -g newman
   Newman run COLLECTION_PATH -e ENV_PATH

6. Reports
   Project was build in a way allowing run with postman runner, newman and jenkins. Reports from runs you can find in folders in main directory.

   KamilG7
  
