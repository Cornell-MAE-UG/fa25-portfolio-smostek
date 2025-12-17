---
layout: project
title: Boeing Analysis
description: MAE 4300 Project Writeup
technologies: [N/A]
image: /assets/images/Boeing.png
---

On 29 October, 2018, Lion Air Flight 610, carried by a Boeing 737 Max 8, crashed off the coast of Java.

On 10 March 2019, Ethiopian Airlines Flight 302, also carried by a Boeing 737 Max 8, crashed within minutes of takeoff from Addis Ababa.

In the last 20 years, there have been 330 deaths on commercial airline flights in and around the US. These two Boeing crashes, which occured within 6 months of one another, resulted in 346 fatalities.

How do such tragic mistakes occur? As with most things resulting from human action, the answer is that a large effect was generated from the combined effect of myriad small decisions.

#### History
In 2010, Airbus released the A320neo, delivering significant fuel efficiency benefits -- a benefit not only to the environment but also to airlines' fuel costs -- and consequently placing pressure on Boeing to deliver a competitve design. The result was the 737 Max.

Within aviation design, the general trend is for larger engines to be more efficient -- they require less pressure to generate the same amount of thrust force. The tradeoff of course, is that larger engines weigh more and create more drag. So as knowledge of aerodynamics and structural mechanics has grown, so too have airplane engines.

Separate from this engineering problem is an economic problem: Boeing's marketing team had promised the upcoming designs would not require any new pilot simulator training, going so far as to offer Southwest a million dollar rebate on each plane if they it did. This was done to ensure that airlines wouldn't pivot to Airbus while Boeing caught up.

Here, then, is the needle Boeing engineers were tasked with threading: fit a larger engine onto an existing chassis without changing the plane's flight characteristics.

In order to fit the new engine onto the old wing, the engineers moved it forward, which shifted the plane's balance and flight characteristics. Mission accomplished. But the engineers were clever: they could fix the problem with software -- always a reassuring strategy. Borrowing an existing system from the military arm of the company, a pitch correction system called MCAS was added to the 737. 

To make a long story short, as development continued, Boeing consistently ignored red flags and even expanded the operational window of MCAS, with the ultimate effect being an enourmous single point of failure: should a single sensor fail, the computer, thinking the plane was about to stall, would aggressively pitch the plane down. When this happened during takeoff, there was not enough time for pilots to correct the computer, leading to the two tragic crashes.

#### Systemic Failures
A couple important questions remain from the story as told: 1, why wasn't the addition of MCAS flagged by regulators; 2, why weren't pilots retrained on this new system? Both of these questions lead to the same root answer: deregulation. For a long time now, the prevailing attitude in Congress towards the federal bureaucracy has been a mix of a neoliberal disgust combined with a begrudging recognition of its necessity. The result, true generally but relevant only specifically, is that the Federal Aviation Administration (FAA) has seen a steady decline in its funding, and thus has had to get creative with its resources. As its bandwidth decreased, the FAA relied more and more on delegation, a technique originally intended for superfluous design elements whereby Boeing employees would represent FAA interests.

This is how MCAS flew under the radar (pun not intended). The certification of MCAS was delegated to Boeing, so the FAA never learned about the true scope of its control, and with regulators out of the loop Boeing could claim to airlines that its new planes didn't introduce any new systems on which pilots needed to be trained, thereby saving money and reputation.

#### Lessons
In my mind the most significant detail in the making of this crisis -- a necessary if not sufficient component -- is the expansion of FAA delegation to design-critical elements. As already hinted at, the roots of this issue trace back to the neoliberal fascination with deregulation that took permanent hold under Reagan. In this framework, Boeing's stagnation and ultimately deadly blundering is categorically indistinct from the series of profit-driven blunders that caused the Great Recession a decade prior. In both cases, the frustrating truth is that the decade's long chain of decisions which culminated in crisis serves to diffuse and muddy the question of blame; each of the major actors were acting rationally, if not cautiously, in response to the set of incentives presented by the system.

It would be tempting, then, to frame the failure as one of individual responsibility: individual Boeing engineers should have recognized the danger and spoken out. But even setting aside the fact that such objections were made but simply ignored, that's far from a reliable system to increase consumer protections. To be sure, stronger whistleblower protections could hardly hurt, but that should be the last line of defense. Had a whistleblower spoken out in this case, many lives may have been saved, but it would only delay the crisis without affecting the warped incentives that caused Boeing to value marketability over truth and safety.
