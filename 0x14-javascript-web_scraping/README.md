#0x14. JavaScript - Web scraping
********************************
This project involved practicing file I/O on Node.js and using the NPM request
framework to interact with the [Star Wars](https://swapi.co/),
[JSONplaceholder](https://jsonplaceholder.typicode.com), and
[Twitter](https://developer.twitter.com/en/docs/api-reference-index) API's.
********************************
#Usage
Allowed editors: vi, vim, emacs
All your files will be interpreted on Ubuntu 20.04 LTS using node (version 14.x)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/node
A README.md file, at the root of the folder of the project, is mandatory
Your code should be semistandard compliant. Rules of Standard + semicolons on top. Also as reference: AirBnB style
All your files must be executable
The length of your files will be tested using wc
You are not allowed to use var
More Info
Install Node 14
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
$ sudo apt-get install -y nodejs
Install semi-standard
Documentation

$ sudo npm install semistandard --global
Install request module and use it
Documentation

$ sudo npm install request --global
$ export NODE_PATH=/usr/lib/node_modules
Notes: Request module has been deprecated since February 2020 - the team is considering alternative to replace this module - however, it’s a really simple and powerful module for practicing web-scraping in JavaScript (and still used a lot in the industry).
#Tasks
#[0-readme.js]/(0. Readme)
* Write a script that reads and prints the content of a file.
#[1-writeme.js]/(1. Write me)
* Write a script that writes a string to a file.
#[2-statuscode.js]/(2. Status code)
* Write a script that display the status code of a GET request.
#[3-starwars_title.js]/(3. Star wars movie title)
* Write a script that prints the title of a Star Wars movie where the episode number matches a given integer.
#[4-starwars_count.js]/(4-starwars_count.js)
* Write a script that prints the number of movies where the character “Wedge Antilles” is present.
#[5-request_store.js]/(5. Loripsum)
* Write a script that gets the contents of a webpage and stores it in a file.5. Loripsum
#[6-completed_tasks.js]/(6. How many completed?)
* Write a script that computes the number of tasks completed by user id.
