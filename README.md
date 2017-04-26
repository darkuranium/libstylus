# libstylus
A library for (portably) dealing with digitizers / styluses / pens.

It is designed to help create stylus-using applications across different operating systems. Windows Ink API will be the first to be supported, but the plans are to support *all* the APIs that can be supported.

## Supported APIs

## Planned APIs
- Windows:
  - Windows Ink (for just about any digitizer in Windows that the OS recognizes --- N-Trig [as used in Windows Surface Pro 4], Synaptics, Wacom, ...)
  - WinTab (for supported Wacom digitizers)
- iOS:
  - UITouch (for Apple Pencil)
- Linux / FreeBSD / ...:
  - libinput
  - xi12
