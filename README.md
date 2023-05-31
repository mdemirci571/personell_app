# personell_app
# Features requested by the customer

Personnel API
* We will have Deparment and Personnel tables and we will connect them to each other. Each department will have its own personnel under it.
* Staff members will be able to add new personnel to the list and update them.
* The response will change according to the dynamic url and the request coming in the url. In other words, when we want to list the personnel of the departments, we will do this through a single url. Swagger also has an example.
* Non-staff members will only be able to list.
* The authority to delete personnel will be only for superusers.
* We will use token authentication. We will delete the token when the user logs out.
