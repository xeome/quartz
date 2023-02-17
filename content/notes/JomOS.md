---
title: JomOS
date updated: 2023-01-22 02:00
---

## About

JomOS is an aggressively optimized meta Linux distribution designed for people who wants to get most out of their hardware. It allows users to mix-and-match well tested configurations and optimizations with little to no effort.

JomOS integrates these configurations & optimizations into one largely cohesive system.

## How does JomOS improve performance

We use tuned systctl values, udev rules and other configurations. We also provide a optimized repo with march=x86-64-v3 support (CachyOS repos) which comes with a notable performance boost. It depends on your cpu if it does support that, but you dont need to worry about it - the installer will detect the correct µarch and adjust to your system. Custom tuned kernel is also planned.
For more information refer to [[notes/JomOS Optimizations]].

## Screenshots

![[notes/assets/img/O_distro.png]]

## Credits

Huge thanks to Linux community and CachyOS team for some of the optimizations and general help.