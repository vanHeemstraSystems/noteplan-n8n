# 100 API Project Specifications

For our project, we are going to build a simple activity management API that will modify the activity information in an Airtable database. Most of 
the workflow that we will be building isn't important to the API itself. All we have to be aware of is the result of each API.

Our API is going to have five endpoints:

-  POST /api/v1/activity/add
-  GET /api/v1/activity/list
-  GET /api/v1/activity/search
-  POST /api/v1/activity/delete
-  POST /api/v1/activity/change_status

The base URL for our API will be https://wvanheemstra.app.n8n.cloud/webhook since that is the Webhook URL for our n8n cloud instance.

Our API will also use header authentication with a bearer token value of xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx.

The Airtable database will store the following information:

- Activity Name: The activity's name
- Activity Status: The activity's status
