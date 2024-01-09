---
author: "Luke"
title: "Great Software Architecture v1.0"
date: "2024-01-07"
description: "How to build great software architecture"
tags: ["Salesforce","Architecture"]
ShowToc: false
ShowBreadCrumbs: false
Comments: true
---
The following article is an article intended to describe some of the key things to consider when designing software architecture.

It contains real anecdotes from my decade long career working with enterprise clients implementing Salesforce and combines this experience with the best of the Salesforce Well-Architected framework although I hope the principles described are equally applicable when implementing other software.

TLDR: Great software architecture is intentional, simple & flexible. Ensure you are working on the right thing, making sure your architecture is simple and easy to understand and flexible enough to handle the inevitable missed / new requirements.



——



Great software architecture is intentional, simple & flexible. 



—— 



Intentional



To design great architecture it is critical to understand the business problem you are trying to solve. 



Understanding the business problem you are trying to solve involves more than understanding the requirements. It’s more than understanding what a customer may tell you and it’s more than understanding the way things are currently done but is to understand the business problem your solution needs to solve. 



The aim of this phase is not to design architecture. It should happen in a technology independent way.



One approach of how to achieve this is to discover your “Jobs to be Done”.

https://trailhead.salesforce.com/content/learn/modules/jobs-to-be-done-framework-for-designers

Reflect on why you are implementing Salesforce, what business problems you are trying to solve or utilise a partner like Publicis Sapient with our experience led offering to help you.



When working with stakeholders, you should remain curious, inquisitive & ask good clean questions (https://en.wikipedia.org/wiki/Clean_language).

Assumptions are documented, the scope of the solution should be clear.



Once we have understood the business problem, we can be intentional with the design of our architecture.



The architecture you will design should solve the challenge you identified ,the requirements you are aware of, within the boundary conditions you have set.



Simple



If architecture is simple. It is easy to understand. 



As the business problem we are trying to solve is clear (see intentional), we are able to avoid ambiguity.

We are also able to avoid unnecessary abstractions that do not solve the problem at hand.



Each stakeholder, including non-technical ones, should have a clear understanding of the business terms and it should be possible to simply explain the data objects required. 

Ideally a single object data object should have a single business purpose. 



When speaking to stakeholders, explanations should be clear, concise and simple including when talking about automation. Non-Technical stakeholders do not for example care about whether something is implemented via click or code, but do care about the function and it’s result.

Developing this skill set is often overlooked in favour of technical expertise, but any one who’s passed the Certified Technical Architect exam will tell you it’s just as important, and anyone who’s worked with an inspiring architect will have seen that they are also a great communicator.


Good architecture also makes things as simple as possible for system users. User Experience is critical for adoption.

To keep things simple, try to break down a problem (e.g. Customer would like to buy a subscription) into smaller and smaller functions.

Using Universal Process Notation (UPN) is one approach here.

https://trailhead.salesforce.com/content/learn/modules/business-process-mapping/understand-universal-process-notation



Flexible



For architecture to be flexible it needs to handle change. New requirements are to be expected as things are often missed as part of the analysis or from new requirements that emerge from either users who use the system, or to support additional business models or processes.



If an architecture is flexible, new requirements should seldom mean extensive factoring to incorporate as the implementation should be capable of handling change.

This does not mean that the existing architecture is the best fit for the new requirements and an analysis should always take place.

It also does not mean that lots of time should be invested in layers of abstraction as this would violate the principle of simplicity.



One way of ensuring your architecture is flexible is to make it composable.



Salesforce Well Architected - https://architect.salesforce.com/well-architected/adaptable/composable states: “A system architected to be composable is built in meaningful units, or building blocks, that can operate gracefully with one another and can be easily swapped in and out of service.”



We discussed Universal Process Notation (UPN) already and UPN fits nicely together with capability maps.

Capability Maps, represent the business capabilities that the IT systems need to support. These capabilities can then be broken down into functions or features which can then be implemented, packaged and deployed.



Summary



Following these steps you’ll have hopefully discovered the business problem you are trying to solve, the “Job to be Done” & you’ll hopefully have identified & designed a simple, easy to understand and flexible architecture to solve it.

Of course… You still need to implement it.


And to implement your great architecture you’ll need a high performing team (LINK) to do so.


Call to action

If you are a business and found this article or series interesting and would like a review of your architecture from either myself or one of the other fantastic PS Architects, fill in the following form.

If you’re working in the Salesforce ecosystem, enjoyed reading the article and you’re interested in a free 1:1 coaching session to improve your own architecture, please feel free to reach out directly.

