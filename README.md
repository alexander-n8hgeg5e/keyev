=================
# keyev/mouseev #
=================
Keyev is a key-event forwarding/proxy program.
The purpose is to get __MULTIHEAD__ functionality.
The program forwards keyevents and mouse/pointer
events to other x-servers.
So it is possible to get more monitors
attached to your computer than it has monitor
connectors or graphic-card slots.
The functionality is like the program "synergy" but
only for x-servers.
Because it's a simple python script it's easy to
customize.
It turned out that the speed and the
responsiveness is really good.
It is possible to navigate over many monitors.
They can be horizontally and/or vertically alligned/stacked.
The configuration is in the code for know.
The vertical stacking is not done, but this
should be easy.

# STATE #
=========

The state is testing/very unstable.
The keyboard file is somewhat clean.
The mouse file needs heavy cleanup.

# Requirements #
================
    * some x-servers that can be reached via Xlib/network
    * env variable 'screen_layout' describing the layout and
        containing the addresses of the x-servers
    * XInputExtension
    * XTestExtension
    * python3
    * pylib (from my github page)
    * python-xlib (python only xlib implementation)
