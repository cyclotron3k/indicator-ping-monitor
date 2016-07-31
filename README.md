# indicator-ping-monitor
An indicator for Ubuntu which monitors internet connectivity

Running this indicator adds a traffic light indicator to the indicator system tray. It pings the specified host every two seconds and displays the result.

Can be run directly with ruby, but you'll probably want to move it to somewhere like `/usr/local/bin`, `chmod` it to executable, and add `indicator-ping-monitor.desktop` to `~/.config/autostart/`
