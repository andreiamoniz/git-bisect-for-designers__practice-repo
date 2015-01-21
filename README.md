# git bisect tutorial

### What is this?
This is the follow up for a presentation given at a Booking.com Design Jam, "git bisect for Designers." We needed a practice area for everyone to work with, outside of our internal code systems...so I've made this.

### How to use it?
**Only works in Google Chrome...right now**

There are a few bugs introduced throughout this very short amount of git commits. The point is to fix each one, individually, using git bisect. The bugs are as follows:

	1. L has a spelling error.
	2. The background should be red.
	3. Z has a spelling error.
	4. Font color should be white.

### git bisect Tutorial

	1. Start with <git bisect start>
	2. Follow by <git bisect good>
	3. For each situation of 1 - 4 you can use quite a few SHAs. 
		- 26 letters: 3e45947b02c79a11d952aa3932a6e5aff510e2bd
		- 9531c8eab34fb25770c61f2d8cb0c82ee36bd73b
		- First commit: 4b1635cdf333ee497eb1456cc53a03105f30873d
	4. Choose which SHA is needed, run <git bisect bad SHA>
	5. Follow through until end for each scenario.


### This is pretty much it. Tweet me at @elnatnal or email me at jonathan.stephens@booking.com to check the answers of 1-4. If you work at Booking.com, feel free to send me a Jabber.
