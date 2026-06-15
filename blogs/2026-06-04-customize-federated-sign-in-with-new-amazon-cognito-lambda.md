---
title: "Customize Federated Sign-In with New Amazon Cognito Lambda Trigger"
url: "https://aws.amazon.com/blogs/security/customize-federated-sign-in-with-new-amazon-cognito-lambda-trigger/"
date: "2026-06-04"
author: "Abrom Douglas"
feed_url: "https://aws.amazon.com/blogs/security/feed/"
---
Amazon Cognito now offers an inbound federation Lambda trigger that intercepts federated authentication responses immediately after an external identity provider responds, allowing developers to transform and enrich user attributes before profile creation. The trigger addresses common challenges such as oversized group attributes from enterprise SAML providers that exceed size limits, and enables automatic account linking for B2C applications where customers attempt sign-in through multiple authentication methods. This reduces duplicate user records and fragmented customer experiences in applications integrating with enterprise or consumer identity providers.
