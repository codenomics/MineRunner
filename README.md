# MineRunner

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v1.4** (Oct 3, 2026)

- [MineRunner_v1.4_no-install.zip](https://github.com/codenomics/MineRunner/releases/download/v1.4/MineRunner_v1.4_no-install.zip) - 91 KB
- [MineRunner_v1.4_Setup.exe](https://github.com/codenomics/MineRunner/releases/download/v1.4/MineRunner_v1.4_Setup.exe) - 163 KB

What's new in v1.4:

- MineRunner now checks GitHub for a newer version when it starts; the Updates button at the bottom says "Update available" (it never pops up while you play)
- Update now downloads and runs the new installer for you (installed copies)
- The Updates button also checks any time, and can turn the startup check off

Older versions are on the [Releases page](https://github.com/codenomics/MineRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find MineRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## More details

```
MINERUNNER
==========

For Star Citizen miners. When your ship's scan shows a number like 11,565,
MineRunner pops up a small see-through box in the game that says what it is:
"3x Titanium". It reads the number off your screen with the text reader
built into Windows - it never touches the game itself, and uses well under
1% of your CPU.


GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
  Download the file ending in _Setup.exe, double-click it and click Install.
  It installs just for you (no admin password) and adds Start menu and
  Desktop shortcuts. Needs Windows 10 or 11 (64-bit).
  To remove it later: Windows Settings > Apps > MineRunner > Uninstall.

OPTION 2 - NO INSTALL (zip)
  1. Download the file ending in _no-install.zip. Right-click it -> Extract
  All... and put the MineRunner folder somewhere it can stay (for example
  Documents). Don't run it from inside the zip.
  2. Double-click MineRunner.exe. Nothing is installed; to remove it, delete
  the folder.

EITHER WAY
  In Star Citizen, set the window mode to Borderless (not Fullscreen),
  otherwise the overlay can't show on top of the game.

"Windows protected your PC"? Click "More info" -> "Run anyway".
Windows shows that for apps downloaded from the internet that aren't
signed with a paid certificate.


USING IT
--------
1. Click Pick area, then switch to the game and scan a rock so the signal
   number shows. After 5 seconds the screen freezes: drag a box around the
   number (a roomy box is fine - it copes better with ship wobble).
2. Click Start reading.
3. Help (or F1) has pointers if something doesn't work.

The overlay settings (right side of the window) change how it looks: text
and background color, how see-through each is, size, how long the name stays
on screen, alignment (left / center / right), text shadow and side accents.
Move overlay lets you drag it anywhere, then Done moving. Reset puts it back
under the reading box. The preview shows the result as you go.

"3x Titanium" means a cluster of 3 Titanium rocks. "Salvage" means the number
isn't in your table but divides evenly by 2000. "No sig" means the number
isn't in your table yet.

Tick "Start reading when MineRunner opens" to skip step 2 next time.


GOOD TO KNOW
------------
- The Signatures button opens the signature table: one row per mineral,
  with the scan number for 1 to 6 rocks. MineRunner only shows a rock when
  the exact number is in the table. It comes filled in from real scans -
  fill in the empty spots from your own scans (click a cell to type). You
  can also test a scan number there.
- Settings are kept in %APPDATA%\MineRunner\settings.txt.
- Updates: when MineRunner starts it checks GitHub for a newer version (it only
  reads the public release page; nothing is sent). It never pops up while you
  play - the Updates button at the bottom just changes to "Update available".
  Click it to update: with the installer it downloads and runs the new installer
  for you, with the no-install zip it opens the download page. The same button
  checks on demand, and can turn the startup check off.
- If something goes wrong, MineRunner-log.txt next to MineRunner.exe says what.
- To remove MineRunner: delete its folder, plus %APPDATA%\MineRunner.
```

