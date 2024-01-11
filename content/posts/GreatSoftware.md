---
author: "Luke Bottomley"
title: "Setting Teams up for Success"
date: "2022-07-08"
description: "Setting Teams up for Success"
tags: ["Team Setup","SAFe"]
categories: [SAFe]
ShowToc: false
ShowBreadCrumbs: true
draft: false
comments: true
---
By opening the post it (hopefully) means you’re interested in giving your teams the best possible chance of success. If not, this blog post probably isn’t for you….

In my previous blog ([(1) (Repost) Most Enterprise Software Challenges are Non-Technical. | LinkedIn](https://www.linkedin.com/pulse/repost-most-enterprise-software-challenges-luke-bottomley/?published=t))

I previously described several common problems I‘ve experienced with software projects in enterprise organisations.

This post is going to introduce some ideas for how to give you and your teams the best possible chance to avoid them.

## Recommendation Number 1: Organise teams around value

In my previous post, I identified „Sub-Optimal“ team structure as a one of the reasons enterprise projects struggle.

Sub-optimal team structure introduces dependencies, often too many dependencies.

Having too many dependencies introduces latency, introduces friction and generally decreases quality.

One solution to this. Organise teams around value.

![No alt text provided for this image](https://media.licdn.com/dms/image/D4E12AQHYlxT1lJ8_-w/article-inline_image-shrink_1500_2232/0/1657278966929?e=1710374400&v=beta&t=eUOmp5SsGfYyMETzt-c8x58d31_DFBKmNCbD0OKhGPA)

Now the statement of organising around value appears as number 10 in the SAFe Lean Agile Principles (I also warned you in my previous post that what I write about wouldn‘t all be new).

If you’ve never heard of SAFe, it stands for Scaled Agile Framework and although there are [arguments about whether SAFe is agile or not](https://jeffgothelf.com/blog/safe-is-not-agile/), I’d still say this principle is a good one.

You can find the principle and it’s meaning described [here](https://www.scaledagileframework.com/organize-around-value/).

Value can have multiple definitions depending on what you are trying to achieve, but the aim should always be to organise around value.

### For example:

- A Use-Case based team - For example „Deliver Omni-Channel Licence Renewals.

SAFe calls these “stream aligned" & spoiler alert: I’ll do a separate blog around the benefits of Use-Cases later.

- A complex sub-system team, a team that uses a separate (& complicated) system or subsystem (for example a Payment & Billing team).

[Here’s more information](https://www.getlago.com/blog/why-billing-systems-are-a-nightmare-for-engineers) about why that’s a good idea.

- Enabling Teams (e.g. Consent)

For processes which have a lot of dependencies outside the delivery team. (e.g. Consent with Legal). These teams should be focussed on building enabling functionality that allows Use-Case based teams to be successful.

But however you define value, the advantage of organising like this is to ensure the team(s) can wherever possible deliver things independently and without dependencies to other teams.

### That‘s great… But what does it mean for me?

To put this in practical teams, this almost always means by definition that teams should be cross functional.

With Integrated Testers, Integration, Developers & Business Analyst working together in a cross functional team it means…. **BINGO**! - No external dependencies.

By naming value as a Use-Case we reduce the dependencies to a minimum as the team should (hopefully) be able deliver them without waiting for decisions from external teams.

At this point you should probably also consider if you break out your enabling processes into their own teams who offer their process as a service.

*There are a whole bunch of other benefits integrating testing, I‘m still hopeful I can convince one of my network to write a separate post in the future so I‘ll leave it there.

_The recommendation: Build your team structure around however you define value, make them cross functional and keep dependencies to a minimum_

## Recommendation 2: Prioritise, prioritise, prioritise.

In most busineses there are more things to do right now than it‘s possible to achieve in the time available. @Mulesoft refers to this problem as “The IT Delivery Gap”.

![No alt text provided for this image](https://media.licdn.com/dms/image/D4E12AQGC5tqD3916Dg/article-inline_image-shrink_1500_2232/0/1657279361241?e=1710374400&v=beta&t=unmXctks7msyX6FCDerk4uCAW_cc8Un-0AqKd6kqzU0)

My first blog post addressed the topic of the perils of working on too many things in parallel.

**SAFe Principle** #6. Limit work in progress.

Lot‘s of companies have the problem that they do not do this effectively either because they are not capable of the stakeholder management required (saying no is key!) or that are not enabled too (politics).

This article ([https://alexturek.com/2022-03-07-How-to-do-less/](https://alexturek.com/2022-03-07-How-to-do-less/)) is **one of the best** I‘ve seen to explain how to prioritise effectively and gives some tips about how to say no or great idea but not yet!

_The recommendation: In order to set teams up for success, you need to prioritise (and enable others to prioritise) and do it well._

## Recommendation 3: Manage the Intake Process

Now manage is a scary word. It implies following a clear, well defined and battle test process and having difficult conversation but what I really mean is that enabling your team to prioritise (and say no) is all well and good, but if you allow (some) stakeholders to skip the process you‘ll eventually in a situation where you‘re either working on too much in parallel or you‘re constantly in a situation where different stakeholders (depending on their importance) are setting different expectations for the team.

I think the examples below will be familiar to you all throwing your existing priorities out the window.

_„The Director of (x) this needs this by tomorrow“._

_„We need this for (x) by next week“._

Now often the problem is that the stakeholder management isn‘t as good as it should be (see point 2) but Even in the case of good stakeholder management where we align of changing the prios and inform the important people that we‘ll work on it as the next priority it usually ends up in the following situation.

„Make it happen, how many extra resources/ much extra budget do you need“?

And this opens a whole other can of worms which I‘ll hopefully cover in point 4.

The overarching point is that once you have a requirements / intake process that you absolutely make sure it‘s followed, that the value behind such a process is clear and communicated & that there is no way around it (no exceptions!)

The stakeholders must be prepared to accept no for an answer or at least accept their place in the list. It‘s for this reason that communicating the value of such as process is so important.

Now, the intake process should still be anti-fragile. It shouldn‘t rely on anyone person in case of holiday, sickness or someone leaving the company. That‘s right artitects, life even goes on when we‘re not there. :)

_The recommendation: Strictly managing the intake process (and not allowing exceptions) will give your teams the best possible chance of success._

## Recommendation 4: Empower Your Team(s)

Working in an enterprise is sometimes tiresome. Your developers know there‘s a problem, your POs know there‘s a problem, your architect‘s know there‘s a problem. In fact, everyone knows what the problem is and usually they know the solution (or at least solution options) too!

The challenge is often that teams are often not enabled to make the (sometimes painful) decisions required to solve problems and remove blockers

Ultimately it‘s the teams that have the best knowledge about what the good (or bad) solutions are and what needs to be improved and if you enable them to solve problems, you’re might just get things done.

And if it doesn‘t work, well hey, we‘re agile. Let‘s learn from the failure and try again.

Enabling your team involves management developing trust, it involves them giving guidance and coaching rather than making decisions themselves and it involves them letting go.

Ultimately if people and teams are responsible for solving the problems themselves, they‘ll be a hell of a lot more invested in the outcomes and you might just see some great things happen.

Ultimately enabling your team applies equally to functional & technical things.

Examples like taking staffing or team structure decisions away Product Owners (or Product Managers) or telling them how to spend their budget or/even which external partner to use would all fall foul of this recommendation.

If we hire a PO / PM and trust that they are the right person for the job let‘s enable them to make decisions too.

_My recommendation here is: Empower your teams to solve problems._

In summary, it’s my absolute belief that if you organise your teams around value you‘d already go a long way to setting your teams up for success. But if you do it while enabling them to prioritise effectively, making sure there are no exceptions AND empowering them to solve problems you‘ll have gone a long way to setting your teams up for success.

## TL;DR

**Give your teams the best possible chance of success by organising them around value (to reduce dependencies), prioritising well (to limit work in work in progress), managing the intake process (to ensure you can prioritise) and empowering your team (to enable them to solve problems that they can & remove the blockers they can‘t solve).**

I‘d love to hear if you‘ve had similar experiences or even if your experience contradicts the recommendations made. Please feel free to leave a comment in either case.

Equally if you‘d just like to get in touch for an exchange about similar topics or give me tips on what I should write about in the future, please feel free to reach out.

As always... Thanks and until next time!

Luke
