---
layout: post
title: 'Learning part 2: I already have ChatGPT, can''t I just ask it to do this?'
date: 2026-09-01
# Paste the LinkedIn post URL below to show an "Originally posted on LinkedIn" link:
# linkedin: https://www.linkedin.com/feed/update/urn:li:activity:XXXX/
---

I showed someone the DuckFleet agents over the weekend, and how the "agents" keep track of loyalty points for you. Her response was to get ChatGPT to do it. I found that really interesting, because she is a middle aged mother who is not technical at all. The instinct now is not "where do I download this," or app, it is "can my AI assistant just do it."

The onboarding experience is changing fast. But here is what I found: it is not actually straightforward to hand agents to someone like her. If you build something new, you can ship it as a custom connector, but she can only add it on the paid version of Claude, or as the single custom connector you get on the ChatGPT free plan.

So these days, building an agent means building at least two front doors. One is the connector. One is a plain web version. And even the connector has a catch: you have to add it from the web first before it shows up on your phone. Once I did that, I opened Claude on my phone, said "add Velocity to my programs," and watched it save. No deploy, no terminal, no cloud project. It runs inside the assistant I already use. I just had to go through the web once to get it there.

None of this is a clean "tap to install" yet, and building two front doors for one agent is more work, not less. If you are building agents right now, are you shipping a connector, a web app, or both? And has anyone cracked getting a non-technical person onto a connector without the web-first detour?

Give it a go: [DuckFleet](https://app.duckfleet.dev/), and let me know if it worked or it was utterly confusing.
