# Documentation: Setting Up Login with Amazon Application for Amazon Ads API

## Step 1: Create a Login with Amazon (LwA) Application

### Onboarding Overview

The onboarding process for the Amazon Ads API involves:

1. Creating an LwA client application.
2. Applying for API access.
3. Assigning access.

The first step in this process is to create an LwA client application, which will be utilized to make requests to the API. After API access approval, this application will be associated with your access.

For more information, refer to:

- [Amazon Ads API Authorization Overview](#)
- [Login with Amazon (LwA) Concepts](#)

---

### Already Have Login with Amazon Credentials?

Even if you already use Login with Amazon credentials (e.g., Selling Partner API), you must create a new LwA security profile for the Amazon Ads API. If you are already logged into Amazon Developer, proceed directly to [Create a New LwA Security Profile](#create-a-new-lwa-security-profile).

---

## Register with Amazon Developer

To create a Login with Amazon application:

1. **Sign in or register on the Amazon Developer website**:

   - Go to [developer.amazon.com](https://developer.amazon.com).
   - Either:
     - Enter your email and password to sign in with an existing Amazon account, **or**
     - Select **Create your Amazon Developer account** to register a new account.

2. **Complete the registration form**:

   - Fill in the required details.
   - Accept the **Amazon Developer Services Agreement**.
   - Click **Submit**.

   **Important Notes:**

   - If creating an application for a business, use a team-managed email address.
   - This email will be associated with Amazon Ads API permissions and cannot be changed later.

---

## Create a New LwA Security Profile

1. **Log in to the Amazon Developer Console**:

   - Use your registered account credentials.

2. **Navigate to the Login with Amazon section**:

   - Click **Developer Console**.
   - From the menu bar, select **Login with Amazon**.

3. **Create a New Security Profile**:

   - Click **Create a New Security Profile** to access the Security Profile Management page.
   - Enter the following details:

     - **Security Profile Name**
     - **Security Profile Description**
     - **Consent Privacy Notice URL** (your company’s privacy policy URL).

     > Note: For Direct Advertisers managing their own data, this URL can be generic and is not essential for onboarding.

   - Click **Save**.

---

## Retrieve Your Security Credentials

1. **Access your security profile**:

   - After creating the profile, you’ll be redirected to the **Login with Amazon** page.
   - Locate your security profile in the list.

2. **Retrieve OAuth2 credentials**:

   - Click **Show Client ID and Client Secret** next to the profile you created.
   - **Save these values**:
     - The **Client ID** is required for all API requests.
     - The **Client Secret** is used to generate access tokens for the API.

   > Note: These credentials are accessible at any time from the Login with Amazon console.

---

## Frequently Asked Questions

### Can I use more than one client ID with the API?

No. Amazon Ads API allows only **one client ID per company**. Multiple users within a company can use the same client ID, with user permissions managed via the Amazon Developer console. However, the account creator must complete the onboarding.

---

## Next Steps

Once you’ve created the LwA application:

- Proceed to **Apply for Advertising API Access**.

---

## Technical Support

For assistance with the Amazon Ads API, visit the [Technical Support page](#).

---

This documentation ensures smooth onboarding for integrating Login with Amazon credentials and accessing the Amazon Ads API. For further guidance, consult the provided Amazon links or contact Amazon Developer Support.

## Step 2: Apply for Amazon Ads API Access

### Onboarding Overview

After creating an Amazon Developer account and a Login with Amazon (LwA) application in Step 1, the next step is to apply for access to the Amazon Ads API. The process differs depending on your company’s intended API use:

1. **Partner**: Businesses providing software solutions to help others optimize advertising. Access the API as a third party.
2. **Direct Advertiser**: Advertisers using the API to manage their own advertising activities.

## Applying for API Access

### **For Partners**

Partners must apply for API access via the **Amazon Ads Partner Network**. This network allows agencies and tool providers to manage relationships with Amazon Ads.

#### Registration Process:

1. **Register for the Amazon Ads Partner Network**:

   - Use an email address that is accessible to the appropriate team members (this may differ from the email used in Step 1).
   - Follow the [Amazon Ads Partner Network Registration link](#).

2. **Log in to the Partner Network Console**:

   - Navigate to the **Advertising API** section from the left-hand menu.
   - Click **Manage Advertising API Access**.

3. **Submit the API Access Request**:
   - On the **Advertising API** tab, select **Request API Access**.
   - Fill out the application form and click **Submit for review**.

> **Important Notes**:
>
> - Registration for API access is just one part of the Partner Network.
> - API access can only be assigned to an LwA client in a later step once approved.

---

### **For Direct Advertisers**

Direct advertisers may directly access the API application form.

#### Application Process:

1. **Go to the Application Form**:

   - Use the [Direct Advertiser API Access form](#).
   - Alternatively, navigate to the Amazon Ads API web page and select **Request API Access**, then choose **Direct Advertiser**.

2. **Sign in with the Correct Email**:

   - Use the email address associated with your Amazon Developer account from Step 1.
   - Ensure the correct profile is displayed in the top right corner of the screen. If not, log out and log in with the appropriate account.

3. **Complete and Submit the Form**:
   - Fill out the required details.
   - Click **Submit for review**.

---

## Next Steps

1. **Confirmation Email**:

   - You will receive a confirmation email at the address used to log in.
   - Application reviews typically take up to **1 business day**.

2. **Application Status Notification**:
   - If approved, follow the instructions to assign API access to your LwA application.
   - If not approved, the email will include details to resolve any issues.

> **Important**: Before acting on the status email, review [Assign API Access to Your LwA Application](#). The LwA developer registration will be permanently linked to your Amazon Ads API permissions.

---

### Additional Steps for Data Provider API

If setting up an account for the **data provider API**, additional steps are required. Refer to specific documentation for details.

---

## Technical Support

For issues with the Amazon Ads API, visit the [Technical Support page](#).

This documentation outlines the steps for applying for API access, ensuring a seamless progression to onboarding completion.

## Step 3: Assign API Access to a Login with Amazon (LwA) Application

### Onboarding Overview

After approval of your Amazon Ads API access request, the final step is to assign the API access to the LwA application you created in Step 1. This allows your application to request permissions and access data through the Amazon Ads API.

---

## Assigning API Access

### Step 1: Follow the Approval Email Link

1. **Locate the Approval Email**:

   - Upon approval, you will receive an email from Amazon Ads with a link to assign API access.

2. **Log Out of Other Amazon Accounts**:

   - Before clicking the link, ensure you log out of all Amazon accounts except the one used to apply for API access in Step 2.
   - **Important**: Clicking the link while logged into the wrong account will invalidate it. A reset by Amazon API support will then be required.

3. **Click the Link**:
   - Open the link from the email to access the assignment page.

---

### Step 2: Select Your LwA Application

1. **Confirm Completion of Step 1**:

   - On the web page, you'll see a reminder to create an LwA client application as described in Step 1.
   - If completed, click **Continue**.

2. **Choose Your LwA Application**:

   - A list of LwA applications associated with your account will appear.
   - Select the LwA application you created in Step 1 and click **Submit**.

3. **View Confirmation**:
   - After submission, a confirmation page will display:
     - The **Client ID** of your LwA application.
     - The scopes your application can use, including:
       - `advertising::campaign_management`: Required for most Amazon Ads API requests.
       - `advertising::test:create_account`: Required for creating test accounts.
       - **If applicable**: `advertising::audiences` (for data provider API access).

---

## Additional Steps for Amazon Ads Partner Network Members

If you are a member of the **Amazon Ads Partner Network (AAPN)**:

1. **Return to the AAPN Console**:
   - Go to the **Advertising API** panel in the AAPN console.
2. **Link Your LwA Application**:
   - Click **Link LwA Application**.
   - Enter the details of the LwA application created in Step 1.

Linking your LwA app to the AAPN helps streamline API access management for your teams.

---

## Next Steps

Your LwA client application for the Amazon Ads API is now established. This means:

1. **Authorization**:
   - Any Amazon user account can authorize your LwA application to access their advertising data and services through the API.
2. **Managing Credentials**:
   - Use this LwA application to create and manage authorization credentials. These credentials must be included in the headers of all API requests.

To begin working with the API, refer to the [Getting Started Guide](#).

---

## Documentation: Additional Setup Steps for the Data Provider API

This document outlines the extra steps required to onboard your application for the **Data Provider API** and set up optional billing reports.

---

## Prerequisites

Before starting, ensure you’ve completed:

1. **General API Onboarding**: Finish all setup steps required for all Amazon Ads APIs.
2. **Jira Account Creation**: Follow the email invitation to set up your Jira account for technical support. This is essential for managing your Data Provider API access.

---

## Step 1: Submit an Onboarding Request in Jira

To access the Data Provider API:

1. Log in to your Jira account.
2. Submit a support ticket stating that you need access to the Data Provider API.
3. **Symptom Path**: Select `/dp Data Provider` in the ticket form.
4. Wait for a response from the Amazon support team via Jira.

---

## Step 2: Optional Billing Report Setup

Amazon Ads provides **monthly audience usage billing reports** for data providers. These reports are delivered to an **Amazon S3 bucket**, where authorized AWS users or roles can access them. Follow these steps to set up billing report access:

### Prerequisites for Billing Setup

1. **AWS Account**: You must have an AWS account. If you don’t, [create one here](https://aws.amazon.com/).
2. **Understand AWS IAM**:
   - Read the [What is IAM?](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html) guide.
   - Decide whether to use **IAM users**, **roles**, or both to manage access.
3. **Create IAM Roles or Users**:
   - After deciding, create the necessary IAM resources.
   - Make note of the **IAM Amazon Resource Name (ARN)** for these resources (e.g., `arn:aws:iam::123456789012:role/ExampleRole`).

---

### Billing Report Setup Steps

1. **Submit a Jira Ticket**:

   - Title: `[Access Request - Billing] Request Access to Billing Reports`
   - Body:

     ```plaintext
     I have set up as a Developer User of the Data Provider API (link: https://advertising.amazon.com/API/docs/en-us/guides/onboarding/data-provider-api). I am requesting access to my Billing Reports.

     Please grant access to my Billing Reports to these authorized AWS IAM Roles/Users, identified by ARN:

     << paste IAM role/user ARNs here >>
     ```

2. Wait for the Jira ticket to be processed.
3. **Receive Confirmation**:
   - You’ll get an email with instructions for accessing your billing reports.

> **Note**: Billing reports are typically available on the **11th day of each month**.

---

## Next Steps

- Once your onboarding is complete, you can start making API calls.
- Begin by learning how to create **API authorization tokens**, which are required for all requests.

---

## Explanation in Simple Words

1. **Prerequisites**:

   - Finish setting up your account for Amazon Ads APIs.
   - Create a Jira account using the invitation from Amazon Ads. Jira is a tool for asking for help and managing requests.

2. **Ask for Access**:

   - Use Jira to ask Amazon for permission to use the Data Provider API.
   - Pick the option `/dp Data Provider` in the form.

3. **Optional Billing Reports**:

   - Amazon gives you billing reports about how much your audience data is used.
   - These reports are stored in Amazon S3 and need AWS permissions to access.

4. **Steps for Billing Reports**:

   - Make sure you have an AWS account and create IAM users or roles.
   - Note the special ID (ARN) for your IAM resources.
   - Send a Jira ticket to Amazon with the ARNs asking for billing access.
   - Amazon will give you instructions to access the reports.

5. **Next**:
   - Once you’re onboarded, you can use the API.
   - Start by learning how to create the tokens needed for API calls.

If you face problems, use Jira for help!
