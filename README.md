# IBM-Watson

* Federated search enables you to add custom search providers to the global search box, just like the same way you search for accounts or leads in your org.
* When you set up federated search, it reads the OpenSearch configuration from the Heroku app.
* Based on the configuration, one or more external objects are created in your org.
* When a user executes a search, Salesforce connects to the Heroku app. That app then executes the query against Watson Discovery, transforms the returned data into XML, and sends it back to Salesforce.
