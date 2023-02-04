This integration takes a set of Contacts objects from a Mock REST API and inserts them into Salesforce. This project can be repurposed for any data type beyond just Contacts. This project supports Upsert functionality, but be sure to clear Salesforce of any Contacts that match what is incoming from the REST API before moving the data if you'd like new Contacts to appear.

This project requires creating a mock API to pass the data from. This is the site I use to create mock API endpoints: https://mockapi.io/projects
