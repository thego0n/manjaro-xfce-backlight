# manjaro-xfce-backlight
commands to make the brightness work up/down on manjaro OS
]

xbacklight

Brightness can be set using the xorg-xbacklight package.
Note:
    xbacklight currently does not work with the modesetting driver [3].

To set brightness to 50% of maximum:

$ xbacklight -set 50

Increments can be used instead of absolute values, for example to increase or decrease brightness by 10%:

$ xbacklight -inc 10

$ xbacklight -dec 10
