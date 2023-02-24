---
title: Media Example
subject: Testing
subtitle: Lorem ipsum dolor sit.
authors:
  - name: John Doe
exports:
  - format: pdf
    template: arxiv_two_column
---

Here we will see:

An image  [](#fig-img).  

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

:::{figure} #my-img
:name: fig-img
Image from matplotlib
:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

:::{figure} #my-vid-embedded
:name: fig-vid-embedded
Embedded video
:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

:::{figure} #my-vid-not-embedded
:name: fig-vid-not-embedded
Not embedded video
:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.


:::{figure} #my-widget
:name: Bar
Interactive ImageSlider
:::

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

:::{figure} #my-gif
:name: fig-gif
:width: 300px
Animated GIF
:::


Hello World!



 <!-- For pdf export, run `myst build 01-hello.md` -->