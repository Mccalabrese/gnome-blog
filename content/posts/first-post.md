+++
title = "Hello Planet GNOME! | GSoC 2026 Introduction"
date = "2026-05-13"
authors = ["mccalabrese@example.com (Michael Calabrese)"]
[taxonomies]
tags = ["gsoc", "gnome", "introduction"]
+++

Hello everyone, I'm Michael, and I am excited to be contributing to the GNOME foundation as a part of Google Summer of Code 2026.

### A bit about me

I am a Computer Engineering student and long time Linux user. GNOME has been my desktop environment for years and I was very excited to be working with the GNOME foundation.

I have a fairly significant amount of custom tooling that was all in Python and Bash, and about 16 months ago I began rewriting it in Rust, primarily to learn, however the performance and reliability improvements were quite noticeable. This led me to rewrite all of my scripts and tools in Rust. That experience put me in a great position to tackle the Rust rewrite of the Pitivi timeline ruler.

### The Summer Project

The plan of attack with this project is first to create a standalone GTK4 Timeline Ruler widget in Rust, then modify Pitivi to use the new ruler via `PyGObject`.

I am currently building a basic test binary, which can be found at [Project](https://gitlab.gnome.org/Mccalabrese/pitivi-timeline-ruler). This will be used to test the functionality of the widget and to ensure that it is working correctly before integrating it into Pitivi.

I am very excited to be working on this project and I look forward to sharing my progress with the community. I hope to learn a lot and contribute something meaningful to the GNOME ecosystem.
