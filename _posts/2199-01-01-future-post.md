---
title: 'Blog Post 8'
date: 2026-04-19
permalink: /posts/2026/04/blog-post-8/
tags:
  - Electronic Integrations
  - Control Programming
  - Emergency System
  - Load Reduction
---
Hi again, as the end of the semester approaches, the Coogineers have been pushing hard toward bringing the whole system together ranging from last minutes machining to reduce load, to troubleshooting programs and refining program sequencing. Here, we present to you the current status of our AMOFT. 

## From Parts to Prototype 

Over the last three weeks (March 30 to April 19), our biggest milestone was reaching first full prototype assembly of the AMOFT and bringing its core controls and safety hardware together into one working system. Earlier in the semester, much of our effort was focused on machining, wiring, and getting subsystems ready on their own. Over the past few weeks, those separate pieces finally came together into a single prototype that now looks and functions like the device we have been designing toward all year. We completed the mechanical assembly, installed the winch cable, finished the main wiring organization, and added the hardware needed to begin controlled motion and safety testing.

![AMOFT](/images/blog8-1.png)

This stretch of the project also included several smaller but important pieces that made the prototype much more usable. We designed and 3D printed a remote control box so the system can be operated more cleanly during testing, with dedicated RUN, STOP, and RESET controls along with status lights. We also installed two limit switches and built mounting brackets for them so the machine can recognize its travel boundaries. These additions moved the project beyond a partially assembled mechanism and closer to a real operator-controlled system. By the end of this period, the prototype was no longer just a collection of fabricated parts and loose electronics. It had become an integrated bench-top machine with a defined structure, organized controls, and the basic features needed for safe operation.

![AMOFT](/images/blog8-2.png)

A nice way to close out this phase was being selected to showcase the project at the UH Energy Industry Crawfish Boil on April 19 as part of the student Capstone showcase. The event brought together students, faculty, alumni, and industry professionals, so it gave us a chance to explain the problem our device solves and show how far the prototype has come. After spending most of the semester building and troubleshooting, being able to present the AMOFT in that setting made this milestone feel especially meaningful.

![AMOFT](/images/uhcf.png)

## From Assembly to Safe Operation

Over the past few weeks, we moved beyond just assembling the AMOFT and began testing whether some of its most important safety and control features actually work the way we intended. 

One of the first systems we checked was the emergency stop. To test it, we triggered the E-stop while the machine was in motion and observed how the system responded. In each trial, motion stopped as intended, power to the moving components was removed, and the machine stayed in a safe condition until it was manually reset. After resetting, the system was able to return to operation without any rewiring or hardware changes. This was an important step because it showed that the prototype already has a reliable baseline safety function in place.

We also tested the limit switches that define the machine’s travel boundaries. These switches are meant to prevent the mechanism from moving too far and causing damage or unsafe motion. We repeatedly commanded the device toward its end positions and confirmed that the switches activated where they were supposed to. During these trials, the switches consistently detected the correct positions and stopped further motion beyond the intended limits. This gave us confidence that the prototype can now recognize and respect its safe operating range.

In addition, we verified the remote control box by checking the RUN, STOP, and RESET buttons. Each control responded correctly during operation. 

At this stage, we are glad to see that the prototype has reached integrated assembly and that core safety/control functions are working. However, we are not yet satisfied with final performance validation because positional accuracy, repeatability, and total cycle time have not been fully verified.

## From Working to Proven

Now that we have confirmed the basic safety and control features are working, our next step is to see how well the prototype performs against the goals we set at the start of the project. 

The biggest item still ahead is position testing. We are waiting on new proximity sensors so we can measure how accurately the system returns to its target locations. That testing will show us whether the automated motion is landing where it is supposed to each time, not just moving in the right general direction.

We also still need to check how repeatable the motion is over multiple cycles. We want to know whether the system can perform the same sequence again and again without drifting, missing positions, or gradually becoming less consistent. A system that works once is a good start, but for this project to be successful, it needs to behave reliably over repeated use.

Another major item still to be verified is total cycle time. One of the main reasons for building this device was to reduce dependence on manual handling and make the process more consistent and efficient. Because of that, we still need to measure how long a full automated cycle takes and compare that result to our project target. That will help us judge whether the prototype is not only functioning, but actually improving the process in a meaningful way.

As we finish these last rounds of testing, we will use the results to make final adjustments to the programming, sensor setup, and motion sequence where needed. Our goal for the remaining time is to move from a working prototype with proven safety features to a prototype that also has clear performance data behind it.

Shown below is the current working draft of our technical poster for the AMOFT project. It highlights the problem background, design process, prototype status, and current validation progress, and it will be updated as final testing and presentation preparation continue.

![Poster](/images/Slide1.PNG) 
