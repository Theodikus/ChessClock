# ChessClock
Chess clock web application

Thanks for taking the time to read my documentation!

The instructions specified that there should be one HTML index file for you to load, so I wrote the JavaScript right 
inside the HTML. It's not very much JavaScript.

-----------------------------

4 functions: 

* init - initializes the game; also used to reset the clocks either manually or by loss of time
	
* getTime - formats the remaining time into an appropriate string, ie. [MM:SS]

* takeTurns - swaps the owner of the turn. If it's White's turn, turn on flags for White and turn off flags for Black;
  if it's Black's turn, then vice - versa.

* elapsed - Determines which player flag is true and elapses time for that player until the flag flips.
  If either counter reaches zero, an alert is called, then 'init()' is called to reset the clocks.

-----------------------------

I hope you found my code pleasant to read - or, at the very least, legible. 
Thank you for your time and attention. 

Cheers!

Alexander Mahterian
