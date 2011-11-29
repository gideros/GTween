GTween for Gideros
This code is MIT licensed, see http://www.opensource.org/licenses/mit-license.php
Copyright (c) 2010 - 2011 Gideros Mobile 

Based on GTween 2.01 for ActionScript 3
http://gskinner.com/libraries/gtween/
GTween 2.01 for ActionScript 3 is MIT licensed, see http://www.opensource.org/licenses/mit-license.php
Copyright (c) 2009 Grant Skinner

**Notes:**
* Documentation is derived from GTween 2.01's original documentation.
* Plugins, GTweenTimeline and proxy objects are not supported.

GTween is a light-weight instance oriented tween engine. This means that you instantiate tweens for specific purposes, and then reuse, update or discard them. This is different than centralized tween engines where you "register" tweens with a global object. This provides a more familiar and useful interface for object oriented programmers.

GTween boasts a number of advanced features:
- frame and time based durations/positions which can be set per tween
- simple sequenced tweens using .nextTween
- pause and resume individual tweens or all tweens
- jump directly to the end or beginning of a tween with :toEnd() or :toBeginning()
- jump to any arbitrary point in the tween with :setPosition()
- complete, init, and change callbacks
- smart garbage collector interactions (prevents collection while active, allows collection if target is collected)
- easy to set up in a single line of code
- can repeat or reflect a tween a specified number of times
- deterministic, so setting a position on a tween will (almost) always result in predictable results
