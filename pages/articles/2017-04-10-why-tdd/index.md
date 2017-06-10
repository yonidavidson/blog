---
title: Why TDD?
date: "2017-04-15"
layout: post
path: "/why-tdd/"
category: "Engineering"
description: "general rant about software engineering."
---

Why TDD?
That is the question for many engineers.

Lately I went to a 'code retreat' at a different company and this question was raised (We were around 30 developers) "How many engineers actually TDD at work".
I was shocked to understand that except for me and 2 other engineers from the company who ran this retreat everyone were not practicing this at work.
Excuses where split:
1. Some never heard of this technique.
2. Most Common reason was that it slows you done and that it isn't suitable for "Production".
3. A small group said that they would like to but it's just too hard.

My response to this:

1. If you are a software engineer (Especially a backend engineer) and you never heard of TDD you should consider changing your workplace.
The past few years I worked for big companies, Startups and mid size companies and I can say that although testing is common in the larger size companies (Startups have a tendency to slack) no one speaks about TDD. Usually the bigger companies will have more "Marshaling" about coding standards and a process that holds the code in a standard (Design review) but TDD is not part of the tool set. I think that this is since TDD is not something that is discussed in our Universities and since a lot of engineers in Israel are trained in the Army (Which doesn't do TDD).

2. If I had a dollar for every "Senior engineer" that snarled at me doing TDD and told me that I over price my tasks in scrum I could have retired already.
Code that was not written using TDD has a tendency to get stale very fast - This means that once errors are risen or a change is needed it becomes a serious pain. The amazing thing is that the same people are afterwards the onces that you need to keep in the system since it's hard to change that code.
Another price that no one talks about is the fact that writing code is EASY! but for every hour you spend writing code you'll spend at least 3 times more reading the same code just for making small changes, This is where TDD shine since refactoring your code later becomes a breeze since you don't need to be fully immersed in the code but just to understand the small area you want to change and make sure all your tests pass!

3. I believe that this is the true reason why people don't TDD. Since companies can't really review all the code which is written and enforce quality this way engineers (And people in general) look for the easiest way to "deliver". I myself don't always TDD (mostly when I enter a new code base which doesn't have proper testing) as engineers we have the obligation to remain practical and deliver features and business logic in predicated time constraints and this mean that sometime we need to increase our tech-debt (Untested code is a loan against time).

Summary:

I don't always TDD myself, Not always I am working in a testable code base or that I am working in a tech-stack that I haven't practiced for a while and I get into time constraints. But I'll catch-up, Usually choose a simple task and use it to work on my TDD skills in the current stack.

Companies needs to understand that the  quality of the engineering department is changing all the time, Not always everyone is in their top game (Changing language, framework or just busy with personal matters) and every day your programmers are writing code your tech debt is rising. The only thing you can and you should make sure is that if you'll need to re-factor some of the old work (That's the business logic that actually matters since you are revisiting it) it will be as easy and safe as possible - And this is what TDD allows you to do.

Personally, TDD helps me write code faster and easier, Something in being in the rhythm of Test, Test, Re-factor makes my work much faster and allows me to solve big issues in small chunks.