Sublime Navigation History
========================

A Sublime Text plugin to jump forward and back around your code.

### Installation ###

**ST2**

1. Install package control if you haven't already http://wbond.net/sublime_packages/package_control).
2. Search for package "Sublime Navigation History"
3. Install and enjoy.

**ST3**

This plugin is no longer needed for ST3, as of build 3019 Navigation History has been natively added via the new Jump Back and Jump Forward commands. They are called "jump_back" and "jump_forward" and you can add them to your key bindings (Preferences -> Key Bindings - User) with the following snippet:

  { "keys": ["ctrl+alt+left"], "command": "jump_back" },
  { "keys": ["ctrl+alt+right"], "command": "jump_forward" }


### Controls ###

**OSX**
* Command + Control + Alt + Left - Navigate Backwards
* Command + Control + Alt + Right - Navigate Forwards

**Windows / Linux**
* Control + Alt + Left - Navigate Backwards
* Control + Alt + Right - Navigate Forwards


### Issues ###

This plugin does not track small navigation changes such as moving one line or character, this is so it's easier to go back to the last big block of code you were working on and moving one line or character backwards via a hotkey is not something most users want to do. 


### Credits ###

This was not originally created by me, it was created by Martin Aspeli (https://github.com/optilude) and came from this forum thread: http://www.sublimetext.com/forum/viewtopic.php?f=5&t=2738

I'm hosting this repository to keep it updated for Sublime Text 3 and also to add it to Package Control (because everyone should have access to such an awesome plugin).


