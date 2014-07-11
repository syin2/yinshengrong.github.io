---
 layout: post
 title: Limitations for dualband testing experiment
---

I was thinking about the dualband testing experiment when I READ [this paper](http://www.mit.edu/~swarun/papers/lteye-sigcomm2014.pdf). The goal is to try to measure all the channels at the same time, but only two channels can be measured simultaneously on the platform. We have one band for 10 channels, another band for 16 channels. In this channel. each time we can choose one from the ten, and one from the 16. If we scan from all the choices, we can have 160 options. Each could use up 24 hours. That should be 160 days consistently. The issue is how we make the experiment controlled, and in level we will consider it as the controlled experiment.

The paper did a survey from the PHY label for the LTE performance with AT&T and Verison.