---
title: How to store and retrieve data using Jakarta Persistence of Jakarta EE
url: https://jakarta.ee/learn/starter-guides/how-to-store-and-retrieve-data-using-jakarta-persistence/
date: '2023-09-22'
author: webdev@eclipse-foundation.org (Eclipse Foundation)
feed_url: https://jakarta.ee/index.xml
---
This guide shows you how to store and retrieve data using Jakarta Persistence . We will first begin by summarizing what we want to build. Next, we build a RESTful web service that can consume data, store it in a database using Jakarta Persistence, and serve it as a REST endpoint. For those unfamiliar with RESTful web services, we recommend reading our previous article . We will build an application that handles coffee product data. The service will consume a JSON payload containing the product’s ID, name, and price. Here’s an example of the JSON payload:
