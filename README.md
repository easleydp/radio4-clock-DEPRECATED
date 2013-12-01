radio4-clock
============

Radio 4 Today Programme clock

To incorporate in a web page simply include the today-clock.js script and two div elements – one with the today-clock class and the other with the today-tell-time class – sized and arranged to suit your design. (In fact, there are no dependencies between the two clock components and either can be omitted.) On load, the script populates any div that has the today-clock class with an analogue clock and populates any div that has the today-tell-time class with a 'tell time' clock. Both clocks auto-size to fill the containing div (even dynamically if the containing div is resizable, although the current implementation depends on a window.resize event). However, the analogue clock will always maintain a 1:1 aspect ratio no matter what the aspect ratio of its containing div. The 'tell time' clock will stretch to match the size of its container div but looks best with an aspect ratio of 3:1.

Supported browsers: Uses the HTML5 canvas element. Should work in any modern web browser and may work in IE9.

Accuracy: The clock simply echoes that of the client machine. Where ultimate precision is needed (as in the Today studio) the computer's clock should be synchronised with a reliable time server, such as ntp2d.mcc.ac.uk

today-clock.js depends on JQuery. A copy of jquery-1.4.2.min.js is included. Alternatively, include this script tag in your HTML file:
  <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.2/jquery.min.js"></script>

