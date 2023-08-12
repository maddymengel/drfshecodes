# Crowdfunding Back End
    { Maddy Mengel }

## Planning:
### Concept/Name
The idea was to create an app that connects creatives and charities.

Name of website: magicmakers

Connecting creativity and charities

### Intended Audience/User Stories
The intended audience is creatives wanting to create and support charities. Creatives are anyone who wishes to make magic and learn a new skill. 

The use of the website will be:
- charities post projects to the creatives that they need help with or would like
- creatives assign and share the project they want to create for the charity
- individuals support by pledging projects that align with their charities

For example:
Rosies (charity) posts the project "we need beanies and scarves". Creatives assign their profile to the project and receive funding from individuals so that the creative can starting making magic. 

Other examples could include:
Making a hat, clothing, bag, pottery item, painting etc for a charity in need e.g. artwork for a house at Ron McDonald homes, knitting a beanie for Rosies, taking photos for a make a wish event 

This is a concept that has not been implemented. I have only completed the basics of what was covered in the modules. 

### Front End Pages/Functionality- 
Projects    
- Ability to create a project
Pledges
- Ability to create a pledge
Users
- Ability to view profile
- Permissions 

### API Spec
| URL | HTTP Method | Purpose | Purpose | Request Body | Success Response Code |Authentication/Authorisation || GET | /projects/ | Returns all projects | N/a | 200 | N/a || POST | /projects/ | Create a new project | Object | 201 | Must be logged in || GET | /projects/1/ | Returns the project with ID of "1" | N/a | 200 | N/a || PUT | /projects/1/ | Updates the project with ID of "1" | Project object | 200 | Must be logged in, Must be the project owner || POST | /pledges/ | Create a new pledge | Pledge object | 201 | Must be logged in, Must not be the owner of the project || GET | /pledges/1/ | Get the pledge with ID of "1" | N/a | 200 | N/a || DELETE | /pledges/1/ | Deletes the pledge with ID of "1" | N/a | 200 | Must be logged in, Must be the pledge owner |


### Additional information/ DB Schema

Deployed project: https://dawn-hill-9103.fly.dev/


A screenshot of Insomnia, demonstrating a successful GET method for any endpoint.
/Users/maddymengel/Documents/SheCodes/07 DRF/img/GET - project.png


A screenshot of Insomnia, demonstrating a successful POST method for anyendpoint.
/Users/maddymengel/Documents/SheCodes/07 DRF/img/POST - project.png


A screenshot of Insomnia, demonstrating a token being returned.
/Users/maddymengel/Documents/SheCodes/07 DRF/img/TOKEN.png 


Your refined API specification and Database Schema.
/Users/maddymengel/Documents/SheCodes/07 DRF/img/SCHEMAS.png