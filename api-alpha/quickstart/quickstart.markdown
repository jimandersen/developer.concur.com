---
title: Quick Start Guide
layout: reference
---

## Quick Start Guide
This Quick Start Guide is written for Concur Partners migrating to version 4 API's. If you are new to Concur API's, follow these steps to make your first API call and try some of our other APIs.

### Provision your developer sandbox.

1. Signup for a developer sandbox by completing the [Sandbox Creation Form](https://developer.concur.com/manage-apps/register.html). Once you submit the form to Concur, we will set up a sandbox company in which you can test your API's.
2. Concur automatically creates a partner application for you, and generates an Access Token for your user account. 
3. Concur will send you this information using two-factor secure email.
4. Copy the Consumer Key, Consumer Secret, and Access Token and keep them in a safe place. You will need them to make authenticated API requests to your sandbox.

-- There is a missing step here: how do I get from the email to the app page to complete the remainder of the steps --

4. Once you close the initial window, click **Get Started** to reach the Setup wizard. Complete the Introduction page and click **Next** or **Skip**. 
5. Select values for the fields on the Introduction page. If you click **Skip**, you can return and configure these pages at any time.
6. Click **Done** on the Reporting Configuration page.
7. Click **Get Started** and the My Concur page of your developer sandbox appears.
8. To add users, create a payment method on the Employee Reimbursements page. On the Invite Users page, click **Invite Now** to activate your company.


### Register your Partner application with Concur
The first action all developers need to take is to register a partner application with Concur. When you register an application, you receive the authorization keys that are necessary to make Web service calls.

1. Click the [App Registration & Management](https://developer.concur.com/manage-apps/partner-applications.html) to register and manage your parnet applications.
2. In the APIs section, check the **E-Receipts Provider** checkbox. If you do not have permissions to the check the **E-Receipts Provider** checkbox, email [name@concur.com](mail to: name@concur.com).

### Obtaining your client ID and client secret

1. Email [name@concur.com](mail to: name@concur.com) with your Company Domain to get your client ID and client secret for the new Authentication API.

### Obtaining access to version 4 Receipts API in your developer sandbox

1. Email [pdspe@concur.com](mail to: pdspe@concur.com)with your Company Domain to enable the new Receipts API in your sandbox.


Create or import users in your sandbox. ( is this covered in Step 8 in the provision your sandbox above?)

6. Refer to the Authentication API documentation to get a valid token for creating a receipt for a user in your sandbox. (Do you want a simple link to the Generate Access Token information [here](https://developer.concur.com/api-reference/index.html#generate-access-token)?)

### Creating a receipt ###
1. Refer to the Receipts API documentation to know how to create a receipt.(Is this the v4 Reciepts content?)
2. Once a receipt is successfully posted, the receipt data and image can be viewed in the Available Expenses section of the website. (Can you provide me with a screen shot of what this looks like. How does a user navigate to this page view?)




