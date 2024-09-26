# CyrillicPhonetic
Pan-Cyrillic phonetic keyboard layout for Windows (supported languages: Russian, Belarusian, Ukrainian, Serbian, Macedonian)

This is a layout that is designed on top of a US QWERTY keyboard layout. Like Stankovski's Russian phonetic layout (https://github.com/stankovski/russian-phonetic-layout-windows10), this layout is similar to the Mac OS Russian phonetic layout. AltGr (or Ctrl+Alt) is used for additional Cyrillic characters. The Pan-Cyrillic additions are mostly based on a DOS keyboard layout that I developed for vDosPlus XyWrite CP866X (see https://www.lexitec.fi/xywrite/utility.html). All US layout's punctuation marks are preserved or relocated to new positions. Ruble, euro and numero signs are included. Set UTF-8 mode in text editors and other applications to view and use all characters. 

## Install

1. Download CyrPhone-installer.zip from Releases
2. Unzip it and run setup.exe
3. On Windows 10, restart Windows before using the new layout

## Build

1. Install `Microsoft Keyboard Layout Creator 1.4` from Microsoft https://www.microsoft.com/en-us/download/details.aspx?id=22339
2. Open `src\Russian Phonetic.klc` using "Keyboard Layout Creator"
3. Go to "Project > Build DLL"
