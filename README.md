# Marketo Integration Template
This module contains examples on how best to integrate with Marketo and pull the lead and activity information.

## Module structure


### Setup
Follow the instructions from the Marketo help pages to find your Marketo application instance url: http://developers.marketo.com/rest-api/base-url/ and setup your Client Id and Client secret following the information on this page:  http://developers.marketo.com/rest-api/authentication/
Once you have this information you can change the configuration of your constants to allow your application to authenticate. 

You can test your client secret and Id by opening your authorization url in the browser.
https://123-ABC-456.mktorest.com/identity/oauth/token?grant_type=client_credentials&client_id=[yourClientId]&client_secret=[YourSecret]
If you are using valid credentials you'll see a JSON text, otherwise it will show the text: "Bad client credentialsinvalid_client" this indicates your credentials aren't valid for the Marketo url (either you have the wrong Marketo server or the wrong secret/id)


The "_example" folder contains 3 scenarios that are functioning if you'd create the corresponding entities in your model, or when using the full project file. 

### Find Lead

### Find Activity

### Bulk Import
