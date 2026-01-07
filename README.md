# WindowsGlass

<div align="center">
<img width="48%" height="auto" alt="Minimal Preview" src="/Preview.png" /> 
<img width="48%" height="auto" alt="Minimal Preview" src="/Minimal-Preview.png" />
</div>

> [!NOTE]
> Let me say right away that I'm neither a programmer nor a designer. I simply liked this design and decided to tweak it a bit to suit my tastes. I'd be grateful for any help or advice. This is still a work in progress (I do this in my free time and whenever I feel like it)

##### Also thanks to @x3phyy for this and other improvements that I'm using

> [!IMPORTANT]
> The start menu theme ONLY supports 16:9 or 16:10 screen reolutions with a DPI of 100% *(Tested on 1920x1080 and 1920x1200)*. Using it on anything else will result in overlapping elements. There is a minimal variation included of which *should* support most resolutions regardless of DPI.
> 
> See the [Instructions](/INSTRUCTIONS.md) page for instructions on how to apply this theme.


#### If you'd like to help, I'd be grateful! Below will be written the current problems that I want to solve in the future or I am unable to solve them. You can find a changelog with all of our current changes [here](/CHANGELOG.md).

## Known Issues

### Problems I couldn't solve:
      Start Menu:
        1. In the "Pinned" section, there's a gray border around the folder thumbnails 
           (where the four app icon previews are)
        2. At the bottom of the "All" section, there's a border that hides the contents of 
           that section, but it's not very nicely positioned. I couldn't lower this border 
           to the "User Panel" bottom level

      Notifications Center:
        1. Change the color of the buttons when it is off, icons and the text underneath them 
            to gray for better  readability

### I want to try doing this in the future:
      Start Menu:
        1. Move the "Account" button slightly to the right and the "power" button to the left 
           for symmetry
        2. Properly fit the navigattion tray on the far right without causing the start menu to
           have a cutoff
             
      Taskbar:
        1. Change the tray background from the standard one to WindowGlass
        2. Add seperate start button images for each start button state. 
           (e.g. pressed, pointer over, normal)

## Manual installation

The theme styles must be imported manually for now due to the official version needing a large amount of fixes. To do that, follow these steps.

### Preperation

* Install the [Vivo Sans En VF](https://1drv.ms/u/c/67fedd4420ed716d/EXRoW1f5dABJrO2dPj0tbM0Bm1uYiGeoKyAYA7X7er2Zww?e=cLsiJJ) and [Vivo Sans Clock Stencil](https://1drv.ms/u/c/67fedd4420ed716d/EW6LJO1CAu1Fs-khbTGXWFUB5sXhRxM-I__B1lkKWgizdA?e=J1RJYy) fonts.
* Download the [w11-grey.png](/resources/w11-grey.png) file and place it into `C:\Resources\Icons\Start Orbs\`. *(If the location doesn`t exist, create it.)*

### Start Menu

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

### Taskbar

* Open the Windows 11 Taskbar Styler mod in Windhawk.
* Go to the `Settings` tab and click the `Textual` button.
* Copy the contents of the [taskbar.yml](/Taskbar/taskbar.yml) file to the text box under `Mod settings` and click `Save`.

### Notification Center

* Open the Windows 11 Notification Center Styler mod in Windhawk.
* Go to the `Settings` tab and click the `Textual` button.
* Copy the contents of the [notification center.yml](/Notification%20Center/notification%20center.yml) file to the text box under `Mod settings` and click `Save`.
