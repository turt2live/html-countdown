# html-countdown
An offline-capable HTML configurable countdown clock (intended for conference timers)

How to use:

1. Copy `countdown.html` to where you want this hosted.
2. Open that page.
3. Start typing a time with the number keys
4. Enter or Space to start/pause (or just hit F5 to reload the page)

If you're using a pi for this:

1. Create the directory `/home/pi/.config/autostart`
2. Put the following into `/home/pi/.config/autostart/autochrome.desktop`:
   ```
   [Desktop Entry]
   Type=Application
   Exec=chromium /home/pi/Desktop/startup.html --start-fullscreen
   ```
3. Put the contents of `countdown.html` into `/home/pi/Desktop/startup.html`
4. Reboot your pi
