delay.css
=========

Delay CSS3 animations form starting on page load, works great with [Animate.css][1] and [wow.js][2] 


Getting started
---------------

To use delay.css in your website, simply drop the stylesheet into your document's <head>

    <head>
      <link rel="stylesheet" href="delay.css">
    </head>

Add the correct class to any animated object to delay it.

    <div class="animated fadeInUp delay0s5ms animated"></div>

Classes are made of 
'delay' - Fixed begining of class name
'0s' - Number of seconds of delay 
'5ms' - Number of miliseconds of delay

So all togeather you get delay0s5ms

That's it! You've got the power to delay CSS elements from animating. Now go have fun! 


  [1]: https://github.com/daneden/animate.css
  [2]: https://github.com/matthieua/WOW
