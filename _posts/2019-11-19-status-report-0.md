---
layout: post
title: "Status Report #0"
categories: [update]
image: /images/posts/speed_switches_cropped.jpg
---

The goal for the original proof of concept was to investigate something I've been sitting on for a while,

- How feasible is it to build a wirefree keyboard?
- Is this something that I want to fully commit to for an extended period of time?
- Is there any community interest in a wirefree keyboard, or is it just me?

The results are in, it is feasible but it will take blood, toil, tears, and keycaps to get there. Not only that, but this has become an obsession - it is without a doubt something I want to invest my time in. Further yet, the community welcomed me with an overwhelming positive reception.

With every objective for the proof of concept checked off, I'm taking another step forward:

- Hack together a keyboard prototype with off the shelf parts that demonstrates 3 core features: BLE HID, USB HID, Qi Charging.
- Check back in with the community to check for further interest in addition to directional feedback.

So where am I on that prototype?

The first order of business was to find a new SoC; the one used for the initial PoC was underwhelming. It had no USB support, was poorly documented, had an underwhelming SDK, and nonexistant community support. I assembled a list of alternatives that might suite my needs better and rewrote the initial proof of concept such that it will hopefully support several.

The switches and diodes have arrived. That leaves the case, it is on the way over from China so that gives about ~20 days to get the firmware to the point it needs to be. See you around then ;)
