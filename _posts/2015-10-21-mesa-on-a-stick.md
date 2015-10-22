---
layout: post
title: MESA-on-a-stick
---

For all those who have thought that MESA was just too hard to install even with the SDK (or your unlucky and only have a Windows machine available), then the solution for your worries is here:

MESA-on-a-stick

This is a complete live linux distribution which has MESA pre-installed (r7624). No ./mk or ./clean needed, no initializing the SDK and no setting paths. MESA should just work.


It comes as a disk image that can either be burned onto a usb stick allowing you to reboot into a full linux distribution (without having to install linux on your machine) or if you have virtual machine software installed (like qemu or virtual box ) then you can load it up inside the virtual machine and no reboot needed (no usb stick needed either).

The disk image can be found here:

https://www.dropbox.com/s/cxsdww393w20p0q/MESA.iso?dl=0 (1.3GB in size)

and instructions for running it can be found here:

https://github.com/rjfarmer/mesa-on-a-stick

So i'm looking for anyone who would be willing to test this out and provide feedback on whether they can get it work, on the instructions, on whether there are additional packages you would like see shipped with this as well as any other feedback. Going forward I'd see this being useful for those who are teaching students who are less technically able and may only have a Windows machine available. So feedback on things that would help in classroom settings is especially appreciated.

