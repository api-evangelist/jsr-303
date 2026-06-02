---
title: Jakarta Concurrency Explained
url: https://jakarta.ee/learn/specification-guides/concurrency-explained/
date: '2024-03-12'
author: webdev@eclipse-foundation.org (Eclipse Foundation)
feed_url: https://jakarta.ee/index.xml
---
Application performance can make or break a user’s experience. Applications that provide a consistent experience and perform well are more likely to benefit user productivity. The Jakarta Concurrency specification targets application performance and usability by providing a standard API for developing concurrent application processes without compromising container integrity. It is not recommended to utilize traditional Java SE threads or timers within a Jakarta EE container because use of threads or timers may cause reliability issues and unexpected results. Jakarta Concurrency provides an API that does not intrude on container integrity, but rather, uses services that are managed by the container and matches the functionality provided by the Java SE Concurrency Utilities.
