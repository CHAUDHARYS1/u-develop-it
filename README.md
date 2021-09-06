# U Vote It
## Description
A voting application called **U Vote It**. It is a backend aplication that uses sql to generate data and the data is handle by routes.

## Installation
  To run the application, do the following(in order):  
  1) ```git clone``` the repo to your desired local folder
  2) ```open a``` with the code editor of your choice
  3) open terminal
  5) install all the packages and dependensies by running ```npm install``` in the CLI
  4) start the server by typing the following in the cli: ```npm run devStart``` (nodemon)
  5) open browser and type the following in the url: ```http://localhost:3001/api/candidates/``` 
  6) list of routes are below:

| Type of request 	| Routes             | Results             |
|-----------------	|-----------------	 | -----------------   |
| GET             	| /api/candidates 	 | show all candidates          |
| GET             	| /api/candidate/:id | show a single candidate      |      	
| POST            	| /api/candidate     | add a candidate          	  |
| PUT               | /api/candidate/:id | change data for a candidate  |      	
| DELETE            | /api/candidate/:id | delete a candidate           |
| GET          	    | /api/parties       | show all parties             |
| GET             	| /api/party/:id     | show a single party          |
| DELETE            | /api/party/:id     | delete party                 |
| GET               | /api/votes         | shows list of votes          |
| POST              | /api/vote          | add votes                    |
| GET               | /api/voters        | shows list of voters         |
| GET               | /api/voter/:id     | shows a single voter         |
| POST              | /api/voter         | add a voter                  |    
| PUT               | /api/voter/:id     | change data for a voter      |
| DELETE            | /api/voter/:id     | delete voter                 |
### Language
- Node.js
- Express.js w/ Nodemon
- JavaScript
- MySQL 
