---
layout: ../../layouts/BlogLayout.astro
title: 3 Key Concepts to Understand Angular Signals
description: Understanding Angular signals is crucial for managing reactivity in modern Angular applications. This guide covers the essential concepts.
tags: ["angular", "signals", "reactivity"]
time: 5
featured: true
timestamp: 2024-12-18T02:39:03+00:00
filename: angular-signals
---

Angular Signals stand out as a noteworthy feature introduced in Angular 16. Despite their existence for almost a year, in my personal opinion, there is a scarcity of comprehensive documentation on this subject. In an effort to contribute to the community, this article delves into the fundamental aspects of Angular Signals and highlights their potential significance in the development of new applications.


## 1. Signals Core Concept

According to the official website: “A signal is a wrapper around a value that can notify interested consumers when that value changes. Signals can contain any value, from simple primitives to complex data structures.”

This definition may appear somewhat vague initially, particularly for those who are relatively new to the framework. To provide more context, signals essentially serve as lightweight wrappers around values. They enable us to receive notifications when the signal value changes, allowing us to take corresponding actions. This level of reactivity is not achievable with plain values, as updating them would require manual variable adjustments, leading to the loss of previous values over time.

Unlike observables, signals always have a value. The main distinction lies in the fact that signals do not emit information, and their values are obtained synchronously. In contrast, observables emit values either synchronously or asynchronously.

## 2. Angular Signals and NgRx Partnership

When Angular Signals were initially introduced a year ago, there was speculation in the community about whether this new functionality would replace the NgRx library. Currently, it is evident that Angular Signals and NgRx serve distinct purposes.

NgRx is a state management library, while signals aim to refine and enhance reactivity within an application. Interestingly, the NgRx team has already implemented a solution for working seamlessly with signals, showcasing their complementary nature.

## 3. Regarding Change Detection…

Quoting Google’s official documentation: “When an OnPush component uses a signal’s value in its template, Angular will track the signal as a dependency of that component. When that signal is updated, Angular automatically marks the component to ensure it gets updated the next time change detection runs.”

This definition emphasizes that signals notify all consumers about their changes, leading to automatic updates in the view. This seemingly subtle feature, is far from revolutionizing the current change detection system, however, it marks the first strategic step of Google to get rid of the use of the painful zone.js library. For further information I recommend you this detailed article by @eugeniyoz.