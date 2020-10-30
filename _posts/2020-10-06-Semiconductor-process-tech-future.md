---
layout: post
title: Future of Semiconductor Process Tech
categories: Semiconductors
---

There was a recent announcement by TSMC at its 2020 Virtual Technology Symposium about its [3nm risk production](https://www.anandtech.com/show/16024/tsmc-details-3nm-process-technology-details-full-node-scaling-for-2h22) and [2nm node research and development](https://www.extremetech.com/computing/309889-tsmc-starts-development-on-2nm-process-node). It took me a moment to process how far we have been pushing silicon scaling. After all those years of being told that Moore's law was ending and silicon scaling would stop, are we still scaling? How has our assumptions of Moore's law changed? What lies ahead for us?

# Moore's Law : Past and Present
## Historical Definition and Interpretations
![Microprocessor Trend](/images/uProcTrend.png)

In the above image, let us focus on the transistor count shown by the red circles. We see the basic statement of Moore's law in action i.e. transistor count doubles ever 2 years. For 35 years, this "law" has held true. A few things to note here about the "law":
* Moore's law is not really a law, it was just an observation Gordon Moore made at the early onset of transistor scaling. 
* For a larger percentage of the 35 year trend, companies have aspired and worked to match Moore's law (and to significant success). They have in fact used this observation to guide development of new nodes. Such R&D has taken significant effort and research to keep the "law" intact.

Moore's law has been interpreted in multiple forms, based on the context in which it is used. One can also think of these as "implications" of Moore's law. The main implication, which forms the driving force of Moore's law, is the following:

> Transistor size shrinks (scales down) 0.5x every 2 years.

In other words, the size of a chip being constant, by reducing the size of the transistor by 0.5x, we can double the number of transistor. This is why we have the massive effort to keep transistor scaling alive!
What other implications do we have?
* **Power** : When transistors scale due to Moore's law, the power density of the chip remains constant given the same area because each transistor now consumed 0.5x the power. (Also called Dennard Scaling)
* **Economic** : The cost per transistor reduces by a factor of 0.5x every 2 years since we can buy the same chip with twice the number of transistors every 2 years.   

Different people and fields used these interpretations. For example, until recently, digital designers and architects assumed that they could double the number of transistors on the chip for the same power budget. Additionally, business units often thought that they could sell a chip 2 times as powerful every 2 years (due to doubling of number of transistors) for the same cost, thus gaining at least a 2x performance boost for free.

We will explore these implications in detail in a few sections and see whether they still hold true. First, let us understand what scaling a transistor even means.

## What does scaling a transistor mean?
![Transistor Trend](/images/TransistorScaling_Length.png)
A transistor is fundamentally, in logic terms, a switch controlling the flow of current from the "Source" to the "Drain". The "switch" part of the transistor is called the "Gate". 
When we say the transistor becomes half its size, we are referring to its gate length, as seen in the above picture. We want to make the gate as thin as possible to reduce the form factor of the transistor in order to increase the transistor density on die.

What we can also infer from the picture above that there is a certain limit upto which the gate can be scaled down. 







