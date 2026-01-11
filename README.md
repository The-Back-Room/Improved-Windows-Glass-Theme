<div align="center">

# Improved Windows Glass Theme

<img width="96%" height="auto" alt="Minimal Preview" src="/resources/Preview.png" />
<img width="48%" height="auto" alt="High DPI Preview" src="/resources/High-DPI-Preview.png" />
<img width="48%" height="auto" alt="Minimal Preview" src="/resources/Minimal-Preview.png" />
</div>

> [!IMPORTANT]
> The start menu theme ONLY supports 16:9 or 16:10 screen reolutions with a DPI of 100% *(Tested on 1920x1080 and 1920x1200)*. Using it on anything else will result in overlapping elements. There is a minimal variation included of which *should* support most resolutions regardless of DPI.


#### If you'd like to help, feel free to open a PR with your improvements and/or fixes!

## To-Do
Tweaks and adjusments that I am looking into and want to get done in future updates.

### Start Menu
1. Adjust the start menu scroll container size for more consistant visuals.
             
### Taskbar
1. Add seperate start button images for each start button state. *(preferably one that looks more like a frosted glass w11 start button to match the glass ui a bit more)*
   - **Normal State**: A grey-scaled *(preferably frosted glass)* version of the default start button's normal image.
   - **Pointer Over State**: A grey-scaled *(preferably frosted glass)* version of the default start button's pointer over image.
   - **Pressed State**: A grey-scaled *(preferably frosted glass)* version of the default start button's pressed image. 

## Manual installation

The theme styles must be imported manually for now due to the official version needing a large amount of fixes. To do that, follow these steps.

### Requirements

* **Vivo Sans Fonts**: Install the [Vivo Sans En VF](https://1drv.ms/u/c/67fedd4420ed716d/EXRoW1f5dABJrO2dPj0tbM0Bm1uYiGeoKyAYA7X7er2Zww?e=cLsiJJ) and [Vivo Sans Clock Stencil](https://1drv.ms/u/c/67fedd4420ed716d/EW6LJO1CAu1Fs-khbTGXWFUB5sXhRxM-I__B1lkKWgizdA?e=J1RJYy) fonts.
* **Start Button Image**: Download the [w11-grey.png](/resources/w11-grey.png) file and place it into `C:\Resources\Icons\Start Orbs\`. *(If the location doesn`t exist, create it.)*

### Default Start Menu

* Open the Windows 11 Start Menu Styler mod in Windhawk.
* Go to the `Advanced` tab.
* Add `LockApp.exe` to the `Custom process inclusion list`.
* Return to the `Settings` tab and click the `Textual` button.
* Copy the contents of the [start menu default.yml](/Start%20Menu/start%20menu%20default.yml) file to the text box under `Mod settings` and click `Save`.

### Minimal Start Menu

This theme also includes a minimal version of the Start menu with the Phone Link companion removed.

* Open the Windows 11 Start Menu Styler mod in Windhawk.
* Go to the `Settings` tab and click the `Textual` button.
* Copy the contents of the [start menu minimal.yml](/Start%20Menu/start%20menu%20minimal.yml) file to the text box under `Mod settings` and click `Save`.

### High DPI Start Menu

This theme also includes a high dpi version of the Start menu with smaller grid limits to allow the Phone Link widget on systems with higher DPI. *(Tested on 1920x1080 and 1920x1200 resolutions at 125% DPI)*

* Open the Windows 11 Start Menu Styler mod in Windhawk.
* Go to the `Settings` tab and click the `Textual` button.
* Copy the contents of the [high dpi start menu.yml](/Start%20Menu/high%20dpi%20start%20menu.yml) file to the text box under `Mod settings` and click `Save`.

### Default Taskbar

* Open the Windows 11 Taskbar Styler mod in Windhawk.
* Go to the `Settings` tab and click the `Textual` button.
* Copy the contents of the [taskbar.yml](/Taskbar/taskbar.yml) file to the text box under `Mod settings` and click `Save`.

### Full Width Taskbar

For users who prefer a full width taskbar.

* Open the Windows 11 Taskbar Styler mod in Windhawk.
* Go to the `Settings` tab and click the `Textual` button.
* Copy the contents of the [full width taskbar.yml](/Taskbar/full%20width%20taskbar.yml) file to the text box under `Mod settings` and click `Save`.

### Notification Center

* Open the Windows 11 Notification Center Styler mod in Windhawk.
* Go to the `Settings` tab and click the `Textual` button.
* Copy the contents of the [notification center.yml](/Notification%20Center/notification%20center.yml) file to the text box under `Mod settings` and click `Save`.
