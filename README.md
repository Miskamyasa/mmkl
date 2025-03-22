## This is my personal keyboard layouts.

https://keyboard-layout-editor.com/#/

[RU](./keyboard-layout-ru.kle)

Base Russian keyboard layout, but with small tweaks. 
Letters `э, б, ю`, comma, semi anc colon have been moved to different places for better multi language consistency.

<img src="./keyboard-layout-ru.png" width="100%">

[HE](./keyboard-layout-he.kle)

Base Hebrew layout with just small tweaks.  
Letters `ת ץ`, comma, semi anc colon have been moved to different places for better multi language consistency.

<img src="./keyboard-layout-he.png" width="100%">

## Installation of the keyboard layout bundle file

Copy MMKL-HE-RU.bundle file to either:

- /Library/Keyboard Layouts/ (all users)
- ~/Library/Keyboard Layouts/ (current user only)

Log out and log back in, or restart Mac

Enable layouts:

Open System Settings > Keyboard > Input Sources
Click the + button
Find layouts under "Custom" section
Select and add each layout

### Troubleshooting

If layouts don't appear, check permissions: chmod -R 644 ~/Library/Keyboard\ Layouts/MMKL-HE-RU.bundle
Clear keyboard cache: sudo touch /System/Library/Extensions
Restart may be required
