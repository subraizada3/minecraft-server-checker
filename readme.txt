This script will check a Minecraft server's status and report the number of
  connected players. Additionally, it can run in the background and send you
  notifications when other players are playing.

================================================================================

Usage:

You must have Python 3 installed. At the top of the file, put in your server's
  hostname and port (you can use the domain name instead of IP address if the
  server has one).

In a terminal:

$ python3 minecraft.py check
Server Name: 2/20    (2 players are currently on, out of 20 maximum)

$ python3 minecraft.py
(this will run in background and send notifications when player count changes)

Or you can just double click the Python file to run it, which will start the
    background notification program.



================================================================================

On macOS, notifications are sent with the builtin osascript tool.
On Linux, the 'notify-send' tool is used for notificiations, but there's a high
    chance that you already have notify-send installed on your computer.
On Windows, this uses 'Notify-send for Windows' by Alexey Vaskovsky.
    http://vaskovsky.net/notify-send/
    https://github.com/vaskovsky/notify-send

================================================================================

This uses code from Nope's answer at https://gaming.stackexchange.com/a/166587,
  licensed CC BY-SA 3.0 (https://creativecommons.org/licenses/by-sa/3.0/).
Changes made to format of code, and extra features added as described above.
This code is also licensed CC BY-SA 3.0.

notify-send for Windows is licensed LGPL3.
