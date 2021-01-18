# manjaro-xfce-backlight
Commands to make the brightness work up/down on manjaro OS. 

Alot of people have been having problems with brightness settings of manjaro after kernel updates.
This may work as a temporary solution for some users.


xbacklight 

Brightness can be set using the xorg-xbacklight package.
Note:
    xbacklight currently does not work with the modesetting driver [3].
    
    //COMMAND MUST BE RAN AS ROOT***

To set brightness to 50% of maximum: 

sudo xbacklight -set 50

Increments can be used instead of absolute values, for example to increase or decrease brightness by 10%:

sudo xbacklight -inc 10

sudo xbacklight -dec 10
