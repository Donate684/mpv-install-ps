``Rewrite original script to PowerShell with GUI`` <img src="https://rossy.github.io/mpv-install/mpv-document.png" align="right">
===================

This script sets up file associations for [mpv] on Windows, using [umpvw].

![preview](preview.jpg?raw=true)

How to install
--------------

1. Open your mpv folder
2. Download the zip: [https://github.com/Donate684/mpv-install-ps/archive/refs/heads/master.zip](https://github.com/Donate684/mpv-install-ps/archive/refs/heads/master.zip)
3. Copy installer folder and umpvw.exe to the same directory as mpv.exe
4. Run ``install.bat``
   
What it does
------------

- Uses umpvw to use mpv in single instance mode, macOS style
- Creates file associations for several video and audio file types
- Registers mpv with the _Default Programs_ control panel
- Puts mpv in the "Open with" menu for all video and audio files
- Registers umpvw.exe so it can be used from the Run dialog and the Start Menu
- Adds mpv as an AutoPlay handler for Blu-rays and DVDs
- Works when reinstalled to a different folder than the one it was in
  previously. (File associations created by the "Open with" menu have trouble
  with this.)

What it doesn't do
------------------

- Add mpv to the ``%PATH%``
- Enable thumbnails for all media types (use [Icaros][3] for this)

[1]: https://mpv.io/
[2]: https://github.com/rossy/mpv-install/issues/7
[3]: http://www.majorgeeks.com/files/details/icaros.html
[4]: https://github.com/SilverEzhik/umpvw
