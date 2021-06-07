+++
author = "Shiraz Valji"
date = 2021-06-06T15:57:00Z
description = "zero trust misunderstandings; thanks vendors, analysts and history."
image = "/uploads/icons8-team-olzlxzm_mow-unsplash.jpg"
tags = ["Cybersecurity", "Blog"]
title = "Musings on Zero Trust"

+++
18 months I’ve been talking about the new world of ZT, no surprises on the trigger (c-19), this is what I’ve learnt so far.

The initial conversations led me to believe there’s a misunderstanding on the terminology, today there's still a misunderstanding (thanks vendors, analysts and history).

I always start with these slides, it gives me and everyone else permission to be wrong.

![](/uploads/planning-for-the-future.png)

I don’t think anyone really cares of differing opinions, the aim is to find what Zero Trust could mean for you today and later in the future.

![](/uploads/zero-trust-timeline.png)

So what have I learnt talking about this for 18 months?

I’ve learnt I really dislike the idea of radical ground up solutions that often put customers on the path of a complete rip/ replace, no one wants this, this practice should have died with the dot-com bubble.

First lesson, don’t make a plan yet. Leverage what you have, the critical components of Zero Trust are likely already in your Network, FWs, Federated Authentication, a number of EPPs and Agents that might be lying around fully-in-support.

Second, as always, figure out what needs protecting, put a dollar value on the loss, breech or underground re-sell value of your most important, revenue generating, mission critical data.

Third, plan and build a ZT strategy to protect THAT data. Use, 2FA, Complex Password, EPP polices, FWs and...I currently hate the phrase, good Info Sec. ‘Hygiene’. This typically means someone reviews the AD security policies and tightens them up!

Fourth, figure out the hosts and systems and networks that can connect to your systems with the most critical data (from session two), this exercise often leads to the ‘uh-oh’ moment, but it’s normally free to fix, cut it or auto-patch it!

OK, now go ahead and talk to vendors a little more, How can I police; what is connecting, who is connecting and then continuously evaluate THOSE connections? Ideally you want to be in a position to assume guilt, for every session.

Whatever you do, don't but buy the bus, with ZT you literally have to measure thrice and cut once, and that 'cute once' should be iterative steps over a course of time, allowing you to iteratively assess each building block over time.