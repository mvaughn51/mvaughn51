---
layout: post
title: "Halloween Decorating, and the 'Bits' Behind It"
date: 2026-08-02 09:00:00 -0700
categories: [Random]
tags: [halloween, home-automation, embedded, hobby]
toc: true
image:
  path: /assets/img/halloween-frontyard.jpg
  alt: The front yard at night, decorated for Halloween with a lit "Cemetery" sign, fog, and a coffin prop
image_inline: true
---

Around 2010 I started getting into Halloween decorating as a hobby, and this is the result. We probably get at least 200 kids (big and small) through the neighborhood on the big night. I've had some kids tell me this is their favorite house, and they make a point to come by every year.

Unlike a season like Christmas, this isn't spread out over weeks — it's a single-night event. Setup starts the weekend before, the display goes live on the 31st, and everything comes down the next day.

<div class="mt-3 mb-3">
  <img src="/assets/img/halloween-frontyard.jpg" class="preview-img" alt="The front yard at night, decorated for Halloween with a lit &quot;Cemetery&quot; sign, fog, and a coffin prop" w="1600" h="2125">
  <figcaption class="text-center pt-2 pb-2">The front yard on the big night — fog, lighting, and a cemetery gate greet everyone coming up the walk.</figcaption>
</div>

## The bits

I call each individual piece of the display a "bit" — a fog effect, a talking skull, a motion-triggered scare, a lit prop. There are somewhere around a dozen of them spread around the yard in a given year, some running for over a decade now, others rebuilt or replaced along the way. A few of the more involved ones — the animatronic skull, the beam-triggered scares, the fence lighting — are complex enough to deserve their own posts, which I'll get to over time.

## The master controller

Tying it all together is a PC running Linux Mint, with a mix of custom and open-source software coordinating the whole display. Alongside that PC, 10-12 microcontrollers are spread through the yard, each handling one or more bits locally and taking direction from (or reporting back to) the central controller.

<div class="mt-3 mb-3">
  <img src="/assets/img/halloween-controller-operating.jpg" class="preview-img" alt="The master controller rack running, with monitoring software and a terminal visible on its screen" w="1400" h="3753">
  <figcaption class="text-center pt-2 pb-2">The controller rack in operation — the brains of the display.</figcaption>
</div>

I'll cover this rack in more detail in a future post — what's actually running on it, and how the custom trigger controller boards talk to the bits out in the yard.

## See it in action

A short video of most of the bits running on the night: [watch here](https://drive.google.com/file/d/11IR2d4JOD6bSJkpHJnvAvGqdGFLzIwU5/view?usp=drivesdk).

This is meant as an introduction — future posts will go deeper on individual bits, starting with the master controller itself.
