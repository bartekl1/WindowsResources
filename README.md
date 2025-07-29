# :open_file_folder: Windows UI Assets

A collection of UI assets (wallpapers, icons, cursors, and sounds) from various versions of Microsoft Windows (7 through 11).

## :arrow_down: Download

[Download the whole repository as a ZIP file](https://github.com/bartekl1/windows-ui-assets/zipball/master/)

You can also clone the repository using Git:

```bash
git clone https://github.com/bartekl1/windows-ui-assets.git
```

## :card_file_box: Content

|             | Wallpapers                                                                                                           | Icons                                                                                                      | Cursors                                            | Sounds                                            |
|-------------|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|----------------------------------------------------|---------------------------------------------------|
| Windows 11  | [:spiral_notepad: Table](Tables/Windows%2011%20Wallpapers.md) [:open_file_folder: Files](Wallpapers/Windows%2011/)   | [:spiral_notepad: Table](Tables/Windows%2011%20Icons.md) [:open_file_folder: Files](Icons/Windows%2011/)   | [:open_file_folder: Files](Cursors/Windows%2011/)  | [:open_file_folder: Files](Sounds/Windows%2011/)  |
| Windows 10  | [:spiral_notepad: Table](Tables/Windows%2010%20Wallpapers.md) [:open_file_folder: Files](Wallpapers/Windows%2010/)   | [:spiral_notepad: Table](Tables/Windows%2010%20Icons.md) [:open_file_folder: Files](Icons/Windows%2010/)   | [:open_file_folder: Files](Cursors/Windows%2010/)  | [:open_file_folder: Files](Sounds/Windows%2010/)  |
| Windows 8.1 | [:spiral_notepad: Table](Tables/Windows%208.1%20Wallpapers.md) [:open_file_folder: Files](Wallpapers/Windows%208.1/) | [:spiral_notepad: Table](Tables/Windows%208.1%20Icons.md) [:open_file_folder: Files](Icons/Windows%208.1/) | [:open_file_folder: Files](Cursors/Windows%208.1/) | [:open_file_folder: Files](Sounds/Windows%208.1/) |
| Windows 7   | [:spiral_notepad: Table](Tables/Windows%207%20Wallpapers.md) [:open_file_folder: Files](Wallpapers/Windows%207/)     | [:spiral_notepad: Table](Tables/Windows%207%20Icons.md) [:open_file_folder: Files](Icons/Windows%207/)     | [:open_file_folder: Files](Cursors/Windows%207/)   | [:open_file_folder: Files](Sounds/Windows%207/)   |

> [!NOTE]  
> Preview tables are not included here to keep the README concise and avoid performance issues in the browser.

Files for older versions (Windows Vista and older) will be added soon.

## :package: Sources

Files have been extracted from official ISO files or from systems installed on VMs.

| Asset type                                                                                                                        | Path in system files                                                                                                                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Wallpapers <br> <ul> <li>Desktop</li> <li>Lock screen (Windows 8.1 and later)</li> <li>On screen keyboard (Windows 11)</li> </ul> | `%WINDIR%\Web` <br> <ul> <li>`%WINDIR%\Web\Wallpaper`</li> <li>`%WINDIR%\Web\Screen`</li> <li>`%WINDIR%\Web\touchkeyboard`</li> </ul>                                                             |
| Icons <br> <ul> <li>Windows 10 and later</li> <li>Windows 8.1 and older</li> </ul>                                                | <br> <ul> <li>`%WINDIR%\SystemResources\shell32.dll.mun` and `%WINDIR%\SystemResources\imageres.dll.mun`</li> <li>`%WINDIR%\System32\shell32.dll` and `%WINDIR%\System32\imageres.dll`</li> </ul> |
| Cursors                                                                                                                           | `%WINDIR%\Cursors`                                                                                                                                                                                |
| Sounds                                                                                                                            | `%WINDIR%\Media`                                                                                                                                                                                  |

## :warning: Legal Notice

All trademarks, images and sounds are the property of **Microsoft Corporation**. \
These resources are provided here for archival, educational, and personal use only. \
Commercial use of these assets may violate Microsoft's End User License Agreement (EULA).

## :scroll: License

Repository structure and Markdown files (this README and preview tables) are released under the **MIT License**. \
All graphical and audio materials extracted from Windows remain subject to Microsoft's original licensing terms. \
This repository does not claim ownership of any Microsoft content.

## :arrows_counterclockwise: Repository Renamed

This repository was previously named `WindowsResources`. \
Repository has been renamed to `windows-ui-assets` to better reflect its content and purpose.
