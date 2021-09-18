<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/CHAUDHARYS1/u-vote">
    <img src="public/images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">U-Vote</h3>

  <p align="center">
    A voting application called **U Vote It**. It is a backend aplication that uses SQL to generate data and the data is handle by routes.
    <br />
    <a href="https://github.com/CHAUDHARYS1/u-vote"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/CHAUDHARYS1/u-vote">View Demo</a>
    ·
    <a href="https://github.com/CHAUDHARYS1/u-vote/issues">Report Bug</a>
    ·
    <a href="https://github.com/CHAUDHARYS1/u-vote/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Simple back-end application built from Express, Node, MySQL. Different endpoints lead to different parts of query. 

### Built With

* [Node.js]()
* [Express.js]()
* [JavaScript]()
* [MySQL]()

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install all NPM packages
   ```sh
   npm install
   ```
3. Start the server
    ```sh
    npm run devStart
    ```

4. Open browser and try different routes!
  ```sh
  http://localhost/3001/add_routes_here/
  ```

List of routes that are available to try out below.

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


<!-- CONTACT -->
## Contact

[Shital Chaudhary](https://www.linkedin.com/in/stlchaudhary/)

[https://github.com/CHAUDHARYS1/u-vote](https://github.com/github_username/repo_name)