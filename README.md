robot-sandbox
=============

Robot arm simulator with rigid body dynamics

WINDOWS: unzip and run 

LINUX: difficult (need help for packaging)

Demos
=====

[belt1]: http://github.com/downloads/alexdu/robot-sandbox/screenshot-conveyor-belt-1.jpg
[belt2]: http://github.com/downloads/alexdu/robot-sandbox/screenshot-conveyor-belt-2.jpg
[draw-rose]: http://github.com/downloads/alexdu/robot-sandbox/screenshot-robot-drawing-rose.jpg
[hanoi]: http://github.com/downloads/alexdu/robot-sandbox/screenshot-hanoi-towers.jpg


Towers of Hanoi
---------------

    env hanoi
    load hanoi
    exec hanoi_main

![Robot solving Towers of Hanoi][hanoi]


Conveyor belt
-------------

    env belt
    load belt
    exec belt

![Conveyor belt demo 1][belt1]

Another conveyor belt example
-----------------------------
    env ex2005
    load rez2005
    exec rez2005

![Conveyor belt demo 2][belt2]


Robot drawing
-------------
... using a ballpoint pen and paper

    env desen
    load desen
    exec rose(3,2)

![Robot drawing a rose curve][draw-rose]
