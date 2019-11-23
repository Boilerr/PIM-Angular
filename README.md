# PIM-Angular
Angular part of PIM project

[![](https://img.shields.io/github/release/Boilerr/ColorShop-Angular.svg)](https://github.com/Boilerr/ColorShop-Angular/releases)[![](https://img.shields.io/github/issues/Boilerr/ColorShop-Angular.svg)](https://github.com/Boilerr/ColorShop-Angular/issues) [![](https://img.shields.io/github/forks/Boilerr/ColorShop-Angular.svg)](https://github.com/Boilerr/ColorShop-Angular/network) [![](https://img.shields.io/github/stars/Boilerr/ColorShop-Angular.svg)](https://github.com/Boilerr/ColorShop-Angular/stargazers) 


## Restoring Development setup
  1. Install Git and Angular    
  2. ```$ git clone ...``` // clone this project to local machine
  3. ```$ npm install```  // load all needed files 
  4. ```$ ng serve``` // test project, http://localhost:4200
 

## Contributing 
 1. **Fork** the repo on GitHub, fork from this Upstream to your Origin
 2. **Clone** the project to your own local machine and restore Development setup
 3. **Commit** changes to your own branch, on local machine:
	1. Create you own feature branch on local git repositories    
    ```$ git checkout -b feature/yourbranchname develop```  //create branch feature/yourbranchname from develop, and switch to new branch    
    2. Do changes to local yourbranchname git branch with many commits you wont    
	3. After feature complete you need to do all unit testing and linter
	4. Merge to develop on local git    
    ```$ git checkout develop```    //switched to branch 'develop'    
    ```$ git merge --no-ff feature/yourbranchname```    
 	```$ git branch -d feature/yourbranchname``` //delete local branch    
 4. **Push** your work to your Origin on GitHub    
 	```$ git push develop```
 5. Submit a **Pull request**, from your Origin to this Upstream, so that we can review your changes

NOTE: Be sure to merge the latest from "upstream" before making a pull request!


## Git commit message guideline 
	Short (72 chars or less) summary, starts, for example, with "Fix bug" and not "Fixed
	bug"

	Body
	More detailed explanatory text 
	Wrap it to 72 characters
	The blank line separating the summary from the body is critical (unless you omit
	the body entirely)

	- Bullet points are okay, too

## Other
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.19.
