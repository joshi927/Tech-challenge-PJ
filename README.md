Demo Application for Cruise0

This app was designed to meet the instructions based out of the technical challenge

Show how Auth0 can support the Cruise0 app modernization on ReactJS (you are free to build the PoC single page application in your preferred language for demonstration purposes).
✅ The Quickstart templates for Auth0 are available in the main admin screen. I built this one off the Vanilla JS template, and later on changed to client side implementation and used the Github link in the document.
https://auth0.com/docs/manage-users/user-accounts/user-account-linking/user-initiated-account-linking-client-side-implementation

Show how a new customer can sign up, and how an existing customer can sign in with email/password, and Google.
✅ This app uses of Auth0's Social Identity Providers feature, using Auth0's default credentials for Google apps, set up via the Auth0 Dashboard. Account linking feature has been enabled to address duplicate accounts.

Ensure that customers who login with username/password and Google, with the same email address, will be treated as the same user. 
✅ This app implements Account Linking via client side implementation and address Account linking feature for duplicate accounts.
The application should display an error if the customer’s email address is not verified.
✅ The customer email address verification status is fetched using /api/V2/users. 

Use the New Universal Login for the Authentication Experience and customize it with a Cruise Ship logo, title of “Welcome Aboard”, and description of “Log in to book your travel with Cruise0”.

✅ The customised login page includes the title “Welcome Aboard” and a description of “Log in to book your travel with Cruise0”. 

The New Universal Login prompt should also feature a background of a Cruise Ship to meet the Marketing Teams objectives.
✅ The Marketing Teams objectives have been met with background and logo changes. 

