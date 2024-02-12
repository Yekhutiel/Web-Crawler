# Web-Crawler
My first web crawler in javascript

Needs: 
* git repository
	- create this repository first
	- create a folder in your computer then download project from git

* .nvmrc file:
	- holds the version of node used

* package.json file:
	- run "npm init" to auto create

Steps used to create this crawler:

* Create crawler.js:
	- this gets the txt (html) of a web page from a link (make sure that it doesnt take more than one link at the time)
	- after getting the html, it checks the code for 'a' tags
	- for each 'a' tags it extracts valid links and stores them in an array

* Create main.js:
	- this initiates the application

modules actively interacted with:
* 
