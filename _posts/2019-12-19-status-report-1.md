---
layout: post
title: "Status Report #1"
categories: [update]
image: /images/posts/tty_wirefree_rev1.jpg
---

The hardware for rev. 1 is complete, a handwired bluetooth keyboard with wireless charging. I've began rewriting the firmware, which now supports HID over bluetooth and USB.

Specs:

- USB HID
- Bluetooth HID
- Qi Charging
- 150mah Lipo battery
- Split Ortholinear 50% layout
- Kailh Gold Speed Switches
- nrf5240
- Zephyr RTOS

I chose an ortholinear layout for this revision since it would be easier to handwire and I'm very partial to the layout, although this won't be the final layout. The battery size is just the product of what I had laying around, I'll have to order something with a little more juice. Working with Zephyr RTOS has been a joy, I'm now able to support a plethora of ARM SoCs instead of just one.

So what lays ahead? My short term objectives:

Market reserach on what layout to go with for the next prototype. I'm leaning towards a split tenkeyless or a 60/65% - but we'll see what people want the most. If you want to let me know I've put together a [google form](https://forms.gle/BnPAt7YkAT69tDKEA).

Shortly after the layout will need to be designed. This will lay a foundation for future case and PCB design.

Continual development of the firmware. Right now it is not public because I've been trying out a lot of ideas as quickly as possible and then throwing the bad ones away. As the firmware gets more stable I'd like to target a public release.