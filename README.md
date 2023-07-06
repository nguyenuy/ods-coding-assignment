# ODS Full Stack Coding Assignment

## ✈️ Assignment Description
A new flight reservation system is being commissioned and you are tasked with building this out. There will be multiple phases to this project, but you will be expected to deliver the first phase here. You are expected to build out the initial flight search feature. Users should be able to visit the application and view a list of flights based on search criteria. A data source is provided for you in the repo to put all of this together.

## Flight Search Feature

1. Allow the user to enter a station (`destination` or `origin`) to search flights. Display the results in a table.

2. Provide an auto-suggest feature for station. A user should be able to see flights based on station code or location name as they're typing out the search terms similar to how Google works.

   Example: A user wants to select flights to/from Jacksonville. The associated station code is JAX
   
       Case 1: User enters the keywords: Jack --> The user is presented with a list of suggestion(s)
       Case 2: User enters the keywords: Jackson --> The user is presented with a list of suggestion(s)
       Case 3: User enters the keywords: Jax --> The user is presented with a list of suggestion(s)
   
3. Provide two RESTful endpoints supporting the functionality listed in steps 1 and 2.

4. You can be creative with this as however you'd like

## Bonus Points (Not Required)
1. Unit tests are created for your code and test the main logic you've put together, e.g. auto-suggest returns BNA when Nashville is the search term.

## Datasource
A zipped CSV file of flights is available in /data/flights.csv. Each row in the CSV file represents a flight.

## Implementation

### Preferred Tech Stack
* Backend: Python, node.js, SpringBoot, or whatever you're comfortable with
* Angular or other frontend framework (React, vue.js, next.js, etc.)
* Docker (If you'd like to host it, try hosting it on Firebase or Netlify since there's a free tier with a small db setup)

However, you may use other tech if you are more comfortable with something else. You can use any additional technologies/frameworks/DBs/libraries you would like to.

### ✅ To submit your solution:
* Clone this repo and push to a personal github repo and submit the link
* Please update the README with how to run your app and your tech stack used and anything else that the reviewer may need to get started with your code. If you'd like to mention anything else about your code and logic, please note it here. We will be running your app locally to validate your work.
* Return your solution within 5 business days, unless other directions provided.
* Feel free to ask questions at any time. Questions are welcome!
* Have fun with it! Your application can be as simple or complex as possible.
