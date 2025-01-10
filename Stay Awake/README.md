The intent of the .py file in here is to keep your computer from timing out on network and/or going to sleep.

The first thing you need to do is download the files to somewhere on your computer and ensure you have the packages in requirements.txt if you are going to use the system tray icon rather than taskbar icon.
Once complete, the next thing to do is adjust the Stay Awake.bat file and point it to your installation of Python along with the path to the Stay Awake.py file.

Within the .py file, there are some different parameters at the top you can adjust.
It's set up to press the Num Lock key on they keyboard to stay awake. However, there's also an option to just move the mouse instead.

Lastly, get Windows Task Scheduler to execute the .bat file for you on days you want it to. The .py will run in a minimized window, and will also display some running text.
Because there's a start/end time parameter, it'll shut off by itself or you can press Ctrl+C on the .py window to stop yourself.
