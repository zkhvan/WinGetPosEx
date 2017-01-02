# WinGetPosEx
A "fork" of a post that can be located
[here](https://autohotkey.com/boards/viewtopic.php?f=6&t=3392). The code in
this repository is the alternative version (refomatted) by the user *Skrell*
from the forums
([post](http://ahkscript.org/boards/viewtopic.php?f=6&t=3392&start=20#p19097)).

## Introduction
With the introduction of the Desktop Window Manager (DWM) and Aero themes in
Windows Vista, the size and position of windows has never been the same. The OS
says that the window is one size but when displayed, the window can be another
(usually larger) size. The `WinGetPosEx` function is an attempt to help the
developer to identify the correct position and size of a window regardless of
window attributes, desktop theme, or version of Windows.

## Key Features

- Actual dimensions. Get the actual position and size of a window.
- Offset values. If the window is a different size than reported by the OS,
  offset values are returned to assist the developer to set the position of the
  window.

## Issues / Considerations

- **Preview**. Yes, this still a preview release.
- **Compatibility**. This function was designed to run on Windows 2000+ and on
  all versions of AutoHotkey. Although I've tested it on most versions of
  AutoHotkey, I only have a Windows 7 box to test on. I have no idea if this
  will work correctly on any other version of Windows. If you find any bugs or
  have any compatibility problems, please let me know.
