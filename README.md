## Nouran Elsaraf

QA engineer. I test AI systems and work on LLM evaluation. When a model gives a wrong answer, I want to know where it came from. I'm also starting to build AI systems myself, and RAG-Doctor below is one of them.

### Transcendental Quest

My younger sister is in her first year of engineering and she couldn't get transcendental functions. I studied engineering too, and I know it's not easy to link what you learn at faculty to real life. I was in her place once. So I built her a game.

It's a browser game about rate of change, exponentials, trig and hyperbolic functions. You play with the graph and find the rule yourself. The formula comes after. Every idea has a real-life example so you can picture what it has to do with everyday life, and it explains things in Egyptian colloquial Arabic. My sister and some of her friends played it.

7 levels, about an hour to finish. Every drag on the canvas also has a slider, so you don't need a mouse.

[Play it](https://nouranelsaraf.github.io/Transce-functions/) · [Code](https://github.com/NouranElsaraf/Transce-functions)

[![Transcendental Quest level map](https://raw.githubusercontent.com/NouranElsaraf/Transce-functions/main/docs/screenshots/map.png)](https://nouranelsaraf.github.io/Transce-functions/)

### Working on now: RAG-Doctor

Some apps kept me on the customer support line for a long time, so I'd try the in-app support chatbot instead. It was useless. A good bot could help people right away, even late at night, save the support team's time, and only pass the issue to a person when it's something critical it can't handle. For that it has to get its answers right and know when to hand off.

I kept running into chatbots that got things wrong in real use, and the tester in me wanted to know where each mistake started. Most RAG eval tools give you a score, so you still have to guess what broke.

You give RAG-Doctor a question your RAG system got wrong and the right answer. It re-runs the pipeline with one change at a time, like inserting the correct passage or making the chunks wider, and shows you whether retrieval, chunking or the model caused the mistake. I'm aiming to finish it by December 2026.

### Stack

Python, TypeScript/JavaScript, React, Vite, pytest, Vitest, GitHub Actions, LLM-as-judge evals, RAG pipelines.

nouranelsaraf@gmail.com
