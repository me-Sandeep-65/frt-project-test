# planSpot

[Click here for the demo of the project](https://happy-cliff-03d235b00.3.azurestaticapps.net)

### Aim and Objectives:
The main aim for developing this project is to develop a ready to go platform for tourists and travellers where one can get almost every information in a very structured way about the place, he/she wants to visit, like its significance, attractions around the place, inhabitant's sentiments towards the tourists and the place, etc.
As we keep witnessing the incidents like tourists getting misbehaved by the local people for hurting their cultural sentiments. Also from my personal experiences, I can say that many times we need some stuff and the stuff is not available or we can say accessible at the place like medical services, and many other things.

### Approach and Tools Used:
This project will be providing a good amount of information about the all the place with some special tips which will help visitors in planning their trips easily and enjoying them safely. Also there is a feedback form for suggestions, user want to give. The data from the feedback form is being stored in an azure cosmos database account.

## The 2 Azure tools used in the project are:-
   1. Azure Static Web App

      ![Static Web App overview](https://github.com/me-Sandeep-65/frt-project-test/assets/136022073/d675cbca-193c-4504-a47a-ed37e3e43b85)
      This image dipicts the use of Azure Static Web App service.


   2. Azure Cosmos DB for NoSQL

      ![Cosmos DB overview](https://github.com/me-Sandeep-65/frt-project-test/assets/136022073/f51bcb74-8a3c-445d-af8b-095ebf0fdfb8)
      This image dipicts the creation of Azure Cosmos DB.

      ![Database connection](https://github.com/me-Sandeep-65/frt-project-test/assets/136022073/e95a531f-70b3-4d5a-b5c2-e7576ec21909)
      This image dipicts the connection between the Web App and the Cosmos DB database server.

      ![form sample](https://github.com/me-Sandeep-65/frt-project-test/assets/136022073/a70874bd-7d99-4385-9125-cd2a9dda28b1)
      This image is showing the feedback form from which we are taking data and storing it to the Cosmos DB server.

      ![data explorer](https://github.com/me-Sandeep-65/frt-project-test/assets/136022073/aef6eeb5-1a35-4400-a2bc-327bf9753897)
      This image dipicts the storage of data taken from the above form into the Cosmos DB database.



### Repo Explanation:
   #### swa-db-connections
   contains schema and api informations for queris and connection to the data base.

   #### src
      1. css contains all the needed css files including style.css
      2. images contains all the image file used in the project
      3. js contains all the javascript files needed throughout the project including the function that sends feedback data to the server
      4. places contains all the place pages linked in the project for dipiction

##### This project is a mere prototype and a fully working release.
