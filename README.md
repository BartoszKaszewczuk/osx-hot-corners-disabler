![Hot Corners Disabler](http://cl.ly/image/1c1a0d3e1V1v/hot-corners-disabler.png)

Hot Corners Disabler
========================
By Bartosz Kaszewczuk

What is it?
-----------
Hot Corners Disabler is an AppleScript wrapper that disables hot corners while certain app is running. It is especially useful for running fullscreen apps, such as games, in multi-monitor setups.

How do I use it?
----------------
Using Hot Corners Disabler is super easy.

1. Start **Automator**.app
2. Select **Application** in document type window
3. Find **Run AppleScript** in Actions Library pane
4. Paste in the code
5. Change path to point to the app you want to run with disabled hot corners and viola!

Like so:
```applescript
...
set appStaticPath to "/Applications/.League of Legends.app/Contents/LoL/RADS/projects/lol_launcher/releases/0.0.0.97/deploy/LoLLauncher.app"...```
Can I customise it?
-------------------
Of course! Do whatever you want! You can even add an icon to make this wrapper look badass.