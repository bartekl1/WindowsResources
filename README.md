# 📂 Windows UI Assets

An unofficial collection of UI assets (wallpapers, icons, cursors, and sounds) from various versions of Microsoft Windows (XP through 11).

## ⬇️ Download

[Download the whole repository as a ZIP file](https://github.com/bartekl1/windows-ui-assets/zipball/master/)

You can also clone the repository using Git:

```bash
git clone https://github.com/bartekl1/windows-ui-assets.git
```

## 🗃️ Content

|             | Wallpapers                                                                                                           | Icons                                                                                                      | Cursors                                            | Sounds                                            |
|-------------|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|----------------------------------------------------|---------------------------------------------------|
| Windows 11  | [🗒️ Table](Tables/Windows%2011%20Wallpapers.md) [📂 Files](Wallpapers/Windows%2011/)   | [🗒️ Table](Tables/Windows%2011%20Icons.md) [📂 Files](Icons/Windows%2011/)   | [📂 Files](Cursors/Windows%2011/)  | [📂 Files](Sounds/Windows%2011/)  |
| Windows 10  | [🗒️ Table](Tables/Windows%2010%20Wallpapers.md) [📂 Files](Wallpapers/Windows%2010/)   | [🗒️ Table](Tables/Windows%2010%20Icons.md) [📂 Files](Icons/Windows%2010/)   | [📂 Files](Cursors/Windows%2010/)  | [📂 Files](Sounds/Windows%2010/)  |
| Windows 8.1 | [🗒️ Table](Tables/Windows%208.1%20Wallpapers.md) [📂 Files](Wallpapers/Windows%208.1/) | [🗒️ Table](Tables/Windows%208.1%20Icons.md) [📂 Files](Icons/Windows%208.1/) | [📂 Files](Cursors/Windows%208.1/) | [📂 Files](Sounds/Windows%208.1/) |
| Windows 7   | [🗒️ Table](Tables/Windows%207%20Wallpapers.md) [📂 Files](Wallpapers/Windows%207/)     | [🗒️ Table](Tables/Windows%207%20Icons.md) [📂 Files](Icons/Windows%207/)     | [📂 Files](Cursors/Windows%207/)   | [📂 Files](Sounds/Windows%207/)   |
| Windows Vista   | [🗒️ Table](Tables/Windows%20Vista%20Wallpapers.md) [📂 Files](Wallpapers/Windows%20Vista/)     | [🗒️ Table](Tables/Windows%20Vista%20Icons.md) [📂 Files](Icons/Windows%20Vista/)     | [📂 Files](Cursors/Windows%20Vista/)   | [📂 Files](Sounds/Windows%20Vista/)   |
| Windows XP   | [🗒️ Table](Tables/Windows%20XP%20Wallpapers.md) [📂 Files](Wallpapers/Windows%20XP/)     | [🗒️ Table](Tables/Windows%20XP%20Icons.md) [📂 Files](Icons/Windows%20XP/)     | [📂 Files](Cursors/Windows%20XP/)   | [📂 Files](Sounds/Windows%20XP/)   |

> [!NOTE]  
> Preview tables are not included here to keep the README concise and avoid performance issues in the browser.

## 📦 Sources

Files have been extracted from official ISO files or from systems installed on VMs.

| Asset type                                                                                                                        | Path in system files                                                                                                                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Wallpapers <br> <ul> <li>Desktop</li> <li>Lock screen (Windows 8.1 and later)</li> <li>On screen keyboard (Windows 11)</li> </ul> | `%WINDIR%\Web` <br> <ul> <li>`%WINDIR%\Web\Wallpaper`</li> <li>`%WINDIR%\Web\Screen`</li> <li>`%WINDIR%\Web\touchkeyboard`</li> </ul>                                                             |
| Icons <br> <ul> <li>Windows 10 and later</li> <li>Windows 8.1 and older</li> </ul>                                                | <br> <ul> <li>`%WINDIR%\SystemResources\shell32.dll.mun` and `%WINDIR%\SystemResources\imageres.dll.mun`</li> <li>`%WINDIR%\System32\shell32.dll` and `%WINDIR%\System32\imageres.dll`</li> </ul> |
| Cursors                                                                                                                           | `%WINDIR%\Cursors`                                                                                                                                                                                |
| Sounds                                                                                                                            | `%WINDIR%\Media`                                                                                                                                                                                  |

## ⚠️ Legal Notice

All trademarks, images and sounds are the property of **Microsoft Corporation**. \
These resources are provided here for archival, educational, and personal use only. \
Commercial use of these assets may violate Microsoft's End User License Agreement (EULA).

## 📜 License

Repository structure and Markdown files (this README and preview tables) are released under the **MIT License**. \
All graphical and audio materials extracted from Windows remain subject to Microsoft's original licensing terms. \
This repository does not claim ownership of any Microsoft content.

## 🔄 Repository Renamed

This repository was previously named `WindowsResources`. \
Repository has been renamed to `windows-ui-assets` to better reflect its content and purpose.
