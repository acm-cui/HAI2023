---
layout: page
title: About the workshop
sidebar: [ "key-dates", "registration" ]

nav_text: About
nav_position: 0

seo:
  name: 'Why is my Agent so Slow? Deploying Human-Like Conversational Turn-Taking'
---

If we look at current conversational speech interfaces we see they are not very similar to human/human conversation. They are mostly two party speak-wait/speak-wait systems. Human conversation in contrast, is often multi-party, allows for fluid interruption and back channeling. Mimicking human behavior may not matter for many applications. For example, Siri, Google Assist, and Alexa function adequately without human/human style turn taking. It may also not be desirable in many contexts as it may encourage unwanted anthropomorphism. However, not being able to use effective elements of human behavior when required in an engineering design is severely limiting.

Major challenges in designing, building and deploying human-like conversational turn-taking systems include:
(1) A speak/wait dialogue system is able to run on one thread/processor, where all modules wait for the others before processing their output. However, as soon as being able to interrupt a process becomes important (often termed barge-in), or a response
is required within a fixed time window, a multi-threaded architecture is required. Such architectures are notoriously difficult to build, debug and guarantee stability.
(2) To implement human-like turn-taking you cannot depend on silence detection. Studies of human-human conversation have found that pauses within turns are on average longer than gaps between turns [2]
(3) The agent you use to render behavior must be: pollable - you know what is said when; interruptible - you can halt it gracefully at any moment; and streamable - you can queue up requests to the system. This has become particularly problematic with cloud based/web based interfaces where the system may not even know what audio device is being used.

We have evidence that poor turn-taking has an impact on user experience e.g. “users not only rate the incremental system as moreresponsive, but also rate its recommendation performance as higher.” The time is right to look squarely at the challenges in imple- menting and deploying human-like turn-taking and build systems that will make a significant difference.

|Start Time | Activity|
|-------|
|9.30am | Welcome |
|9.45am | Keynote Gabriel Skantze: KTH |
|10.45am | Brief introductions from all attendees |
|11.15am | Coffee Break |
|11.45am | Group discussion: Experiences and failures with spoken conversational systems |
|13.00pm | Lunch Break |
|14.15pm | 8 Short 10 minute talks from attendees |
|15.35pm | Group discussion: Design guidelines for building human-like turn-taking systems |
|17.00pm | Conclusion and wrap up |
|17.10pm | End of Workshop |
|19.00pm | Informal workshop dinner |
