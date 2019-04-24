# Getting Started
There are two steps to using Halla I/O's services.
1. Create a Google Cloud API key
2. Create a Service User

### Before create your Google Cloud API key
1. Create a new [Cloud Platform project](https://console.developers.google.com/projectcreate).
2. [Enable billing](https://cloud.google.com/billing/docs/how-to/modify-project#enable_billing_for_a_project) for your project.

### Creating an API key
1. [Create an API key](https://console.developers.google.com/apis/credentials) in the Google APIs Console.
2. Click **Create credentials**, then select **API key**.
3. Copy the key to the clipboard.
4. Click **Close**.

### Enable the API
Before you can make calls to this API, you need to enable it in the Cloud Platform project you created.
1. [View this API](https://console.developers.google.com/apis/api/{{apiHost}}/overview) in the Google APIs Console.
2. Click the **Enable** button, then wait for it to complete.
3. You can now call the API using the API key you created!

### Creating a Service User
1. Navagate to the **/serviceUsers** route.
2. Use your newly created **API key** and **Admin User key** to create a Service User. One **Admin User key** will be released upon completion of data ingestion, email henry@halla.io for access.

### Using the API
Browse the reference section of this site to see examples of what you can do with this API and how to use it. You can use the **Try this API** tool on the right side of an API method page to generate sample requests.
