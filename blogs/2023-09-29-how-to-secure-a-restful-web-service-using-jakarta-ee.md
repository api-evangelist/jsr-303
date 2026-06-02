---
title: How to Secure a RESTful Web Service Using Jakarta EE
url: https://jakarta.ee/learn/starter-guides/how-to-secure-a-restful-web-service/
date: '2023-09-29'
author: webdev@eclipse-foundation.org (Eclipse Foundation)
feed_url: https://jakarta.ee/index.xml
---
This guide shows you how to secure a rest endpoint using Jakarta Authentication . As we delve into securing RESTful web services, let’s first define a basic scenario that we will be working with throughout this article. We are constructing a service that will accept an HTTP GET request at http://localhost:8080/jakartaee-hello-world/rest/hello . In response to this request, our service will return a JSON payload, as shown in the following example:
