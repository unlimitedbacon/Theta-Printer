Theta Printer
=============

The Theta Printer is a platform for printing with as many different materials as possible. Whether it be different colors of plastic, wood, carbon fiber, chocolate, or anything else you can make an extruder for. Each extruder moves simultaneously and independently, allowing the printer to lay down 4 different materials onto the same object at the same time. [See it in action.](https://www.youtube.com/watch?v=p_tqMAzWGm0)

![A magnificent rendering of the Theta Printer](http://i.imgur.com/bO3yb8Y.png)
[Full Size](http://i.imgur.com/XjrklZc.jpg)

With most 3D printers, adding more extruders makes the machine slower and reduces the build volume. The Theta Printer overcomes this by using polar coordinates. A polar printer works kind of like an old fashioned record player. Your objects are printed onto a platter which spins. The advantage is that you can have many print heads. Each extruder is on the end of an arm which swings in and out. The spinning platter is called the ϴ ("theta") axis and the swinging arm is called the R axis. Together these replace the normal X and Y coordinates you're used to. A polar printer has a couple of advantages over normal cartesian 3D printers.

1. Less moving mass means better acceleration
2. Finer resolution, especially near the center
3. Multiple toolheads without reducing build area

The spinning platform makes this machine ideal for integrating a 3D scanner. In addition, you can easily swap out an extruder for a mill or any other tool, making the Theta Printer the perfect all-in-one fabrication machine.

Specs
-----
+ 4 extruders for multiple colors and materials
+ 320 mm build platter
+ 80425 mm^2 print area (bigger than most repraps)
+ 0.084 degrees/step angular resolution (ϴ Axis)
+ 0.20 mm/step linear resolution (R Axis)
+ Now comes in two versions! The lasercut edition and the reprap edition (printed parts & threaded rods)

Links
-----
* [Development progress](http://forums.reprap.org/read.php?185,178379)
* [Videos](https://www.youtube.com/channel/UC-gtCzj4NQnUl9iEiGGx9JA/videos)
* [Firmware](https://github.com/unlimitedbacon/Marlin)

ϴ Axis
------
![A wooden disk, under which resides a complicated set of motors gears rods and bearings](http://i.imgur.com/seQVbID.png)
[Full Size](http://i.imgur.com/GR4uxWu.png)

Objects are printed onto a platter that spins back and forth. Its driven via a stepper motor and a large gear. Rollers support the platter around the perimeter and keep it level.

R Axis
------
![Four robotic arms arranged in a diamond shape](http://i.imgur.com/jy5FFq8.png)
[Full Size](http://i.imgur.com/bllIclA.png)

Four Extruders are each mounted on the end of an arm that swings in and out. The blue protractor things are gears for moving the arms.

Z Axis
------
![A set of four sprockets with the associated pulleys, motors, and drive belt](http://i.imgur.com/kKX2q1Q.png)
[Full Size](http://i.imgur.com/wnbYKVQ.png)

The Z axis is nothing new. Threaded rods in each corner are synchronized by a timing belt and driven by two stepper motors. 
