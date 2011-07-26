FlippyNum
========

FlippyNum is a basic flip counter animator.

Usage
-----

To generate, just call the flippyNum function with the dom element that you want it appended to as the first parameter.

	<div id="flippy"></div>

	// call the flippyNum function
	flippyNum(document.getElementById('flippy'));
	
Options
-----

FlippyNum accepts an options object as it's second argument. Below are the available options:

**imagePath** *string* Location of sprite to use for numbers
`"imagePath: 'flippyNum.png'` Default

**width** *integer* Width of each number in pixels
`width: 29` Default

**height** *integer* Height of each number in pixels
`height: 40` Default

**digits** *integer* How many digits to the left of decimal point to include
`digits: 6` Default

**startNumber** *integer* What number to start counter at
`startNumber: 0` Default

**endNumber** *integer* Number to stop counting at
`endNumber: 0` Default

**duration** *integer* How long it should take to get from the start number to the end number, in ms
`duration: 9000` Default

Public Methods
-----

FlippyNum comes with two public methods for easy adjustment of numbers after initial load:

**flipTo(num)** 
num is an integer to automatically flip to (at originally set duration)

**addOne()**
adds on to current number

Supported Browsers
------------------

  * Firefox 3.5+
  * Google Chrome
  * Internet Explorer 7+
  * Safari 3+
  * Mobile Safari
  * Android

Other browsers probably work, but I haven't tested them.

License
-------

Copyright (c) 2011 Donald Cook (donald.cook@dachisgroup.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
