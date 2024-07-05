# 300 Creating Webhooks

Next, let's create the Webhooks in n8n. Create an empty workflow and click the **+** sign:

![Screenshot 2024-07-05 at 13 26 34](https://github.com/vanHeemstraSystems/noteplan-n8n/assets/1499433/68f0d37d-e84b-45c7-8d89-11f76284abd0)

1) Create five new Webhook nodes (pick **On webhook call**) and name them like so:
   - Add
   - List
   - Search
   - Delete
   - Change_Status
  
Enter the following settings for the **Add** Webhook:

![Screenshot 2024-07-05 at 13 37 00](https://github.com/vanHeemstraSystems/noteplan-n8n/assets/1499433/2d6ea43b-24d3-4614-bd3a-34836a1e78fd)

Enter the following settings for the **List** Webhook:

![Screenshot 2024-07-05 at 13 43 07](https://github.com/vanHeemstraSystems/noteplan-n8n/assets/1499433/a2662d9f-8fe0-4653-8496-d97da2c6828a)

Enter the following settings for the **Search** Webhook:

![Screenshot 2024-07-05 at 13 47 23](https://github.com/vanHeemstraSystems/noteplan-n8n/assets/1499433/150d8056-65db-4215-b988-6003de0172e7)

Enter the following settings for the **Delete** Webhook:

![Screenshot 2024-07-05 at 13 52 48](https://github.com/vanHeemstraSystems/noteplan-n8n/assets/1499433/4b4cfb4f-9a88-4281-b8df-f4b534890c5d)

Enter the following settings for the **Change_Status** Webhook:

![Screenshot 2024-07-05 at 13 58 28](https://github.com/vanHeemstraSystems/noteplan-n8n/assets/1499433/912c7807-ec0a-4f03-b554-d46fbde25a98)

That should complete the initial Webhook creation. Make sure to save and activate the workflow.

![Screenshot 2024-07-05 at 14 01 35](https://github.com/vanHeemstraSystems/noteplan-n8n/assets/1499433/c2f0634e-9c30-4316-9ff7-6a0d4e0b7252)

## The rest of the workflow
While the rest of the workflow is important for generating the proper outcomes for the API, it has very little to do with the API itself.

You can download the whole workflow here: https://github.com/PacktPublishing/Rapid-Product-Development-with-n8n/blob/main/Chapter%205/User_Management_API.json

Now that we have built the API in n8n, let's look at how to add further security to your API endpoints.
