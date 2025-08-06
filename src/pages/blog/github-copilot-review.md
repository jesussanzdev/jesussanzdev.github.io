---
layout: ../../layouts/BlogLayout.astro
title: My Thoughts After One Month Using GitHub Copilot
description: A firsthand account of integrating GitHub Copilot into daily development workflows, highlighting its benefits and considerations.
tags: ["github copilot", "AI tools", "developer experience"]
time: 5
featured: true
timestamp: 2024-12-19T00:00:00+00:00
filename: github-copilot-review
---

![GitHub Copilot Overview](/posts/copilot1.webp)

Launched in 2021, GitHub [Copilot](https://github.com/features/copilot) entered the tech scene with great promise but also significant controversy. Early criticisms centered on concerns about code quality, potential copyright violations, and its reliance on OpenAI’s language models. Skeptics questioned its utility, fearing it might generate insecure or inaccurate code, and the open-source community expressed reservations about how it leveraged public code repositories.

Now, three years later in 2024, GitHub Copilot has evolved significantly. The tool has undergone major updates, addressing early challenges and improving its functionality. But has the industry’s perception of Copilot shifted?

After following numerous tech influencers and reading countless tech blogs, it might seem like GitHub Copilot has turned the tables. However, I have to admit it, as an early skeptic, I wanted to form my own opinion. A month ago, I decided to take advantage of the free trial and spent the past few weeks using GitHub Copilot daily while working on my personal projects. Now, after a month of using the product, I have developed my own perspective.

So, is GitHub Copilot worth it in 2024? What features does it bring to the table and how can it enhance our daily productivity? Let’s dive into the details.

<i>NOTE: As I’m finishing this article, GitHub has released Copilot for free in order to train their IA models, so hopefully this piece of work will reach more people!</i>

## GitHub Copilot Features

### AI Models à la Carte

As you may know, GitHub Copilot is powered by OpenAI, and its main feature enables developers to highlight any fragment of code and ask the tool questions about its quality, potential code smells, bugs and more.

Nevertheless, what surprised me when I started the free trial, is that GitHub Copilot now allows developers to select the OpenAI model best suited to the task at hand. As of December of 2024 it offers four distinct options:

- **Claude 3.5 Sonnet**: Known for its creativity and natural language understanding, this model excels in generating documentation, code comments, and even refactoring code with a focus on readability. It’s particularly useful for developers trying to simplify complex code.

- **GPT 4o (default)**: GPT 4o balances power and precision. It provides high-quality code completions, bug detection and suggestions. It is the most versatile.

- **o1-mini**: Designed for lightweight tasks, this model is optimized for speed and efficiency.

- **o1-preview**: To be honest I have not proved this one myself, it still in development but it shows promise in tackling more complex scenarios such as interpreting ambiguous code or offering innovative solutions.

![GitHub Copilot Chat Interface](/posts/copilot2.webp)

### “The Chat”

GitHub Copilot’s Chat may be the most popular feature of 2024. This integrated chat allows developers to place it wherever they find it most convenient. Personally, I tend to keep it in a secondary window — at least until I get accustomed to incorporating it into my daily workflow.

So, what can I say about GitHub Copilot’s Chat? Using it feels like having a dedicated ChatGPT instance that understands the specifics of your project. It doesn’t just answer generic coding questions — it generates code based on the specific context of your work, making it incredibly intuitive and useful.

What I have found more surprising is the boost in productivity it provides when starting new projects. I will admit it, I have never been a fan of setting up new projects, especially when I have to optimize my time between multiple issues. Now, this task becomes much smoother and efficient, saving valuable time and effort.


Using GitHub Copilot’s chat to generate one table with Angular Material

![Angular Material Table with Copilot](/posts/copilot3.webp)
![GitHub Copilot Code Suggestions](/posts/copilot4.webp)

Now, with GitHub Copilot I am starting to believe that these tools, when used properly, can truly be game-changers. Their impact, for better or worse will inevitably shape the outcomes of the IT sector. In my personal opinion, the difference between enterprises equipped with AI tools like Copilot and those without them could determine not just the success or failure of a single project, but their overall competitiveness in the industry.

## Pros

After some time using Copilot I would summarize its main benefits in three different aspects:

### Optimization of Time in the Beginning of Projects

GitHub Copilot helps developers kickstart new projects by generating boilerplate code, setting up common configurations, and suggesting initial structures based on project requirements. This can significantly reduce the time spent on repetitive tasks, such as creating folder structures or writing basic class definitions, allowing developers to focus on the core functionality of the project from the start.

### Improvement in Quality Code

By leveraging its training on a vast dataset of high-quality code, GitHub Copilot provides intelligent suggestions that include best practices, coding standards, and design patterns. It helps developers write cleaner, more efficient code by offering context-aware completions, refactorings, and suggestions for a wide variety of cases.

### Support with Unit Testing and Test Cases

Copilot suggests edge cases, data inputs, and even appropriate assertions, ensuring comprehensive test coverage. By automating much of the boilerplate involved in testing, developers can focus on verifying the logic and reliability of their code. This not only accelerates the development cycle but also promotes a culture of testing from the outset.

## Cons

On the other hand, not all that glitters is gold; there’s always room for improvement, I’m still having some personal issues with Copilot:

### The Need for Balanced Usage

Effective use of Copilot requires a balanced approach. It should serve as a support mechanism, not a substitute for critical thinking or manual effort. Proper utilization ensures the tool enhances productivity without compromising independent decision-making.

### Overreliance on AI Tools

While Copilot is a powerful assistant, excessive dependence on it can hinder personal skill development and problem-solving capabilities. Users may find themselves relying on the tool as a crutch rather than using it as a complement to their own expertise. Personally, this is the biggest disadvantage I can think of at the moment. Using Copilot can make a lot of difference between forming good and lazy developers.

### Expertise Required for Validation

Depending on the complexity of the problem, users may need significant expertise to evaluate the accuracy of Copilot’s suggestions. Without the necessary knowledge, it becomes challenging to determine whether the AI’s output is correct or suitable for the context.

## Conclusion

I’ve summarized my experience with the tool over the past month, and I must admit that after testing it in real scenarios, I’m now more inclined to integrate GitHub Copilot into my daily workflow. That said, concerns remain regarding how the models are trained and the protection of sensitive data. Only time will tell how these issues unfold. For now, this former skeptic is ready to embrace the potential of AI — at least for personal projects! ;)
