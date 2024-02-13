# postman-reflection
## Pokemon API - Data retrieval and understanding
- Send Get request for the desired character to receive its data. Analyize and understand the data returned,
  eg. Number of values returend, data type, Arrays and Object and any URL's etc
- Chracter Name: charmeleon  
- URL: https://pokeapi.co/api/v2/pokemon-form/5/
- Data retrieved: Type; String, Array, Number, boolean  
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/23e3efac-38f6-4257-81bc-9a5229f06c1e">
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/78cb30f2-244c-4c1f-b6c1-31ba1af888de">


Chracter Name: Staryu

<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/d28bfab7-b4ad-492f-bc4d-9180763401ed">
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/7969cdc9-db14-4ca5-bd19-be38cb4e27a9">


Chracter Name: Kingler

<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/f22ebc0f-ad87-4437-a2d2-df6c97d81dd6">

<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/1cf13add-e4c5-406b-91de-23cd3c9e357f">



<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/4c8fcd19-7f1a-4591-985f-0aef92547fa8">



# Exploring a Weather API
## Objective
Gain hands-on experience with the Weather API by sending requests using Postman. Understand the significance of query parameters in API requests and document the process and findings.



<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/080cc1d4-708b-40db-a769-1f953b8ceb8c">

<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/ddd1b839-5d74-423c-a8e7-dc10da77e3b9">



# API Collections
## Objective
Create a collection in Postman specifically for the weather API, and utilize a variable to manage the API key. Send a request to the weather API and document the entire process and the response received.

### Steps:
- In Postman, create a new collection named "Weather API Collection"
- Set up a new environment in Postman, named "Weather API Environment".
- Added new variable for the API key, with the name 'weatherApiKey'.
- Assigned my weather API key to this variable.
- Created new Get request "GetWeatherReport" in "Weather API Collection".
- Passed the 'weatherApiKey' variable instead of actual API key in Get request.
- Chose an endpoint and set location parameter to retrieve its data.

- <img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/7e3f3467-5351-4679-af09-2d3e459c23eb">
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/71bbb9f0-f39b-4e7b-abac-4d60caa74174">


# Interacting with GitHub's API
## Objective
Utilize Postman to interact with GitHub's API by retrieving user information and creating a new repository. Document the entire process, including the request setup and the response in your README.md file, accompanied by appropriate screenshots.

<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/ceb11a80-6201-4047-8ec0-c7adb8378fee">

<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/2f6a1e44-94d7-407f-a7f4-123928303ef0">

Learning Curve: sent Post Request to Create a new GitHub Repo with "private": "False" as string while it had to be a boolean, as a result a private Repo was created.
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/c161cf72-4620-41f9-a9ac-9a5eeba67f69">

Fixed data tpye to boolean to succesfully create a Public Repo.
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/89beb8f2-c83a-492b-bf88-7cd6f12e5180">

Repo Successfully Created:
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/a7289612-4000-4917-be50-ae6f1569d953">

GitHub Repo Page:
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/274fc242-5e99-445a-b644-5710173e8792">

# Thunder Client
## Objective
The objective of this assignment is to replicate the tasks completed on Day 4, but this time using Thunder Client in VS Code. This will provide hands-on experience with an alternative API testing tool and offer insights into the differences and similarities between Thunder Client and Postman.

- I found Thunder Client bit easier to use being integrated in VS Code, basic functions are same to create a variable and to send a GEt or POST request.  
- Although the secret option to hide the Keys is used but still with Mouse Hover, hidden keys still display which is not very secure. 
### Get Request:
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/fc52144d-aeef-49e0-95cb-e5b1e35d6a8b">
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/a4d5dcb1-7a58-4b01-9b7c-60a174873e65">

Post request: Create a New GitHub repo with POST
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/7397872e-2a2e-451d-8be4-9f2b67ccfd3d">

GitHUb Screenshot of new Repo:
<img width="960" alt="image" src="https://github.com/uxeeCoder/postman-reflection/assets/148591312/ffc056f7-f376-42c9-b4fa-c78faff8c1d0">

























 
