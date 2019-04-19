---
layout: post 
title: "Explaining Technical Debt to Non-Coders"
subtitle: ""
date: 2019-04-08T23:00:02-07:00
description: "Technical debt is not a very intuitive concept for non engineers. If you're in software engineering, chances are that at some point in your career (and maybe frequently!) you'll have to introduce to a non-engineer to the metaphor of technical debt and explain why it happens. This is another way to think about it."
image: "/img/card.jpg"
draft: false
IsPage: true
showtoc : false
---

If you're in software engineering, chances are that at some point in your career (and maybe frequently!) you'll have to introduce to a non-engineer to the metaphor of [technical debt](https://en.wikipedia.org/wiki/Technical_debt "Technical Debt") and explain why it's used in the field of software development. That person may be an executive in your company, a customer or perhaps just a friend or loved one wondering why things take too long. While the metaphor technical debt as coined by [Ward Cunningham](https://www.youtube.com/watch?v=pqeJFYwnkjE) is close to perfect when it comes to describing the origins and impact of the phenomenon, I feel like it's sometimes hard to explain to non-technical folks how it comes.

When explaining technical debt, you're basically telling someone that the design of your system is no longer or _was never_ optimum and the longer you go on without addressing these issues the more painful the repercussions of that mis-alignment become. At this point in the conversation, the non-engineer will be questioning your competence, your sanity and may even ask you outright, "Why didn't you just design it right in the first place?"

In addition to the technical debt metaphor, here's another analogy I've used to help add color to the situation:

Imagine you're opening a tiny restaurant and you're going to make one thing: french fries. You get a small shack (because that's all you can afford) and you lay out your shack with an area to clean and chop potatoes. You've got a refrigerator that you probably don't want directly near your deep fryer, so you locate that across your kitchen. You've got a cash register behind a small window. You've thought this out perfectly, your fry shop opens and is a monument to efficiency, you're cranking out fries and people love them.

Inspired by demand, you decide to offer milk shakes. There isn't enough counter space right near the refrigerator, so you have to put the milk shake machine on another counter a few steps away. Not a big deal to walk those few steps with ice cream, you don't make a millions of shakes a day. It's fine. Next you decide you can add a grill for hamburgers, that needs gas hookups next to the fryer, so you move the potato chopping station across the room near the milk shake machine.  Your milkshakes are so successful that your first milkshake machine can't keep up. Your model makes one, but there are other models out there on the market that can make three at a time, but you're actually out of room in that part of your shack and don't have the room.

People want beer with fries because, duh, that's delicious. You don't have room by the register, so you locate the beer tap on the backside of your shack. If someone just wants a beer the cashier (or someone) has to walk across the kitchen to get the beer then come back to the cash register to deliver.

When you first opened your shack, it was designed to make french fries as efficiently as possible, but now you're making burgers, milkshakes and serving beer. You shack is no longer designed in an optimum way to deliver all of those things well. Employees are taking unnecessary trips across the shack, they're bumping into each other and they're waiting for each other to pass at critical cross traffic locations. At the beginning you weren't 100% sure if or when you'd ever make other menu items, you didn't have the budget for a bigger place so it was difficult to plan for this appropriately.

In this (pretty stupid) analogy, the shack is your product and your menu items are your features.

As time goes on a software system will inevitably add new features and frequently you'll need to get these features out the door fast for some type of sales opportunity or customer deadline. You may not have time to "do it right" and you may not realize what the "right" solution is until afterwards when you see the product in action. To get back to optimum a result you are going to have to shift around your code (pay off debt)--and that's an investment that takes time.

Cue the part in the conversation when someone asks you why you didn't just design it for all these things in the first place. Surely you knew you _may_ want to sell burgers & beer someday. However, that is a slippery slope. Engineers and architects do need to spend a lot of time thinking about the future when designing products, but when doing that they can quickly run into another (possibly bigger!) problem: premature optimization. This term, coined by Donald Knuth and used famously as ["premature optimization is the root of all evil (or at least most of it) in programming."](https://en.wikiquote.org/wiki/Donald_Knuth). Knuth was apparently referring to efficiency optimization when he uttered this phrase, but the same principle also applies to optimizing around future features. I learned very early on in my career that I added complexity to my products when I tried to  anticipate features that we may need one day. But guess what? Frequently that future never came or it came A LOT later than I thought it would. Instead I delayed shipping product and even worse I had to now code around the unnecessary complexity I added for these features. The future, like the stock market, is routinely unpredictable.

While the fry shack analogy is pretty fun, it's pretty narrow in it's explanation of why tech debt happens. Here is another great source that categorizes technical debt, which may help when discussing with others [3 Main Types of Technical Debt](https://hackernoon.com/there-are-3-main-types-of-technical-debt-heres-how-to-manage-them-4a3328a4c50c) 
