# SysMonScripts

To install fonts for all users, move .ttf font files to `` /usr/local/share/fonts ``

My setup is configured for triple monitors, so you will have to configure the ``gap_x`` (and possibly the ``gap_y``)variables in the rc files. This will change where the conky is displayed.

This is a fork of https://github.com/ragnarokxg/SweetDarkConkyReboot, with a few changes for my preferences.

To run conky scripts on startup, add ``conky -c "scriptname.rc"`` to xinitrc or to i3 config. 
