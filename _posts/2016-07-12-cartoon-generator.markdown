---
layout: post
title:  "p5.js cartoon generator"
date:   2016-07-12 14:29:35 -0400
categories: creative p5js
---

This p5.js sketch uses a genetic algorithm to generate cartoons. Made for the [Kadenze Nature of Code class][kadenze]. [Click here][click-here] to see it in action. Find the code [here][code-link].

![Example comic](/assets/2016-07-12-cartoon.png)

The original plan was for the critic (head on the side when you click through to the app) to change facial expressions depending on what you hovered over on the screen. In effect, it would have been a bit of a game, where you would click preferred images to try to converge on an optimal target as quickly as possible. In reality, I never implemented the facial expressions. While the sketch still uses the idea of the critic having a preference, that preference is not displayed to the user and creates some confusion as to why the cartoons converge on any particular style or language.


[kadenze]: https://www.kadenze.com/courses/the-nature-of-code/info
[click-here]: generative_cartoons/index.html
[code-link]: https://github.com/clayheaton/generative_cartoons