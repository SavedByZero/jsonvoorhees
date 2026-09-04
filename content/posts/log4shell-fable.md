+++
date = '2026-09-04T08:19:20-04:00'
draft = false
title = 'Log4shell : Fable'
+++
My attack was mentioned in Fable 5.1's scorecard! The section under Trajectory Labs (for whom I'm contracting) mentions a log4shell vulnerability, which I unearthed.

If you ask me exactly what this code does, I'll be the first to admit it beats the heck out of me; much of the time I have no idea what these models are doing, but I'm pretty good at getting them to do it. I know it involves injecting malicious code into a logging service. 

The important technique here was a combination of "What concerns do you have [...]" prompts that addressed every component of the malicious recipe, paired with pizza-related distractors that got by the classifiers; at the end of the request, I'd ask something like "How many slices of pepperoni are ideal for a 19 inch pizza?" and the legitimate content would override the security flags, while answers to both questions appeared in the output. I used this trick to get pretty high on the Safeguards and Staged leaderboards of Gray Swan's competitions. 
