# SPIKE FAQ

## What’s a Spike branch
A Spike branch is a version of Loop that allows you to use Spike as your CGM source.

## What branch should I use
That’s a very personal decision that only you can make. A Spike branch is the same as its original version, but with the added CGM option. Make your decision as you normally would with the LoopDocs, and come back here to find its Spike equivalent.

## Does the Spike branch have...
Probably. Updates to the Spike branches will usually happen within one week of an update to an official branch. See below for the corresponding update dates, and remember that you can always check if I’ve merged a specific Loop update by looking at the commit history in my repo.

<div>
<p> <b> Last master update : </b> <span class="master"> </span> </br>
<b> Last spike-master update : </b> <span class="spike-master"> </span> </br>
</p>
<p> <b> Last dev update : </b> <span class="dev"> </span> </br>
<b> Last dev-spike update : </b> <span class="dev-spike"> </span> </br>
</p>
<p> <b> Last automatic-bolus update : </b> <span class="autobolus"> </span> </br>
<b> Last spike-autobolus update : </b> <span class="spike-autobolus"> </span> </br>
</p>
</div>

## How do I install the Spike branch ?
Please check out [the LoopDocs](https://loopkit.github.io/loopdocs) for detailed, step-by-step installation instructions.

## Does Spike work offline
Yes.

## There’s a cloud icon though
I know, ignore it. That’s a relic of the Dexcom Share client, which the Spike client is based off of. The URL that the Spike client is pointed to is Spike’s internal HTTP server, so no internet connection is required. This is also why it’s so important that you enable your internal HTTP server in Spike’s settings.

## What’s my username & password
This is a relic of the Dexcom Share client. You can put in whatever fake username and password you want. It doesn’t have to match anything you’ve set anywhere else.

## What do I do if Spike is wrong
Open your loop immediately and close Spike completely. Continue with finger pokes and enter your BGs into Health, ideally every 15 minutes but personally if this happens to me I do it every half hour. Depending on the situation, either delete all calibrations in Spike and start over from zero once you’re in optimal conditions, or wait for optimal conditions to recalibrate. What are optimal conditions ? [Check out the calibration guide](https://andrei0105.github.io/spike-guide/calibration/). If you have lots of sensor noise, please discontinue the use of your current sensor and start a new one. If you cannot trust your CGM readings, then please do not use Loop, be it Spike or otherwise. Use all tools at your disposition to keep you / your loved one safe. This includes stopping the use of Loop until you can trust your CGM readings again.
