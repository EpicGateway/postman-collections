# EpicPay Gateway API - Postman Collections
A repository of Postman collections for the EpicPay Gateway API.

### Get Started

1. Import the Postman collections into Postman.

2. Update your Postman Environment to include these variables:

| Environment Variable | Value |
| ------------- | ------------- |
| APIKeyID  | {The Key ID for your Sandbox API Key}  |
| Password  | {The Password for your Sandbox API Key}  |
| IP  | {Your public IP address}  |
| FutureYear  | {Any year in the future, not to exceed 2100 (4-digit)}  |
| BaseURL  | https://sandbox-api.epicpay.com/payment/v1  |
| BaseURL_Reports  | https://sandbox-api.epicpay.com/reporting/v1  |

### Usage

Some requests depend on data returned from another request and will fail until the other request is run successfully.  Use the map below to determine which requests depend on results from other requests.  Also see the "Tests" section of each Postman request to see what data will be stored when the response for that request is received.

![API Map](https://epicpay-public.s3.amazonaws.com/shared/images/devdocs/APIMap.png)
