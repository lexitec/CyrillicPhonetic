# CyrillicPhonetic
Pan-Cyrillic phonetic keyboard layout for Windows
Supported languages: Russian, Belarusian, Ukrainian, Serbian, and Macedonian.

This is a layout that is designed on top of a US QWERTY keyboard layout. Like Stankovski's Russian phonetic layout (https://github.com/stankovski/russian-phonetic-layout-windows10), this layout is similar to the Mac OS Russian phonetic layout. AltGr (or Ctrl+Alt) is used for additional Cyrillic characters. The Pan-Cyrillic additions are mostly based on a DOS keyboard layout that I developed for vDosPlus XyWrite CP866X (see https://www.lexitec.fi/xywrite/utility.html). All US layout's punctuation marks are preserved or relocated to new positions. Ruble, euro and numero signs are included. Set UTF-8 mode in text editors and other applications to view and use all characters. 

Keyboard conflicts: Please note that some applications may use default global AltGr shortcuts that interfere with some keys, e.g. Google Drive has AltGr+G, Keepass has AltGr+K. If you use these applications and the additional Cyrillic keys (Ґ = Ukrainian GHE with upturn or Ќ = Macedonian KJE), the keyboard conflicts must be resolved by changing the respective shortcuts.

## Install

1. Download CyrPhone-installer.zip from Releases
2. Unzip it and run setup.exe
3. On Windows 10, restart Windows before using the new layout

## Uninstall

1. Run setup.exe and select Remove
2. Wait until a dialog appears stating that the uninstall is complete

## Build

1. Install the current version (2020) of `Microsoft Keyboard Layout Creator 1.4` from Microsoft https://www.microsoft.com/en-us/download/details.aspx?id=102134
2. Open (and optionally edit) `src\CyrPhone.klc` using "Keyboard Layout Creator"
3. Or edit the source file with a text editor (advanced users only!)
4. In "Keyboard Layout Creator", go to "Project > Build DLL"
