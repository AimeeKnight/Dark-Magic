### Title
It's Not Dark Magic - Pulling Back the Curtains From Your Stylesheets

### Description
All too often developers are left completely puzzled when the browser renders CSS in ways they didn’t expect. It’s not dark magic though and as developers, we know that computers are just parsing our instructions. While many talks discuss how to fix common bugs, this talk will focus on the why by taking a deep dive into browser internals to see how our styles are parsed and rendered.

### Notes
Chances are if you're a web developer you're going to have to write some CSS from time to time. When you first looked at CSS it probably seemed like a breeze. You added some border here, changed some colors there. JavaScript was the hard part of front-end development! Somewhere during your progression as a front-end developer that changed though! What's worse is that many developers in the front end community have simply learned to dismiss CSS as a toy language. The truth, however, is that when we hit a wall many of us don’t actually understand what our CSS is doing under the hood!

We all like to make jokes about it, but how many of us have actually taken the time to try and understand the CSS we're writing. How many of us have actually reasonably debugged an issue to the next lowest abstraction layer when we hit a wall? All too often we settle for the first StackOverflow answer, hacks, or we just let the issue go entirely.

In this talk, we're going to finally take a step back and stop mindlessly throwing darts at the dartboard! We’ll discuss the most common issues developers face such as, z-index, the cascade, and positioning in depth by diving deep into the browser's internal rendering engine structure to see how our styles are actually parsed. Sure, you may still not have an eye for design, but you might just walk away a CSS guru!
