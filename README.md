leapLamp [![Build Status](https://travis-ci.org/xseignard/leapLamp.png?branch=master)](https://travis-ci.org/xseignard/leapLamp)
========

# Description

The idea behind this work was to explore how to interface Arduino with Leapmotion, and to see what would be the precision we could get with some basic servos.

Everything is surprisingly smooth. Except for the servo when the lamp goes up, because it's a cheap and weak one.

Since there is no lib to directly connect the Leapmotion to the Arduino, I used node.js to connect to the websocket server that streams the Leapmotion data and the johnny-five node.js lib to control the Arduino and the servos.

# How to run it
- Build the lamp!
- Upload the StandardFirmata to the Arduino (preferably version 2.2)
- Connect the Leapmotion and the Arduino
- Run the Leap websocket server
- Run `make run`


You can see a video here: https://vimeo.com/68530396

## License

(The MIT License)

Copyright (c) 2013 Xavier Seignard

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
