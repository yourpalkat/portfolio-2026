---
layout: ../../layouts/WritingLayout.astro
title: 'As Little as Possible'
slug: 'as-little-as-possible'
pubDate: 2020-06-19
featureOrder: 2
author: 'Kat'
description: 'Thoughts about building less, but better.'
introText: 'Thoughts about building less, but better.'
tags: ["blog", "web dev", "astro"]
---
There’s a running joke in programming that efficient, DRY, reusable code is considered best-practice only because developers are lazy. It’s not entirely untrue, which is what makes it a pretty good joke. I’ve made it myself. But: if programmers are so inherently lazy, why do we keep over-engineering things?

> Good design is as little design as possible.

That’s an oft-trotted out quote from Dieter Rams, the industrial designer who is basically the heart and soul of Braun, the German consumer electronics company. This is the tenth of his ten principles of good design; all of them are worth heeding, but this is the one that gets quoted the most often, and it’s the one that applies most to what’s on my mind today.

There’s a common tendency — and I’ve been guilty of it, especially as a new developer who’s still learning as much and trying as many new things as possible — to reach for the biggest club in the bag when solving a problem. I want to grab that neat library I just read about and use it on this project, because it’s new and interesting, because it’s a fun challenge, because I want to learn to use a thing, because when I have a hammer everything looks like a nail. And, not for nothing, because I’m looking for a job and I want to show off that I know how to do something.

We should, rather, be showing off that we know when not to do something, and why. We don’t need to add in a bonkers amount of JavaScript libraries to build a landing page. HTML and CSS is fine.

(It’s better than fine, it’s ideal! It’s the right tool for the job! Have you seen the crazy-ass things you can do with CSS? CSS is amazing.)

We don’t need to go nuts with tab-index and aria-label on everything; if we use semantic elements in a logical order, we get a lot of accessibility benefits out-of-the box, and then we can add more code where needed to make sure of a good experience for everyone. Again: use the right tool for the job, even if it’s not a glamorous new thing.

So much of good design — and good development — is about doing your users a kindness. That means meeting them where they are on a lot of different levels:

- copy that’s approachable and clear, but doesn’t talk down to them;
- images that look great on their device, but aren’t so big that they chew bandwidth;
- sites that are as performant as possible, so the user can see our content and finish their tasks quicker;
- accessibility that’s considered and built-in from the start, rather than bolted-on at the end;
- animations or visual flourishes that enhance the experience, but aren’t distracting and can be turned off if the user indicates they prefer that.

It’s a lot! But all these things have in common the simple precept that we should do as much design and coding as we need to, and no more, unless we’re certain it improves the experience. “As little as possible” isn’t a joke about laziness, it’s a careful and deliberate decision about how to do what’s best for the user.

We may wind up building things that don’t look as flashy in our portfolios, but we shouldn’t be building things for our portfolios in the first place: we should be building things for the user.

We shouldn’t be making “more, because we can” – rather, we should always try to be making “less, but better”.