---
layout: post
title: "AI Can't Tell Time: What Two Weeks Testing Claude Taught Me About AI Assistance in Civic Tech"
date: 2026-01-04
tag: "AI & Tools"
summary: "I spent two weeks putting AI through its paces using my real life as a proxy for civic tech work. What I discovered challenges both the hype and the skepticism."
---

I'm a product manager with over two decades of experience in private and civic tech. I'm also an AI skeptic. When everyone started breathlessly talking about AI transforming work, I wanted proof — actual evidence that these tools could handle the unglamorous reality of government and nonprofit tech work. As I have been between gigs for the past several months, I decided to seize the opportunity to look for that evidence myself.

I spent two weeks putting AI through its paces, using my real life as a proxy for the things folks like me do at work: real projects, real deadlines, real consequences. With Claude's help, I managed budgets, built presentations, coordinated schedules, and ensured accessibility compliance. What I discovered challenges both the hype and the skepticism: AI is capable of more than I expected and can also be trusted even less than I feared.

My approach was simple: real-world testing, not theoretical scenarios, based on what actually needed to be done in my day-to-day life. I documented everything, created daily performance grades, and tracked variance between what AI promised and what actually happened. I used it for the kinds of tasks I'd actually do in a civic tech product or project management role — schedule coordination, document creation, research synthesis, and strategic planning. I wanted to see what the real consequences of using it would be, using tasks with low stakes.

The question I wanted to answer: Can AI tools genuinely augment product and project management work in government and nonprofit settings?

Spoiler: The answer is "it depends," but in ways more extreme than what I was expecting.

## The Surprise Win: Christmas Shopping

I started with what seemed like a trivial test: managing Christmas shopping for 21 people with a set budget. This is fundamentally the same skill set as managing a small civic tech project. You're brainstorming options, making prioritized decisions, tracking deliverables, managing budget, coordinating timelines, and making sure nothing falls through the cracks.

Instead of building a spreadsheet, I just had conversations with Claude. "Bought Aunt Harriet audiobook subscription, $120." There were no manual updates and no formulas. When I got stuck on gift ideas, I asked for suggestions, and Claude brainstormed. Claude kept a running budget total automatically and remembered what I'd already bought when I checked in later.

The specific wins were impressive. When I was drawing blanks on books for my 89-year-old grandmother, Claude helped me curate a list of 81 options she'd actually enjoy. It suggested a MIDI keyboard for my 13-year-old son — a perfect gift I didn't even know existed. It tracked purchases across multiple shopping trips, kept running totals without my doing math, monitored shipping, and remembered context from previous conversations.

The result? Easiest Christmas shopping year I've ever had.

This worked so well because the task was asynchronous and not time-critical. It was conversational; it was cumulative; it was forgiving. Finally, and most crucially, it was low-stakes. A wrong gift means mild disappointment, not a policy failure that affects vulnerable families.

This is what AI does well: ongoing, flexible, iterative work where "pretty good" is good enough and where human judgment can catch and correct errors without serious consequences.

## The Spectacular Fail: Schedule Management

Encouraged by the Christmas shopping success, I tested something a bit more professionally relevant: daily schedule creation and tracking for a week of family coordination. If AI can't manage my personal calendar, it definitely can't manage a government project timeline.

It was a disaster.

I created versioned documents, trying to get a working schedule. Claude made consistent time and date errors. It thought a hockey game that started at 7:30 hadn't happened yet at 9:43. It estimated fifteen minutes for a drive that takes 35. It lost track of whether tasks had actually happened. There were platform synchronization issues where mobile and desktop showed different information.

Specific failures included allowing me to schedule overlapping appointments, "forgetting" I'd already watered the ferns, being unable to track whether I'd called the vet, and mixing up days of the week — repeatedly. If I didn't tell it time had passed, it assumed it hadn't. I spent more time managing the AI's mistakes than it would have taken to just use Google Calendar or a productivity tracking tool.

Why did it fail so spectacularly? Because schedules are time-sensitive, requiring temporal accuracy. There's also no tolerance for errors; a missed appointment has real consequences. They are precise — not "around 3pm" but "exactly 3:30pm" — and require real-time updates. Finally, especially when coordinating the activities of multiple people, they are complex and there are consequences when mistakes are made.

This is what AI does poorly: anything requiring temporal precision, real-time coordination, or zero-error tolerance.

The professional implication here is an important one: If AI can't manage my Tuesday, it absolutely cannot manage a multi-stakeholder project timeline. The consequences in civic tech work — delayed housing approvals, missed grant deadlines, coordination failures with vulnerable populations — are far too serious to trust to a tool that can't reliably tell time.

## The Useful Middle Ground: Document Creation

Between the spectacular win and the spectacular fail, I found a useful middle ground with document creation. I needed to create a presentation for a job interview. Could AI make this process easier or more efficient?

I gave Claude my detailed outline and asked it to create slides. The first attempt was disappointing: basic bullets, boring design, generic corporate template. I told it directly: "This is pretty bad. Can you do better?"

The second attempt was dramatically different. Professional design with visual hierarchy, a cohesive color scheme, structured two-column layouts where appropriate, and callout boxes for emphasis. The presentation was 90% complete in about fifteen minutes.

This revealed what I'm calling the "laziness problem." AI will often produce "good enough" work unless you push it. It won't automatically give you its best effort. The second attempt proved it was capable of much better work all along — it just needed to be challenged to produce it.

What this experience showed me: AI is excellent at turning ideas into polished deliverables, but it needs human direction on quality expectations and tone. It iterates quickly based on feedback and handles formatting and visual design well, but you still need human refinement for that final 10%, and you can't just accept the first output. If something feels generic or low-effort, say so. AI often has another gear but won't use it unless prompted.

The professional applications are clear. By all means, use AI to draft presentations you'll refine, create structured documents from rough notes, handle formatting while you focus on content, and turn outlines into polished deliverables quickly. But always demand quality — don't just accept whatever it gives you first.

The time saved was significant. What would have taken me 2–3 hours of slide-building took fifteen minutes, leaving me time to polish and practice my presentation, rather than wrestling with formatting.

## The Accessibility Win: Alt Text and Image Description

One of the most unexpectedly valuable applications turned out to be accessibility compliance. In government work, creating alt text for images isn't optional — it's legally required under WCAG 2.0 AA standards and morally essential for ensuring equal access to information.

I tested AI's ability to create alt text and identify objects in photos. I uploaded various images and asked for accessibility-compliant descriptions. The AI provided detailed, accurate descriptions, identified objects and settings correctly, and generated compliant text quickly.

This matters because accessibility work is important but tedious. It has clear right and wrong answers. It needs to be done for every single image. It follows established standards. It takes significant human time, even though it doesn't require human judgment.

The applications for civic tech work are immediate: AI can make documents WCAG 2.0 AA compliant faster, create alt text for presentations and reports, identify elements in images for documentation, and reduce time spent on compliance tasks while maintaining quality.

This is exactly the kind of "useful but unglamorous" work where AI delivers genuine value. Accessibility isn't a nice-to-have — it's a legal requirement and an ethical imperative. A tool that makes compliance easier and faster while maintaining quality is worth using.

## What This Means for Civic Tech PMs

After two weeks of systematic testing, here's what I tell people now about using AI in civic tech and government work.

**Use AI for:** research and synthesis you'll verify; document drafting you'll edit and refine; brainstorming ideas you'll evaluate; organizing information you'll review; accessibility compliance tasks like alt text; async tasks where iteration and verification are possible; and low-stakes work where errors can be caught and corrected.

**Don't use AI for:** managing project timelines or schedules; coordinating stakeholders in real-time; anything where "pretty good" isn't good enough; time-sensitive operations; critical decisions where mistakes have serious consequences; or work requiring temporal precision or zero-error tolerance.

A clear pattern emerged from my testing: AI excels at basic assistant work — flexible, forgiving, cumulative tasks where iteration is possible. AI fails at project manager work — precise, time-sensitive operations where accuracy is non-negotiable.

The fundamental rule is **supervise everything**. Every output needs human review. Every recommendation needs verification. Every "fact" needs confirmation.

When you play to its strengths, AI is genuinely valuable. Just don't let the hype convince you it's ready for mission-critical operations. In public sector work, we can't afford that mistake.

## Was I Wrong?

I went into this testing expecting AI to be mostly hype with limited practical value. I was wrong — but also right.

I was wrong that AI has no real utility for civic tech work. It does, when used strategically, with clear limitations. The Christmas shopping success, presentation creation, and accessibility compliance work all showed me that AI can genuinely make certain aspects of my job — and life — easier and faster.

But I was right about the core concern: AI cannot be trusted with mission-critical operations. It's not ready to manage projects, coordinate teams, or make decisions where errors have serious consequences. The scheduling failures proved that dramatically.

What surprised me most is that AI turned out to be genuinely valuable as a "thought partner." Not revolutionary. Not transformative. Not a replacement for human expertise. But useful enough that I am still using it for the right kinds of tasks.

Is it worth the hype? No. The claim that AI can do everything, replace human workers, and transform how we work is oversold.

Is it worth experimenting with? Yes — if you go in with clear eyes about what it can and cannot do. You have to understand its limitations and be willing to verify everything. You must use it as a tool in your toolkit, rather than a replacement for human judgment.

For civic tech product and project managers, I recommend you try it for the low-stakes stuff and see if it makes your work easier. Use it to draft documents you'll refine, research topics you'll verify, organize information you'll review, and handle tedious compliance tasks. But don't let anyone convince you it's ready to replace humans in the work that actually matters.

When you're trying to improve people's lives, accountability isn't optional. Lives and livelihoods depend on getting things right. Use AI as a tool to augment your capabilities, not as a replacement for competent, accountable humans who understand the stakes of the work we do.

*Originally published on [Medium](https://medium.com/@gracemitchellwriting/ai-cant-tell-time-what-two-weeks-testing-claude-taught-me-about-ai-assistance-in-civic-tech-41b7fad692be).*
