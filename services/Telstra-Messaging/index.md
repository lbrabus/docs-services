---

copyright:

  years:  2018

lastupdated: "2018-10-25"

---


{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}
{:pre: .pre}

# About Telstra Messaging API
{: #gettingstarted}

Send and receive SMS and MMS messages globally using Telstra's enterprise grade Messaging API. It also allows your application to track the delivery status of both sent and received messages. Get your dedicated Australian number, and start sending and receiving messages today. Receive 1,000 free messages by registering for Telstra Messaging API.

{:shortdesc}

## Getting started

Below are the steps to get started with the Telstra Messaging API.

1. Register at [https://dev.telstra.com](https://dev.telstra.com/telstra_ui/nojs/register?DistributorID=IBMCLOUD).
2. After registration, login to [https://dev.telstra.com](https://dev.telstra.com) and navigate to the **My apps and keys** page.
3. Find your keys under the free trial app, called **Free Trial APIs**
4. There is a maximum of 1000 free messages per developer. Additional messages and features can be purchased from [https://dev.telstra.com](https://dev.telstra.com/pricing-plan).
5. Note your `Client key` and `Client secret` as these will be needed to provision a number for your application and for authentication.

Below are the steps to get started with the Telstra Messaging API.

1. Generate an OAuth2 token using your `Client key` and `Client secret`.
2. Use the Provisioning call to create a subscription and receive a dedicated number.
3. Send a message to a specific mobile number.

### Run in Postman
Download the Telstra Messaging API Postman collection to get started rapidly with the Messaging API

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/ded00578f69a9deba256#?env%5BMessaging%20API%20Environments%5D=W3siZW5hYmxlZCI6dHJ1ZSwia2V5IjoiY2xpZW50X2lkIiwidmFsdWUiOiIiLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoiY2xpZW50X3NlY3JldCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6ImFjY2Vzc190b2tlbiIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6Imhvc3QiLCJ2YWx1ZSI6InRhcGkudGVsc3RyYS5jb20iLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoiQXV0aG9yaXphdGlvbiIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifSx7ImVuYWJsZWQiOnRydWUsImtleSI6Im9hdXRoX2hvc3QiLCJ2YWx1ZSI6InNhcGkudGVsc3RyYS5jb20iLCJ0eXBlIjoidGV4dCJ9LHsiZW5hYmxlZCI6dHJ1ZSwia2V5IjoibWVzc2FnZV9pZCIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifV0=)

### Sample Apps
- [Perl Sample App](https://github.com/telstra/MessagingAPI-perl-sample-app)
- [Happy Chat App](https://github.com/telstra/messaging-sample-code-happy-chat)
- [PHP Sample App](https://github.com/developersteve/telstra-messaging-php)

### SDK Repos
- [Messaging API - PHP SDK](https://github.com/telstra/MessagingAPI-SDK-php)
- [Messaging API - Python SDK](https://github.com/telstra/MessagingAPI-SDK-python)
- [Messaging API - Ruby SDK](https://github.com/telstra/MessagingAPI-SDK-ruby)
- [Messaging API - NodeJS SDK](https://github.com/telstra/MessagingAPI-SDK-node)
- [Messaging API - .Net2 SDK](https://github.com/telstra/MessagingAPI-SDK-dotnet)
- [Messaging API - Java SDK](https://github.com/telstra/MessagingAPI-SDK-Java)

