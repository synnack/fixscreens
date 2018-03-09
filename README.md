# fixscreens
Because mate-settings-daemon and gnome-settings-daemon don't get it right..

Be sure to run fixscreend at startup applications in the session (System -> Preferences -> Personal -> Startup Applications (mate-session-properties or gnome-session-properties).

Also disable xrandr plugin for gnome / mate settings daemon: 
1. Start dconf-editor
2. Browse to /org/mate/settings-daemon/plugins/xrandr.
3. Set active to false


Also, the priorities should be adjusted to the configuration of your screens/laptop CRTCs.

