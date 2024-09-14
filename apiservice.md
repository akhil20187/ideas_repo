# API as a Service Marketplace.

Idea: Have multiple micro applications based on Python, that anyone can use to build any application using the APIs. 
It's a pay-as-you-go model with no fixed subscription charges.
The APIs will be provided to other clients for a fee like $10 for 1000 Credits and for every API, the number of credits consumed might be mentioned that will be consumed against the credits available. In case of no credits available then the user cannot use the API. 
We will only provide the API and not store any data.
The details of the API will be provided along with the functionality, expected output and samples. However, these APIs will be customized.


I will be able to host multiple micro applications which will be for specific purposes like Image Generation, Story Generation, Swimlane Diagrams, Social Media Post Generator and many other. 
Each micro application should have a folder and have relevant files of the application in that folder only. 
All the applications will be built on Fast API. 


# Home Page
The home page will have a repository of all the Applications with their Names, Description
The user, if logged in, should be able to see the credits available on the top corner of the Navigation Bar

# Applications Detail Page
Every application will have a dedicated page, which describes the Application 
It will tell about the Input Schema and the Output Schema from the API.
The sample outputs from the API will be available for the user to check in the Dedicated Page
The page will also have API endpoint details with details about the INPUT parameters and OUTPUT Format of the API
It will have a description of each api endpoint in detail. 
The page will also have details about the amount consumed per API usage that will be deducted against the credits given.

# Genearate unique API Token
If any user has to use the API, they need to signup with social login. If they have an existing account, they can SignIn.
Once the user has logged in, on the My Accounts page the user can see the option to Generate API keys
Users can generate a unique API key, which will be secure. 
Users can see the list of all the generated API keys
A user can generate any number of API keys and the API key should be secured so no one can store it. 

# Credits
As a first-time user, the user will get given 100 Credits that can be used against any application.
To use the APIs after the 100 Credits are exhausted, they need to add credits to their Wallet
The user can add Credits by clicking on the Credits Section, where the user can see the credits available and the option to ADD CREDITS
Once the user clicks on ADD Credits, The user will be asked about the amount of Credits to Add like $10, $20, $30 or custom amount. Add Coupon Codes
The user will be taken to a Payment Gateway by Stripe to make the payment
Once the payment is done, the credits will be added to the application 
The user can see the credits in their Login 
The Credits will get deducted as the APIs are consumed.
We need to keep track of the credits consumed per APIs as a transaction record for the user to check on the their dashboard on the Transactions Section. 


