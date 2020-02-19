# bmpanel1 - modified
A stripped down version of bmpanel version 1.

All credits to the original author nsf <no.smile.face@gmail.com> .

This version doesn't have: clock, tray.
This version have: taskbar, desktop switcher (not enabled in the darkmini theme).
It is shipped with the darkmini theme, which is also the default one.
Custom themes must be copied in HOME/.config/bmpanel/themes .
This program is fully compatible with all the themes created for the original 
bmpanel 1 except for clock and tray.

Requirements:
 - imlib2
 - freetype2
 - Xlib
 - XRender
 - XComposite
 - Xfixes
 - fontconfig
 - make and gcc

Install:
./configure && sudo make install

Running:
bmpanel
