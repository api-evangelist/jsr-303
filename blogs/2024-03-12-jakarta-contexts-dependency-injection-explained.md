---
title: Jakarta Contexts Dependency Injection Explained
url: https://jakarta.ee/learn/specification-guides/contexts-dependency-injection-explained/
date: '2024-03-12'
author: webdev@eclipse-foundation.org (Eclipse Foundation)
feed_url: https://jakarta.ee/index.xml
---
Jakarta Dependency Injection provides the ability to make use of contextual objects in an application with maximum reusability, testability, and maintainability. This specification provides a means for developers to easily obtain objects throughout classes within an application without the requirement to use constructors, factories, or service locators. Jakarta Contexts and Dependency Injection, Jakarta CDI for short, is one of the paramount specifications of the Jakarta EE Platform, as it contains a number of powerful complimentary services that are utilized across a majority of Jakarta EE applications. Jakarta CDI has been known as the “glue” for the Jakarta EE Platform because one of the most significant features is the enablement of contextual objects to be made available for use throughout other classes and views within an application. The specification makes use of the Jakarta Dependency Injection specification to provide this capability, but Jakarta CDI also provides a number of other features beyond dependency injection including scope assignment, generation of preconfigured objects, qualification, initiating code when events occur, to mention a few.
