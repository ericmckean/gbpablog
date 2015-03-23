**gbpablog 0.9** (2011-06-18)
  * Added sound (`*`)
  * Added support for savestates
  * Improved the way the frames are drawn
  * Fixed bug in MBC
  * Implemented serial port interruption (needed by some games)
  * The SDL library is no more needed to be installed in MacOSX, is included in the app bundle
  * Improved accuracy
  * Improved compatibility

`*` Note:
The sound in ubuntu with pulseaudio is not good enough:
  * Choppy sound with the package libsdl1.2debian-pulseaudio.
  * Delayed sound with the package libsdl1.2debian-alsa but with some games can be acceptable.
  * The emulator hangs with the package libsdl1.2debian-esd.

**gbpablog 0.8** (2011-02-26)
  * Added the possibility to change the keys on the keyboard
  * Added support for drag & drop roms
  * Added load of roms from command line
  * Added a menu list of recent roms
  * Added support for the roms with battery to save the state to a file and restore it in a later execution
  * Fixed bug with interruptions that prevented to start some games or produced graphic errors in others
  * Other minor changes

**gbpablog 0.7** (2010-12-07)
  * Fixed bug in windows intaller.
  * Added preferences dialog:
    * Window size
    * Greenscale / grayscale
  * Added support for zipped roms
  * Added about dialog with number version and url to the webpage

**gbpablog 0.6**: (2010-08-21)
  * First public version released