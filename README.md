<div align="center">

# Improved Windows Glass Theme

</div>

> [!IMPORTANT]
> The start menu theme ONLY supports 16:9 or 16:10 screen reolutions with a DPI of 100% *(Tested on 1920x1080 and 1920x1200)*. Using it on anything else will result in overlapping elements. There is a minimal variation included of which *should* support most resolutions regardless of DPI.


#### If you'd like to help, feel free to open a PR with your improvements and/or fixes!

<details>
<summary>Preview Images</summary>
<img width="96%" height="auto" alt="Minimal Preview" src="/resources/Preview.png" />
<img width="48%" height="auto" alt="High DPI Preview" src="/resources/High-DPI-Preview.png" />
<img width="48%" height="auto" alt="Minimal Preview" src="/resources/Minimal-Preview.png" />
<hr />
<img width="48%" height="auto" alt="File Explorer Preview" src="/resources/File-Explorer-Preview.png" />
<img width="48%" height="auto" alt="File Explorer Preview" src="/resources/File-Explorer-Tabs-Preview.png" />

</details>

## To-Do
Tweaks and adjusments that I am looking into and want to get done in future updates.

### Start Menu
1. Adjust the start menu scroll container size for more consistant visuals.
2. Adjust list view width to remove overlapping on hover.
3. Adjust grid view width to allow for more columns and better fit the available space.
             
### Taskbar
1. Add seperate start button images for each start button state. *(preferably one that looks more like a frosted glass w11 start button to match the glass ui a bit more)*
   - **Normal State**: A grey-scaled *(preferably frosted glass)* version of the default start button's normal image.
   - **Pointer Over State**: A grey-scaled *(preferably frosted glass)* version of the default start button's pointer over image.
   - **Pressed State**: A grey-scaled *(preferably frosted glass)* version of the default start button's pressed image. 

### File Explorer
1. Adjust the transparency of the overflow menus for improved visibility.
2. Adjust the transparency of the tooltips for improved visibility.

## Manual installation

The theme styles must be imported manually for now due to the official version needing a large amount of fixes. To do that, follow these steps.

## Requirements

* **Windhawk Mods**: `Windows 11 Start Menu Styler`, `Windows 11 Taskbar Styler`, `Windows 11 Notification Center Styler`, `Shell Flyout Positions`, `Taskbar tray system icon tweaks`, `Translucent Windows`, `Taskbar Clock Customization`
* **Vivo Sans Fonts**: Install the [Vivo Sans En VF](https://1drv.ms/u/c/67fedd4420ed716d/EXRoW1f5dABJrO2dPj0tbM0Bm1uYiGeoKyAYA7X7er2Zww?e=cLsiJJ) and [Vivo Sans Clock Stencil](https://1drv.ms/u/c/67fedd4420ed716d/EW6LJO1CAu1Fs-khbTGXWFUB5sXhRxM-I__B1lkKWgizdA?e=J1RJYy) fonts.
* **Start Button Image**: Download the [w11-grey.png](/resources/w11-grey.png) file and place it into `C:\Resources\Icons\Start Orbs\`. *(If the location doesn`t exist, create it.)*

## Start Menu

### Default Start Menu

1. Open the `Windows 11 Start Menu Styler` mod in Windhawk.
   - Go to the `Advanced` tab.
   - Add `LockApp.exe` to the `Custom process inclusion list`.
   - Return to the `Settings` tab and click the `Textual` button.
   - Copy the contents of the [start menu default.yml](/Start%20Menu/start%20menu%20default.yml) file to the text box and click `Save`.

### Minimal Start Menu

This theme also includes a minimal version of the Start menu with the Phone Link companion removed. *(Should work regardless of resolution or DPI)*

1. Open the `Windows 11 Start Menu Styler` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [start menu minimal.yml](/Start%20Menu/start%20menu%20minimal.yml) file to the text box and click `Save`.

### High DPI Start Menu

This theme also includes a high dpi version of the Start menu with smaller grid limits to allow the Phone Link widget on systems with higher DPI. *(Tested on 1920x1080 and 1920x1200 resolutions at 125% DPI)*

1. Open the `Windows 11 Start Menu Styler` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [high dpi start menu.yml](/Start%20Menu/high%20dpi%20start%20menu.yml) file to the text box and click `Save`.

## Taskbar

### Default Taskbar

1. Open the ``Windows 11 Taskbar Styler`` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [taskbar.yml](/Taskbar/default%20taskbar.yml) file to the text box and click `Save`.
2. Open the `Taskbar tray system icon tweaks` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [system tray.yml](/System%20Tray%20Tweaks/system%20tray.yml) file to the text box and click `Save`.
3. Open the `Taskbar Clock Customization` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [clock.yml](/Clock/clock.yml) file to the text box and click `Save`.

### High DPI Taskbar

This theme also includes a high dpi version of the taskbar. *(Tested on 1920x1080 and 1920x1200 resolutions at 125% DPI)*

1. Open the `Windows 11 Taskbar Styler` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [taskbar.yml](/Taskbar/high%20dpi%20taskbar.yml) file to the text box and click `Save`.
2. Open the `Taskbar tray system icon tweaks` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [system tray.yml](/System%20Tray%20Tweaks/system%20tray.yml) file to the text box and click `Save`.
3. Open the `Taskbar Clock Customization` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [clock.yml](/Clock/clock.yml) file to the text box and click `Save`.

### Full Width Taskbar

For users who prefer a full width taskbar.

1. Open the `Windows 11 Taskbar Styler` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [full width taskbar.yml](/Taskbar/full%20width%20taskbar.yml) file to the text box and click `Save`.
2. Open the `Taskbar tray system icon tweaks` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [system tray.yml](/System%20Tray%20Tweaks/system%20tray.yml) file to the text box and click `Save`.
3. Open the `Taskbar Clock Customization` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [clock.yml](/Clock/clock.yml) file to the text box and click `Save`.

## Notification Center

1. Open the `Windows 11 Notification Center Styler` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [notification center.yml](/Notification%20Center/notification%20center.yml) file to the text box and click `Save`.
2. Open the `Shell Flyout Positions` mod in Windhawk
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [align with tray.yml](/Shell%20Flyout%20Positions/align%20with%20tray.yml) file to the text box and click `Save`.

## File Explorer

1. Open the `Windows 11 File Explorer Styler` mod in Windhawk.
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [file explorer.yml](/File%20Explorer/file%20explorer.yml) file to the text box and click `Save`.
2. Open the `Translucent Windows` mod in Windhawk.
   - Go to the `Advanced` tab and copy the contents of the [Translucent Windows Exclusions](/Translucent%20Windows/Exclusions.txt) file into the `Custom process exclusions list`.
      - *(Refer to [this issue comment](https://github.com/The-Back-Room/Improved-Windows-Glass-Theme/issues/3#issuecomment-3812780048) in regards to getting around a bug with excluding MS Office apps from Translucent Windows)*
   - Go to the `Settings` tab and click the `Textual` button to swap into Textual mode.
   - Copy the contents of the [translucent windows.yml](/Translucent%20Windows/translucent%20windows.yml) file to the text box and click `Save`. Update CHANGELOG