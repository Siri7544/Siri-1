# Siri
Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@siri234fhv 
Aakashdeveloper
/
Apr_Ang_Mrng
Public
Code
Issues
Pull requests
5
Actions
Projects
Wiki
Security
Insights
Apr_Ang_Mrng/extra
@Aakashdeveloper
Aakashdeveloper a
Latest commit 5a434eb on May 22, 2020
 History
 1 contributor
195 lines (147 sloc)  4.19 KB


FullStack
Template
Login Logout
> MEAN
///////////////////////
Reactive Form
Multiple langugae
Testing app
-----------------------
production
--------------
Docker
Nginx

-----------
Github
Mock Api

----Not----
Backend API
DataBase


----------
Angular1 => Angular2=>Angula9

----------
//Folder Walk Through
//Create first page
//Adding Css

//////////////
Node.JS 
Github
Visual Studio Code

https://code.visualstudio.com/
 https://github.com/ 
https://nodejs.org/en/ 


SPA => Single Page application


Angular help to make single page appliication
using component base structure with typescript


local package /global package

////////////////////////////////////
Step to install package.json
/////////////////////////////////

**NodeJs must be install
> navigate to folder where you want to generate the file using cmd
> npm init
> "answer all question"
> type "yes"


////////////////////////////////////
Step to install local package
/////////////////////////////////
> navigate to folder where you want to generate the file using cmd
> npm i packagename


////////////////////////////////////
Step to install Global package
/////////////////////////////////

#Window
> Run cmd as admin
> npm i -g @angular/cli


#Mac/Linuc
> Open Terminal
> sudo npm i -g @angular/cli

////////////////////////////////////
Step to create Angular App
/////////////////////////////////
#Window
//One Time//
> Run cmd as admin
> npm i -g @angular/cli

//EveryTime//
>navigate to folder where you want to generate the application using cmd
>ng new appname
>cd appname
>npm start
>localhost:4200

-----------------------------------
#Mac/Linux
//One Time//
> Open Terminal
> sudo npm i -g @angular/cli

//EveryTime//
>navigate to folder where you want to generate the application using Terminal
>ng new appname
>cd appname
>npm start
>localhost:4200


/////////////
Angular Building Block
///////////////

>Module=> Where we declare all things   (NgModule)
>Component =>Contains HTML CSS Logic    {Component}
>Pipe=> Run Time data manupulation       {Pipe,PipeTransform}
>Services=> To Call the API(Dependency Injection) {Injectable}
>Routig=> Nvigate between pages           {Routes,RRouterModule}
>Directive=> Smalll portion of page        {Directive}
  

import
@> decorator
export

angular.json > main.ts > app.module.ts > app.component.ts

//////////////////////////////////////
   File Walkthrough
/////////////////////////////////////
tslint.json ==> make strutcure of code
tsconfig.spec.json => help to locate test files
tsconfig.json => it will tell where is build code and which version to target
tsconfig.app.json => to locate application file
ReadMe.md => Detail Description of application
package.json => used for Dependency, commands and small Description
package-lock.json => used for child Dependency
angular.json => fist file to run and locate all content of application
.gitignore => thing we dont want to push to git
.editorconfig => For editor standards
src/style.css => main style file of application
src/polyfills => help to render application of all browser
src/index.html => first and only file that  will load  in browser
src/favicon=> simple icon
src/assets => for all static file images /videos/script
src/environment => help to build for prod /dev 
src/app => all development happen here
src/main => this will help to locate main module

////////
Data Binding
////////////
one way
> databinding  {{}} > 
> poperty Binding []
> event binding ()
two way  [()]


cli
>Command line interface
>ng g c hotels


parent --> Child [] (@Input)
child --> parent () (@output)

90/5*2

> npm i -g json-server 
> json-server --watch db.json --port 8900


ng-pristine   ng-untouched  ng-invalid
ng-dirty      ng-touched    ng-valid

/******GetAllUser*****/
(GET)> http://localhost:5000/api/auth/users

/******Register*****/
(POST)> http://localhost:5000/api/auth/register
(body) => {"name":"Aakash", "email":"aa@gmail.com","password":"12345678","role":"user?"}


/******Login*****/
(POST) => http://localhost:5000/api/auth/login
(body)  => {"email":"aa@gmail.com","password":"12345678"}
(response)=> {auth:true,token:'dgsdg'}

/******UserInfo*****/
(GET) => http://localhost:5000/api/auth/userinfo
(Header) => {'x-access-token':'token value from login'}
(response) => {userinfo}
© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
