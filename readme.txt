Wiim Now Playing (Go Version)
==============================

A lightweight desktop application that displays "Now Playing" information from
Wiim/Linkplay audio devices on your local network.

This is the Go version - compiles to a single .exe file with no dependencies.


Features
--------
- Automatic device discovery via SSDP/UPnP
- Album art display with fallback to iTunes artwork
- Playback controls (play/pause, previous, next)
- Device switching when multiple Wiim devices are found
- Auto-selects Wiim Ultra if multiple devices are present
- Fullscreen mode (F11 or ESC to exit)
- Dark theme UI
- Single .exe file - no installation required


Requirements
------------
For running:
- Windows 10/11
- Wiim device on the same network


Keyboard Shortcuts
------------------
Playback (works in all modes):
Space   Play/Pause
Right   Next track
Left    Previous track

Fullscreen:
F11     Toggle fullscreen
ESC     Exit fullscreen
1       Full view (title, artist, album, progress)
2       Title + progress
3       Art + progress
4       Art only (maximum size)
5       Art + corner text (title, artist, album in bottom-right)
9       Help screen

Note: Fullscreen view mode is remembered between sessions.


Troubleshooting
---------------
- If no devices are found, ensure your Wiim device is powered on and connected
  to the same network as your computer.
- The app uses SSDP multicast for discovery. Some routers/firewalls may block
  this traffic. As a fallback, the app will scan common IP addresses on your
  local subnet.
- If you have multiple network adapters, ensure the correct one is active.


Author
------
Hallakorpi Digital
