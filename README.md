SleekoCommander
===============

My entry for aisandbox.com's Capture the Flag tournament.

Note that this script is exactly how I submitted it.  It's more or less what I submitted at 4 AM just before the Phase #1 deadline.  As such, it's very messy and my goal is to clean it up and make it more pythonic.

Currently, the commander creates two bot classes:  runners and defenders.
* Runners are fairly stupid at this point, but generally take side routes while attacking the flag.  They currently do not learn.
* Defenders are intelligent, however.  Defenders will search for tiles in a radius equal to the firing distance around the flag stand for optimal hiding spots.  This saved my commander many times during Phase #1.  Unfortunately, due to nerfs to defense, defenders became less effective during Phase #2.

I've decided to license this under GNU GPL-3 unless somebody has a better alternative.  http://www.tldr.legal.com/l/GPL3
