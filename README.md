
# <p align="center">Nology Cloud engineering course</p>
# Front End
## HTML
### <em>What</em>
- Html stands for HyperText Markup Language. 
- It is a language of the World Wide Web.
- It is a standard text formatting language which is used to create and display pages on the Web.
- It can turn text in to images, tables and links

### <em>How</em>
- Used HTML to built pages for projects as part of the training.
- Used HTML tags to built front end of react applications.

### <em>Benefits</em>
- Widely used Markup Language used to built the structure of the website
- It is supported in easy to learn and it easily integrates with other programming languages
    
## CSS
### <em>What</em>
- Cascading Style Sheet is a popular styling language that describes how 
  HTML element are displayed on the screen. 

### <em>How</em>
- After creating the HTML webpages CSS was used to style each element in the webpage.
- All the projects with HTML and react as front end was styled with CSS
      
### <em>Benefits</em>
- Used to define styles for your webpages which can vary from styling the simple text to styling 
  different images on the screen
- CSS styles are stored in files with .css extensions and are imported to the html file.
- Same style can be applied to multiple tags so that we dont have to write seperate style tags for 
  each element in the web page.

##  Javascript
### <em>What</em>
- Javascript is programming language that can be used for adding interactivity and behaviours to a 
  webpage

### <em>How</em>
  [Calculator](https://shameenakoodan.github.io/Calculator/)
- Created a browser based Calculator.
- Built a calculator web app using HTML, SCSS, and JS.This app can accept inputs, do 
  some calculations and give you the correct output. 
- Inputs will be generated from users clicking on the calculator buttons.
- Calculator is deployed using GitHub Pages
- A public GitHub repository is made for the codebase
-  A README.md with a short intro to the project
- It is responsive and works on different screen widths
- Accept multiple inputs, perform an operation and show the output
- UI is designed using SASS and BEM
  
[HangMan](https://shameenakoodan.github.io/HANGMAN/)
- Created a full functioning browser based game using HTML, CSS/SCSS and JavaScript
- This single player game gives the user the option to select from different themes.
- Based on the theme a word with few clues is displayed. User have 7 chances to guess 
  the missing letters

### <em>Benefits</em>
- Javacsript can be used for Front-end development i.e for the the UI's or the client side code.
- It can also be used for the Back-end devlopment i.e for the Servers,API's or the server side code.
- It can be used to built websites, Mobile Apps, Games, Command-line tools and Netwroking
    Applications

##  SCSS
### <em>What</em>
- Syntactically Awesome Style Sheet is the superset of CSS. 
- SCSS is the more advanced version of CSS. 
- SCSS have file extension of .scss.
- SASS adds the feature of @import which lets you import your customized SCSS files

### <em>How</em>
- Demonstrated SASS BEMm knowledge with the following : [SASS-BEM](https://shameenakoodan.github.io/SASS-BEM-Challenge/)
- Worked on several applications that was styled using SASS instead of pure CSS.

### <em>Benefits</em>
- SCSS contains all the features of CSS and contains more features that are not present in CSS which 
  makes it a good choice for developers to use it.
- SCSS is full of advanced features.
- SCSS offers variables, you can shorten your code by using variables. It is a great advantage over 
  conventional CSS.
- SASS allows us to use nested syntax

##  FlexBox
### <em>What</em>
- Flex Box is a layput module which makes it easier to design flexible layout layout structure
  without using float or positioning.
- Flexbox is a one-dimensional layout method for arranging items in rows or columns. 
- Items flex (expand) to fill additional space or shrink to fit into smaller spaces.

### <em>How</em>
- Demonstrated the knowledge of flex blox with the following [Flex1](https://shameenakoodan.github.io/flexbox-challenge2/)
- [Flex2](https://shameenakoodan.github.io/flexbox-challenge/)
- Created a [Calculator](https://shameenakoodan.github.io/Calculator/) and 
  [HangMan](https://shameenakoodan.github.io/HANGMAN/) that uses flex box and display the components



### <em>Benefits</em>
- Positioning child elements becomes easier with flexbox.
- Flexbox is responsive and mobile-friendly.
- We can easily change the order of elements on our webpage without even making changes in HTML.
- Flexbox has a list of important properties that are used to make a flexible container. 
  They are flex-direction, flex-wrap, flex-flow, justify-content, align-items, align-content.


##  Grid
### <em>What</em>
- The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, 
  making it easier to design web pages without having to use floats and positioning.

### <em>How</em>
- Created a [Calculator](https://shameenakoodan.github.io/Calculator/) and 
  [HangMan](https://shameenakoodan.github.io/HANGMAN/) that uses flex box and display the components

### <em>Benefits</em>
- Rather than creating extra HTML elements to contain your grid, columns, and rows, your grid tracks are 
  created within your stylesheet.
- As CSS Grid is native, there is no need to include large libraries like Bootstrap in your projects.
- A grid is two-dimensional and respects both rows and columns. If an element is too big for its cell
  ,the row and/or column will grow accordingly. A grid is ideal for page and form layout.
- It provides Responsiveness based on screen size.

## Media query
### <em>What</em>
- The @media for CSS is used to make different styles for different screen sizes

### <em>How</em>
- Built applications that have a mobile view and desktop view for different screen sizes

### <em>Benefits</em>
- Media queries allow you to vary viewport dimensions based on screen size
- Helps to set different style properties for different devices, including color schemes, font styles,
  motion settings and animations, borders and spacing, and almost any other CSS property.

## React
### <em>What</em>
- React is a Javascript libraray for building User Interfaces
- It provides a virtual DOM

### <em>How</em>
- Built a ticket tracker Application with React as Front End
- Built a Todo list application with React
- Built a full stack application that displays current and previous weather for
  a location of the user's choice. 
  - React front end contains a search box that allows the user to search for a 
    location and display the current weather for that location.
  - React application makes a get request to the endpoint openweathermap API 
  - Created an API with Node/Express that takes the current weather and 
    stores it in a MySQL database using the Sequelize ORM
  - When a user searches for a location that has been previously searched the 
    React frontend displays the weather for that location at a historic time/date. 
  - Styled using SASS
- Built a website using React based on the Punk API
  - Render individual cards based on the information obtained from the API
  - Search functionality based on name and the page content is updated as you 
    type  each letter in the box.
  - Filter the contents based on different conditions
  - Send information to the MySQL database from the React front end to via Node API
  - Used RTL for unit testing

### <em>Benefits</em>
- It re-renders components only when needed
- Provides a file structure to build large applications
- It is a library so provides flexibilty when creating applications
- It will only change individual elements rather than reloading the whole page

## React Testing Library
### <em>What</em>
- is a library used for testing React applications.

### <em>How</em>
- Tested react application to check whether the required components are rendered 
on the screen.
- Tested for error messages and success messgaes

### <em>Benefits</em>
- It focuses on testing components from the end-user's experience rather than 
  testing the implentation and logic of the underlying React components.

## Cloud 
### <em>What</em>
- Cloud is a  massive network of computers owned by different providers like AWS
  Azure and GCP which we pay for and use to deploy our applications.

### <em>How</em>
- Deployed a nodejs application with MongoDB on AWS. Currently  working on a React
  application that should be deployed on AWS and to use AWS s3 bucket for storing
  files.

### <em>Benefits</em>
- Cost is the massive benefit because we only pay for what we use. We dont have to   
  worry about set up cost. 
- We have multiavailablity of resources that means data and applications 
  are available at all time with limited outages.If one server 
  goes down other is available.Integrations are much more easier in cloud

## DevOPS
### <em>What</em>
- DevOPS is a combination of culture and a way of working. DevOPS is a model of
  working were development and operations teams merge and work together  where they 
  work on the entire life cycle of the application starting from dev environmentsetup,
  application development,testing and deploying the applications.A devops engineer 
  typically automates a job.  

### <em>How</em>
- Worked on a full stack application that is  deployed on cloud which  have a CI/CD pipeline 
  to automate the deployment  

### <em>Benefits</em>
- Faster than traditional   
- Continous delivery  
- Cost effective : We can spin down an app if it is not more required which saves a lot of money  
- Efficiency and effectivenes -evrything should be easy to use.
  
## CI/CD
### What
    CI/CD is the process of continous integration and continous delivery and continous deployment.
    This is the process where where we automate the development and deployment.
### How
    We use Jenkins so that any time we make a push to the github it will be affected in the 
    deployed application
### Benefits
    * Allows to integrate small pieces of code which is inturn more manageable
    * Faster release of applications because for the every sprint a smaller version of 
        application is available
    * Easy maintenance
## Jenkins
### What
    Jenkins is a tool used to setup CI/CD using pipelines. With jenkins the code is pulled from a 
    repository like github. Any push to the github repository runs the application with new changes.

### How
    Created a pipeline to automate a node js application where the code is pulled from the git 
    hub repo.
### Benefits
    * It can be easily installed
    * It can be used on different platforms
    * It automates all integration work. 
    * It helps in saving time and money over the project lifecycle.
## Provisioning
### What
    Provisioning allows to automatically install software and its dependencies in a virtual environment
     like virtual box or vmware
### How
    We have a node application that requires a mongodb connection.
    Created an application environment with node in it and used bash to provision it
    Created a environemt for mongo and used bash to provision it. And these both are linked

### Benefits
    * The problem of it works in your system and not mine is solved because applications
        are run on VM's


## OOP
### <em>What</em>
### <em>How</em>
### <em>Benefits</em>
##    Webhook
### <em>What</em>
### <em>How</em>
### <em>Benefits</em>
    React Router
### <em>What</em>
### <em>How</em>
### <em>Benefits</em>
    React State
# Tools
    Terminal

    VsCode
    MySQL Workbench
    Postman
    Trello
    Github
    Jenkins
    VMware Fusion
# Versioning
    Github
# Testing
    Unit Testing - Jest
    Mocha / Chai testing
    TDD
    npm
# Application tier
    Python
    Nodejs / Express
    Node, a backend JS engine uses v8 to execute JS. This enables JS to be run
outside of a browser and in a Node environment.
    CORS
# Database 
    SQL & NoSQL
    MySQL
    Mongodb
    Queries
    ORM
    Mongoose
    Sequelize
# DevOps
    CI/CD pipeline
    Docker
    Terraform
    Containerization
    Packer
    VM
    Vagrant
    Provisioning
    UbuntuARM and Bionic

    AWS
    GCP
    S3 Bucket
    Compute Engine
    AppEngine
    IAS
    PAS
    Amazon EC2
# Networking
    VPC
    Subnet
    IP
    Route Table
    Gateway
# Other
    Linux
    Ubuntu
    Json
    CSV
# Agile
    Sprint
    Scrum
    Trello
      
  

  



##  Networking
### What  
### How
### Benefits
##  Principle of Least Privilege
### What  
### How
### Benefits
##  IAC
### What  
### How
### Benefits
##  Packer
### What  
### How
### Benefits


### What
### How
### Benefits