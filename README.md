Digital Clock — JavaScript

A real-time digital clock built with HTML, CSS, and JavaScript, styled as a retro LED clock-radio. It displays the current hours, minutes, and seconds and updates automatically every second — no page refresh required.

Live Demo

https://shadow12546-sketch.github.io/digital-clock/

Features


Displays real-time hours, minutes, and seconds in 12-hour format with an AM/PM indicator
Automatically updates every second using setInterval() — no page reload needed
Shows the current day, month, and full date above the time
Blinking colon separator between hours and minutes for an authentic digital-clock feel
Fully responsive layout that adapts down to mobile screen widths
Retro clock-radio aesthetic with glowing LED-style digits, built entirely with CSS gradients and text-shadow (no images or external assets)


Technologies Used

TechnologyPurposeHTML5Structural markup for the clock-radio body, display panel, and time/date elementsCSS3Retro LED styling — gradients, glow effects, rounded panel edges, decorative dials, responsive breakpointsJavaScript (ES6)Reads system time via the Date object, formats it, and updates the DOM every second via setInterval()

How It Works


Date() is used to read the current system hours, minutes, seconds, day, month, and date.
Values are formatted (zero-padded, converted to 12-hour format, AM/PM calculated).
The formatted values are written into the DOM using textContent.
setInterval(updateClock, 1000) re-runs this process every second, keeping the display live.
