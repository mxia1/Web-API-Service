# Web-API-Service

Endpoints functionalities 

    1. GET `/api/contacts`
    This will return a json object containing the information for all of 
the contacts in your contact collection.
    2. POST `/api/contacts`
    This will create an instance of a contact in your contacts 
collection with the data you provide that needs to match the schema you 
define.
    3. GET `/api/contacts/:email`
    This will return a json object containing the information for the 
contact in your collection that matches the email request parameter.
    3. PUT `/api/contacts/:email`
    This will update the contact entry in your contacts collection with 
the values you provide.
    4. DELETE
    `/api/contacts/:email`
    This will delete the contact resource inside of your contacts 
collection that has the email passed in as the parameter.
