# Conference-Clock
Countdown conference clock in html

The purpose is to make a countdown timer for conference use. I borrowed the idea from TED talks.

The result is a webpage programmed in html+javascript called
`clock.html`.

You can download it by [this link](http://wpregliasco.github.io/clock/clock.html).

It looks pretty well in a fullscreen navigator. I don't know how to make a fullscreen in an android navigator, but also works reasonably. Do no forget deactivate screen sleep during the use. (if this is the case, the program continues working ok).

You can download the webpage to your machine or click the links below.

Feel free of use it, modify or comment.

## Working

When you load the page, a digital clock appears with mins and seconds.

Clocks begins stopped. When stopped, numbers are brilliant yellow. You can stop or continue countdown by either clicking the mouse or pressing any key. In  touchscreen device you can touch the screen. 

Clock countsdown up to zero, where remains blinking. You can stop in that state and with a new click, reset the count to the inicial value, ready for a new beginning. 

With the default values, countdown begins with bright numbers, but when remains 20 minutes numbers change to light red, and when remains 5 minutes numbers change each second between red and magenta. 

## Time values

You can set three times:
* `min`: total countdown time, in minutes (default:45)
* `mid`: change color time, in minutes (default:20)
* `end`: final blinking time, in minutes (default:5)

These values can be changed by three ways:
1. editting the file, 
2. through variables in the URL:
```url
http://clock.html?min=15&mid=5&end=1
```  
If you omit any of the parameters, it wil take the default value.  
3. Using any of these links:  

| link   | min | mid | end |
|---|---:|---:|---:|
| [1 hour](http://wpregliasco.github.io/clock/clock.html?min=60&mid=30&end=10) | 60  | 30 | 10|
| [45 min](http://wpregliasco.github.io/clock/clock.html?min=45&mid=20&end=5)  | 45  | 20 | 5 |
| [30 min](http://wpregliasco.github.io/clock/clock.html?min=30&mid=15&end=3)  | 30  | 15 | 3 |
| [15 min](http://wpregliasco.github.io/clock/clock.html?min=15&mid=06&end=2)  | 15  | 6  | 2 |
| [10 min](http://wpregliasco.github.io/clock/clock.html?min=10&mid=5&end=1)   | 10  | 5  | 1 |


I hope this will be usefull for talkers and organizers. Comments welcome. 

Willy Pregliasco
