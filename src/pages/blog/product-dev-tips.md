---
layout: ../../layouts/BlogLayout.astro
title: Tips for Starting Product Development
description: Practical advice for launching a successful product, focusing on technical strategy and long-term scalability.
tags: ["product development", "software architecture", "best practices"]
time: 5
featured: false
timestamp: 2024-01-23T00:00:00+00:00
filename: product-dev-tips
---

Throughout my professional life, I have worked extensively with various technical products. In the past eight years, I have been fortunate enough to develop a diverse range of solutions and, for the last four years, I have had the opportunity to create two different product apps from scratch. These experiences extended over time, have contributed significantly to my growth as a developer.

While many of us may believe that building a product isn’t necessarily difficult — just follow a methodology and stick to it — the reality, as time has taught me, is far from that simple. Following a methodology is a good starting point, but what happens when the product scope keeps expanding? Or when your team lacks sufficient technical experience?

There are numerous challenges that can arise for an IT team throughout the lifespan of a product. Some are easier to address than others. What is certain is that working on a product is a complex undertaking, requiring a scalable work methodology and an agile, communicative team.

![Product Development Illustration](/posts/product.webp)

Having reflected on my experiences, I believe it’s time to share some insights. In this post, I want to focus on tips that I would have appreciated years ago, before starting product development.

## 1. Know Your Framework Well

It might sound obvious, but one thing that developers cannot take for granted is the technical stack they are working on. If you are leading or developing a new product the first thing you should have in mind, is ensuring that you have senior developers familiar with the technologies you will be working with. This might seem like a logical requirement, but it’s not always met as often as you might think.

If your team lacks the desired seniority, and you still have to continue developing on a stack that no one has experience with, it is critical to conduct an analysis of the advantages and disadvantages of the architecture you will develope. Analyzing the technologies, planning application scalability, and ensuring effective communication between dependencies can help identify crucial errors early on, preventing technical debt that could be challenging to address in the future.

## 2. Limit External Dependencies

Nowadays, with decoupled technologies, integrating external dependencies into projects is incredibly simple. For instance, when working with frontend libraries such as Vue.js or React, if you need to develop a popup for your app, you don’t have to build it from scatch. You can install a [library](https://tailwindcss.com/plus/ui-blocks/application-ui/overlays/modal-dialogs) in 2 minutes with a pre-built component.

Nevertheless, external libraries can require a lot of maintenance in product-focused development. If you are not selective or consistent with the number of libraries you install in your applications, you can end up working with a large volume of dependencies. Consequently, these libraries would have to be maintained throughout the life of the product. If by any chance you work with a framework that requires versioning, one day, you may find that the library that brings to your product a fundamental value is no longer maintained. This should never happen!

To avoid such issues, it’s crucial to be selective in installing libraries and review their evolution before integration. Understanding the nature of a solution and predicting how the library might evolve over the life of your framework or programming language can make a significant difference.

## 3. Modularize Your Application

One technical aspect that sometimes is overlooked is the modularization of products. As I mentioned in the first tip, <b>it is really important to plan and analyze the scalability of our product before starting development.</b>

Each framework and product are completely different. If for some reason, you have problems planning the evolution of your product, or you doubt when you should develop a separate module or library, I strongly recommend defining a plan, which through different general and specific objectives, will allow you to identify when and how to modularize your product app.

This guide can be designed by the team’s software architect or previously agreed upon by all the team’s developers, the system does not matter, the important thing is that your team draws clear lines that are easy to follow as the product evolves.

## 4. Plan How To Implement Internationalization/Globalization

Depending on your app product’s nature, one fundamental aspect to design is internationalization. The development of internationalization is a topic that warrants a dedicated article, as it heavily depends on the technologies and tools provided by the languages or frameworks in your ecosystem.

Typically, in most modern web architectures, the scalability of internationalization tools are limited, and for this reason these tools can be critically dependent on the overall scalability of the architecture. It is an aspect that should not be overlooked and can have a major impact on the future of your product. A good approach to address this issue is to concurrently address an internationalization planning compatible with your architecture growth plan, whether or not your applications require internationalization.

## 5. Consider Implementing a Testing Plan From Day One


In line with the previous point, a fundamental aspect of your product, especially if you expect its architecture and complexity to grow, is implementing a scalable testing plan from day one.

QA best practices are clear on this: each test should be developed before incrementally adding functionality to an application. As developers, we tend to ignore testing until is too late.

I would like to emphasize a personal point of mine: “As developers, the suffering we experience when implementing a robust testing system is proportional to the time taken to implement it.”

## 6. Automate Documentation

There is no better code than that which is self-explanatory, but in certain occasions, especially in large-scale applications, it is convenient to document some foundations of our application.

In 2024, you have access to a wide variety of free tools that allow us to automate documentation of componentes and modules. For instance, a library I recently discovered and like to include in all my Angular or React projects is [Compodoc](https://www.npmjs.com/package/@compodoc/compodoc).

As with other cases, you should evaluate available tools in the market for each programming language. Automating documentation not only benefits developers and teams but also contributes to a product mentality, making it less likely for documentation tasks to be neglected.


## 7. Follow an Agile Work System

Last but not least, in my personal opinion, a fundamental aspect to take care of in a product is the agile methodology.

You can use the methodology that best suits your team: scrum, kanban, extreme programming… As I mentioned before, the important thing is to mark some lines that, in this case, let you generate spaces for retrospective, planning or continuous improvement. All these spaces are essential not only to improve your work compared to the previous day, but also to force you to stop for a few minutes and evaluate if you are personally and professionally satisfied with the path your team is following.

## Final Thoughts

In conclusion, establishing a product mentality can be challenging, especially at the beginning if you are accustomed to working on temporary projects.

In my personal opinion, developing a product is a job that demands effort and perseverance, resembling a long-distance race. Every step counts, and the journey is long. Similar to an athlete establishing systems that benefit every kilometer, as developers, we have the opportunity to establish our own framework, making our daily work a bit easier.