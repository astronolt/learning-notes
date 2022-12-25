# Project name
***
Short description of the project.


# Headline H1
## Headline H2
### Headline H3
#### Headline H4 
##### Headline H5
###### Headline H6



## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)



## Table of Contents
<a name="general-info"></a>
### General Info




## General Info
***
Write down general information about your project. It is a good idea to always put a project status in the readme file. This is where you can add it. 
### Screenshot
![Image text](/path/to/the/screenshot.png)




## Technologies
***
A list of technologies used within the project:
* [Technology name](https://example.com): Version 12.3 
* [Technology name](https://example.com): Version 2.34
* [Library name](https://example.com): Version 1234




## Installation
***
A little intro about the installation. 
```
$ git clone https://example.com
$ cd ../path/to/the/file
$ npm install
$ npm start
```
Note: To use the application in a special environment use ```lorem ipsum``` to start



# How to use

To use this tool, follow these steps:

1. Install the dependencies by running `npm install`
2. Run the tool using the `node` command and specifying the name of the file (e.g. `node index.js`)
3. Follow the prompts to enter the required information
4. The tool will output the result to the console

You can also specify command-line arguments to customize the tool's behavior. For example, you can use the `-h` flag to display the help message:




## Collaboration
***
Provide instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> Should it encompass several lines?
> This is how you do it.



## FAQs
***
A list of frequently asked questions
1. **This is a question in bold**
Answer to the first question with _italic words_. 
2. __Second question in bold__ 
To answer this question, we use an unordered list:
* First point
* Second Point
* Third point
3. **Third question in bold**
Answer to the third question with *italic words*.
4. **Fourth question in bold**

| Headline 1 in the tablehead | Headline 2 in the tablehead | Headline 3 in the tablehead |
|:--------------|:-------------:|--------------:|
| text-align left | text-align center | text-align right |




### Project Support Features
* Users can signup and login to their accounts
* Public (non-authenticated) users can access all causes on the platform
* Authenticated users can access all causes as well as create a new cause, edit their created cause and also delete what they've created.
### Installation Guide
* Clone this repository [here](https://github.com/blackdevelopa/ProjectSupport.git).
* The develop branch is the most stable branch at any given time, ensure you're working from it.
* Run npm install to install all dependencies
* You can either work with the default mLab database or use your locally installed MongoDB. Do configure to your choice in the application entry file.
* Create an .env file in your project root folder and add your variables. See .env.sample for assistance.
### Usage
* Run npm start:dev to start the application.
* Connect to the API using Postman on port 7066.
### API Endpoints
| HTTP Verbs | Endpoints | Action |
| --- | --- | --- |
| POST | /api/user/signup | To sign up a new user account |
| POST | /api/user/login | To login an existing user account |
| POST | /api/causes | To create a new cause |
| GET | /api/causes | To retrieve all causes on the platform |
| GET | /api/causes/:causeId | To retrieve details of a single cause |
| PATCH | /api/causes/:causeId | To edit the details of a single cause |
| DELETE | /api/causes/:causeId | To delete a single cause |
### Technologies Used
* [NodeJS](https://nodejs.org/) This is a cross-platform runtime environment built on Chrome's V8 JavaScript engine used in running JavaScript codes on the server. It allows for installation and managing of dependencies and communication with databases.
* [ExpressJS](https://www.expresjs.org/) This is a NodeJS web application framework.
* [MongoDB](https://www.mongodb.com/) This is a free open source NOSQL document database with scalability and flexibility. Data are stored in flexible JSON-like documents.
* [Mongoose ODM](https://mongoosejs.com/) This makes it easy to write MongoDB validation by providing a straight-forward, schema-based solution to model to application data.
### Authors
* [Black Developa](https://github.com/blackdevelopa)
* ![alt text](https://avatars0.githubusercontent.com/u/29962968?s=400&u=7753a408ed02e51f88a13a5d11014484bc4d80ee&v=4)
### License
This project is available for use under the MIT License.