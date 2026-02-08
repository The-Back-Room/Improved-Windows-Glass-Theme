# Taskbar

> [!IMPORTANT]
> The theme styles must be imported manually for now due to the official version needing a large amount of fixes. To do that, follow these steps.

## Installation
Follow the instructions listed below to install and setup the Windows Glass Taskbar theme on your system.

---

### Requirements

* **Windhawk Mods**:
  * [Windows 11 Taskbar Styler](https://windhawk.net/mods/windows-11-taskbar-styler)
  * [Taskbar tray system icon tweaks](https://windhawk.net/mods/taskbar-tray-system-icon-tweaks) *(Optional)*
  * [Taskbar Clock Customization](https://windhawk.net/mods/taskbar-clock-customization) *(Optional)*
  * [Taskbar Music Lounge - Fork](#taskbar-music-lounge---fork-optional) *(Optional)*

---

### Default Taskbar

<img src="Default-Preview.png" width="100%" height="auto" />

* Open the `Windows 11 Taskbar Styler` mod in Windhawk.
* Go to the `Advanced` tab and copy the code below into the `Mod settings` box and click `save`.

<details>
<summary>Content to import (click to expand)</summary>

```json
{
"theme": "",
"controlStyles[0].target": "Taskbar.TaskbarFrame#TaskbarFrame",
"controlStyles[0].styles[0]": "CornerRadius=$CornerRadius",
"controlStyles[0].styles[1]": "HorizontalAlignment=Stretch",
"controlStyles[0].styles[2]": "MaxWidth=1330",
"controlStyles[0].styles[3]": "Width=Auto",
"controlStyles[1].target": "Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid",
"controlStyles[1].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[1].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[1].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[1].styles[3]": "Background:=$Background",
"controlStyles[2].target": "Rectangle#BackgroundFill",
"controlStyles[2].styles[0]": "Visibility=1",
"controlStyles[3].target": "Rectangle#BackgroundStroke",
"controlStyles[3].styles[0]": "Visibility=1",
"controlStyles[4].target": "Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
"controlStyles[4].styles[0]": "Margin=-2,0",
"controlStyles[5].target": "Grid#SystemTrayFrameGrid",
"controlStyles[5].styles[0]": "Background:=$ElementBG",
"controlStyles[5].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[5].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[5].styles[3]": "CornerRadius=$ElementCornerRadius",
"controlStyles[5].styles[4]": "Margin=4",
"controlStyles[5].styles[5]": "RenderTransform:=<TranslateTransform X=\"-304\" />",
"controlStyles[6].target": "SystemTray.ChevronIconView",
"controlStyles[6].styles[0]": "CornerRadius=$CornerRadius",
"controlStyles[7].target": "SystemTray.NotifyIconView#NotifyItemIcon",
"controlStyles[7].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[8].target": "SystemTray.OmniButton",
"controlStyles[8].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[9].target": "SystemTray.IconView#SystemTrayIcon > Grid#ContainerGrid > ContentPresenter#ContentPresenter > Grid#ContentGrid > SystemTray.TextIconContent > Grid#ContainerGrid",
"controlStyles[9].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[10].target": "Taskbar.Gripper#GripperControl",
"controlStyles[10].styles[0]": "Width=Auto",
"controlStyles[10].styles[1]": "MinWidth=24",
"controlStyles[10].styles[2]": "HorizontalAlignment=Left",
"controlStyles[11].target": "TextBlock#TimeInnerTextBlock",
"controlStyles[11].styles[0]": "FontSize=13",
"controlStyles[11].styles[1]": "FontFamily=vivo Sans EN VF",
"controlStyles[11].styles[2]": "Margin=0",
"controlStyles[11].styles[3]": "Padding=0",
"controlStyles[11].styles[4]": "RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />",
"controlStyles[12].target": "TextBlock#DateInnerTextBlock",
"controlStyles[12].styles[0]": "Visibility=1",
"controlStyles[13].target": "TextBlock#InnerTextBlock[Text=]",
"controlStyles[13].styles[0]": "Text=",
"controlStyles[14].target": "TextBlock#SearchBoxTextBlock",
"controlStyles[14].styles[0]": "Text=Search This PC",
"controlStyles[14].styles[1]": "FontSize=10",
"controlStyles[14].styles[2]": "FontFamily=vivo Sans EN VF",
"controlStyles[15].target": "SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon > Grid > Grid > SystemTray.TextIconContent",
"controlStyles[15].styles[0]": "Visibility=1",
"controlStyles[16].target": "Border#OverflowFlyoutBackgroundBorder",
"controlStyles[16].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[16].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[16].styles[2]": "Background:=$Background",
"controlStyles[16].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[17].target": "WindowsInternal.ComposableShell.Experiences.Switcher.AltTab > Grid#ModalRootGrid > Border",
"controlStyles[17].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[17].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[17].styles[2]": "Background:=$Background",
"controlStyles[17].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[18].target": "WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement#VirtualDesktopBar",
"controlStyles[18].styles[0]": "CornerRadius=$CornerRadius",
"controlStyles[18].styles[1]": "Background:=$Background",
"controlStyles[19].target": "Border#BackgroundDimmingLayer",
"controlStyles[19].styles[0]": "Background:=$Background",
"controlStyles[19].styles[1]": "CornerRadius=$CornerRadius",
"controlStyles[20].target": "Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel > Border#BackgroundElement",
"controlStyles[20].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[20].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[21].target": "Taskbar.TaskListButton#TaskListButton",
"controlStyles[21].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[21].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[22].target": "Border#SnapBarBorder",
"controlStyles[22].styles[0]": "Background:=$Background",
"controlStyles[22].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[22].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[22].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[22].styles[4]": "Margin=2",
"controlStyles[23].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Border#BackgroundElement",
"controlStyles[23].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[23].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[23].styles[2]": "Background@ActiveNormal:=$ActiveBG",
"controlStyles[23].styles[3]": "Background@ActivePointerOver:=$ActiveBG",
"controlStyles[23].styles[4]": "Background@ActivePressed:=$ActiveBG",
"controlStyles[23].styles[5]": "Background@InactivePointerOver:=$ElementBG",
"controlStyles[23].styles[6]": "Background@InactivePressed:=$ElementBG",
"controlStyles[23].styles[7]": "BorderBrush@ActiveNormal:=$ElementBorderBrush",
"controlStyles[23].styles[8]": "BorderBrush@ActivePointerOver:=$ElementBorderBrush",
"controlStyles[23].styles[9]": "BorderBrush@ActivePressed:=$ElementBorderBrush",
"controlStyles[23].styles[10]": "BorderBrush@InactivePointerOver:=$ElementBorderBrush",
"controlStyles[23].styles[11]": "BorderBrush@InactivePressed:=$ElementBorderBrush",
"controlStyles[23].styles[12]": "Margin=1",
"controlStyles[24].target": "ContentPresenter#ContentPresenter@CommonStates",
"controlStyles[24].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[24].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[24].styles[2]": "Background@ActiveNormal:=$ActiveBG",
"controlStyles[24].styles[3]": "Background@ActivePointerOver:=$ActiveBG",
"controlStyles[24].styles[4]": "Background@ActivePressed:=$ActiveBG",
"controlStyles[24].styles[5]": "Background@InactivePointerOver:=$ElementBG",
"controlStyles[24].styles[6]": "Background@InactivePressed:=$ElementBG",
"controlStyles[24].styles[7]": "BorderBrush@ActiveNormal:=$ElementBorderBrush",
"controlStyles[24].styles[8]": "BorderBrush@ActivePointerOver:=$ElementBorderBrush",
"controlStyles[24].styles[9]": "BorderBrush@ActivePressed:=$ElementBorderBrush",
"controlStyles[24].styles[10]": "BorderBrush@InactivePointerOver:=$ElementBorderBrush",
"controlStyles[24].styles[11]": "BorderBrush@InactivePressed:=$ElementBorderBrush",
"controlStyles[24].styles[12]": "Margin=1",
"controlStyles[25].target": "Border#SnapPickerBorder",
"controlStyles[25].styles[0]": "Background:=$Background",
"controlStyles[25].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[25].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[25].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[25].styles[4]": "Margin=2",
"controlStyles[26].target": "Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
"controlStyles[26].styles[0]": "Background:=Transparent",
"controlStyles[27].target": "ToolTip > ContentPresenter#LayoutRoot",
"controlStyles[27].styles[0]": "Background:=$Background",
"controlStyles[27].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[27].styles[2]": "BorderThickness:=$BorderThickness",
"controlStyles[27].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[28].target": "WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement > Grid#GridElement > Border#VirtualDesktopSwitcherBackground",
"controlStyles[28].styles[0]": "BorderBrush:=$BorderBrush",
"controlStyles[28].styles[1]": "BorderThickness=$BorderThickness",
"controlStyles[28].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[28].styles[3]": "Background=$Background",
"controlStyles[29].target": "WindowsInternal.ComposableShell.Experiences.Switcher.SwitchItemListViewItem > Grid > Border",
"controlStyles[29].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[30].target": "Border#VirtualDesktopBarBackground",
"controlStyles[30].styles[0]": "Background:=$Background",
"controlStyles[30].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[30].styles[2]": "BorderThickness=$BorderThickness",
"controlStyles[30].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[31].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Border#BackgroundElement",
"controlStyles[31].styles[0]": "Background:=$ElementBG",
"controlStyles[31].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[31].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[31].styles[3]": "CornerRadius=$ElementCornerRadius",
"controlStyles[32].target": "Rectangle#RunningIndicator",
"controlStyles[32].styles[0]": "Visibility=1",
"controlStyles[33].target": "Rectangle#ShowDesktopPipe",
"controlStyles[33].styles[0]": "Visibility=1",
"controlStyles[34].target": "Rectangle#RightOverflowButtonDivider",
"controlStyles[34].styles[0]": "Visibility=1",
"controlStyles[35].target": "SearchUx.SearchUI.SearchIconButton > SearchUx.SearchUI.SearchButtonRootGrid@CommonStates > Border#BackgroundElement",
"controlStyles[35].styles[0]": "Background:=Transparent",
"controlStyles[35].styles[1]": "BorderBrush:=Transparent",
"controlStyles[36].target": "SearchUx.SearchUI.SearchButtonRootGrid",
"controlStyles[36].styles[0]": "Background:=Transparent",
"controlStyles[36].styles[1]": "BorderBrush:=Transparent",
"controlStyles[37].target": "Border#SearchPillBackgroundElement",
"controlStyles[37].styles[0]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[37].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[37].styles[2]": "CornerRadius=$ElementCornerRadius",
"controlStyles[37].styles[3]": "Margin=0,1",
"controlStyles[38].target": "SearchUx.SearchUI.SearchBoxButton > SearchUx.SearchUI.SearchButtonRootGrid@CommonStates > Border#BackgroundElement",
"controlStyles[38].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[38].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[38].styles[2]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[38].styles[3]": "Background:=$ElementBG",
"controlStyles[38].styles[4]": "Margin=0,-4",
"controlStyles[39].target": "Canvas#HoverFlyoutCanvas > Grid#HoverFlyoutGrid > Border#HoverFlyoutBackground",
"controlStyles[39].styles[0]": "Shadow:=",
"controlStyles[39].styles[1]": "Background:=$Background",
"controlStyles[39].styles[2]": "BorderBrush:=$BorderBrush",
"controlStyles[39].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[39].styles[4]": "CornerRadius=$CornerRadius",
"controlStyles[40].target": "Border#BackgroundElement",
"controlStyles[40].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[40].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[40].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[40].styles[3]": "Background:=$ElementBG",
"controlStyles[41].target": "// Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Border#BackgroundElement",
"controlStyles[41].styles[0]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[41].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[41].styles[2]": "CornerRadius=$ElementCornerRadius",
"controlStyles[41].styles[3]": "Padding=18",
"controlStyles[41].styles[4]": "Background@Normal:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Normal.png\" />",
"controlStyles[41].styles[5]": "Background@PointerOver:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Hover.png\" />",
"controlStyles[41].styles[6]": "Background@Pressed:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Pressed.png\" />",
"controlStyles[41].styles[7]": "// This section is on hold until I have the correct images and have fleshed out the correct method to add them.",
"controlStyles[42].target": "// Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Microsoft.UI.Xaml.Controls.AnimatedVisualPlayer#Icon",
"controlStyles[42].styles[0]": "Visibility=1",
"controlStyles[42].styles[1]": "// This section is on hold until I have the correct images and have fleshed out the correct method to add them.",
"controlStyles[43].target": "SystemTray.SystemTrayFrame",
"controlStyles[43].styles[0]": "HorizontalAlignment=Right",
"controlStyles[44].target": "Grid#AugmentedEntryPointContentGrid",
"controlStyles[44].styles[0]": "HorizontalAlignment=Left",
"styleConstants[0]": "BorderThickness=0.3,1,0.3,0.3",
"styleConstants[1]": "ElementBorderThickness=0.3,0.3,0.3,1",
"styleConstants[2]": "Background=<WindhawkBlur BlurAmount=\"15\" TintColor=\"#25323232\" TintOpacity=\"0.2\" />",
"styleConstants[3]": "BorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"0.0\" /><GradientStop Color=\"#50404040\" Offset=\"0.25\" /><GradientStop Color=\"#50808080\" Offset=\"1\" /></LinearGradientBrush>",
"styleConstants[4]": "GlassBG=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeAltHighColor}\" TintOpacity=\"0.3\" FallbackColor=\"{ThemeResource SystemChromeAltHighColor}\" />",
"styleConstants[5]": "GlassBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"0.0\" /><GradientStop Color=\"{ThemeResource SystemChromeLowColor}\" Offset=\"0.25\" /><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"1\" /></LinearGradientBrush>",
"styleConstants[6]": "ElementBG=<WindhawkBlur BlurAmount=\"20\" TintColor=\"#202020\" TintOpacity=\"0.2\" />",
"styleConstants[7]": "ActiveBG=<WindhawkBlur BlurAmount=\"40\" TintColor=\"#FFFFFF\" TintOpacity=\"Opacity=\"0.8\" />",
"styleConstants[8]": "ElementBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"1\" /><GradientStop Color=\"#50606060\" Offset=\"0.15\" /></LinearGradientBrush>",
"styleConstants[9]": "CornerRadius=10",
"styleConstants[10]": "ElementCornerRadius=6",
"resourceVariables[0].variableKey": "",
"resourceVariables[0].value": ""
}
```

</details>

---

### High DPI Taskbar
This theme also includes a high dpi variant of the taskbar. *(Tested on 1920x1080 and 1920x1200 resolutions at 125% DPI)*

<img src="High-DPI-Preview.png" width="100%" height="auto" />

* Open the `Windows 11 Taskbar Styler` mod in Windhawk.
* Go to the `Advanced` tab and copy the code below into the `Mod settings` box and click `save`.

<details>
<summary>Content to import (click to expand)</summary>

```json
{
"theme": "",
"controlStyles[0].target": "Taskbar.TaskbarFrame#TaskbarFrame",
"controlStyles[0].styles[0]": "CornerRadius=$CornerRadius",
"controlStyles[0].styles[1]": "HorizontalAlignment=Stretch",
"controlStyles[0].styles[2]": "MaxWidth=1330",
"controlStyles[0].styles[3]": "Width=Auto",
"controlStyles[1].target": "Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid",
"controlStyles[1].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[1].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[1].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[1].styles[3]": "Background:=$Background",
"controlStyles[2].target": "Rectangle#BackgroundFill",
"controlStyles[2].styles[0]": "Visibility=1",
"controlStyles[3].target": "Rectangle#BackgroundStroke",
"controlStyles[3].styles[0]": "Visibility=1",
"controlStyles[4].target": "Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
"controlStyles[4].styles[0]": "Margin=-2,0",
"controlStyles[5].target": "Grid#SystemTrayFrameGrid",
"controlStyles[5].styles[0]": "Background:=$ElementBG",
"controlStyles[5].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[5].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[5].styles[3]": "CornerRadius=$ElementCornerRadius",
"controlStyles[5].styles[4]": "Margin=4",
"controlStyles[5].styles[5]": "RenderTransform:=<TranslateTransform X=\"-104\" />",
"controlStyles[6].target": "SystemTray.ChevronIconView",
"controlStyles[6].styles[0]": "CornerRadius=$CornerRadius",
"controlStyles[7].target": "SystemTray.NotifyIconView#NotifyItemIcon",
"controlStyles[7].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[8].target": "SystemTray.OmniButton",
"controlStyles[8].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[9].target": "SystemTray.IconView#SystemTrayIcon > Grid#ContainerGrid > ContentPresenter#ContentPresenter > Grid#ContentGrid > SystemTray.TextIconContent > Grid#ContainerGrid",
"controlStyles[9].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[10].target": "Taskbar.Gripper#GripperControl",
"controlStyles[10].styles[0]": "Width=Auto",
"controlStyles[10].styles[1]": "MinWidth=24",
"controlStyles[10].styles[2]": "HorizontalAlignment=Left",
"controlStyles[11].target": "TextBlock#TimeInnerTextBlock",
"controlStyles[11].styles[0]": "FontSize=13",
"controlStyles[11].styles[1]": "FontFamily=vivo Sans EN VF",
"controlStyles[11].styles[2]": "Margin=0",
"controlStyles[11].styles[3]": "Padding=0",
"controlStyles[11].styles[4]": "RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />",
"controlStyles[12].target": "TextBlock#DateInnerTextBlock",
"controlStyles[12].styles[0]": "Visibility=1",
"controlStyles[13].target": "TextBlock#InnerTextBlock[Text=]",
"controlStyles[13].styles[0]": "Text=",
"controlStyles[14].target": "TextBlock#SearchBoxTextBlock",
"controlStyles[14].styles[0]": "Text=Search This PC",
"controlStyles[14].styles[1]": "FontSize=10",
"controlStyles[14].styles[2]": "FontFamily=vivo Sans EN VF",
"controlStyles[15].target": "SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon > Grid > Grid > SystemTray.TextIconContent",
"controlStyles[15].styles[0]": "Visibility=1",
"controlStyles[16].target": "Border#OverflowFlyoutBackgroundBorder",
"controlStyles[16].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[16].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[16].styles[2]": "Background:=$Background",
"controlStyles[16].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[17].target": "WindowsInternal.ComposableShell.Experiences.Switcher.AltTab > Grid#ModalRootGrid > Border",
"controlStyles[17].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[17].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[17].styles[2]": "Background:=$Background",
"controlStyles[17].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[18].target": "WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement#VirtualDesktopBar",
"controlStyles[18].styles[0]": "CornerRadius=$CornerRadius",
"controlStyles[18].styles[1]": "Background:=$Background",
"controlStyles[19].target": "Border#BackgroundDimmingLayer",
"controlStyles[19].styles[0]": "Background:=$Background",
"controlStyles[19].styles[1]": "CornerRadius=$CornerRadius",
"controlStyles[20].target": "Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel > Border#BackgroundElement",
"controlStyles[20].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[20].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[21].target": "Taskbar.TaskListButton#TaskListButton",
"controlStyles[21].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[21].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[22].target": "Border#SnapBarBorder",
"controlStyles[22].styles[0]": "Background:=$Background",
"controlStyles[22].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[22].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[22].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[22].styles[4]": "Margin=2",
"controlStyles[23].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Border#BackgroundElement",
"controlStyles[23].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[23].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[23].styles[2]": "Background@ActiveNormal:=$ActiveBG",
"controlStyles[23].styles[3]": "Background@ActivePointerOver:=$ActiveBG",
"controlStyles[23].styles[4]": "Background@ActivePressed:=$ActiveBG",
"controlStyles[23].styles[5]": "Background@InactivePointerOver:=$ElementBG",
"controlStyles[23].styles[6]": "Background@InactivePressed:=$ElementBG",
"controlStyles[23].styles[7]": "BorderBrush@ActiveNormal:=$ElementBorderBrush",
"controlStyles[23].styles[8]": "BorderBrush@ActivePointerOver:=$ElementBorderBrush",
"controlStyles[23].styles[9]": "BorderBrush@ActivePressed:=$ElementBorderBrush",
"controlStyles[23].styles[10]": "BorderBrush@InactivePointerOver:=$ElementBorderBrush",
"controlStyles[23].styles[11]": "BorderBrush@InactivePressed:=$ElementBorderBrush",
"controlStyles[23].styles[12]": "Margin=1",
"controlStyles[24].target": "ContentPresenter#ContentPresenter@CommonStates",
"controlStyles[24].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[24].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[24].styles[2]": "Background@ActiveNormal:=$ActiveBG",
"controlStyles[24].styles[3]": "Background@ActivePointerOver:=$ActiveBG",
"controlStyles[24].styles[4]": "Background@ActivePressed:=$ActiveBG",
"controlStyles[24].styles[5]": "Background@InactivePointerOver:=$ElementBG",
"controlStyles[24].styles[6]": "Background@InactivePressed:=$ElementBG",
"controlStyles[24].styles[7]": "BorderBrush@ActiveNormal:=$ElementBorderBrush",
"controlStyles[24].styles[8]": "BorderBrush@ActivePointerOver:=$ElementBorderBrush",
"controlStyles[24].styles[9]": "BorderBrush@ActivePressed:=$ElementBorderBrush",
"controlStyles[24].styles[10]": "BorderBrush@InactivePointerOver:=$ElementBorderBrush",
"controlStyles[24].styles[11]": "BorderBrush@InactivePressed:=$ElementBorderBrush",
"controlStyles[24].styles[12]": "Margin=1",
"controlStyles[25].target": "Border#SnapPickerBorder",
"controlStyles[25].styles[0]": "Background:=$Background",
"controlStyles[25].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[25].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[25].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[25].styles[4]": "Margin=2",
"controlStyles[26].target": "Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
"controlStyles[26].styles[0]": "Background:=Transparent",
"controlStyles[27].target": "ToolTip > ContentPresenter#LayoutRoot",
"controlStyles[27].styles[0]": "Background:=$Background",
"controlStyles[27].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[27].styles[2]": "BorderThickness:=$BorderThickness",
"controlStyles[27].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[28].target": "WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement > Grid#GridElement > Border#VirtualDesktopSwitcherBackground",
"controlStyles[28].styles[0]": "BorderBrush:=$BorderBrush",
"controlStyles[28].styles[1]": "BorderThickness=$BorderThickness",
"controlStyles[28].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[28].styles[3]": "Background=$Background",
"controlStyles[29].target": "WindowsInternal.ComposableShell.Experiences.Switcher.SwitchItemListViewItem > Grid > Border",
"controlStyles[29].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[30].target": "Border#VirtualDesktopBarBackground",
"controlStyles[30].styles[0]": "Background:=$Background",
"controlStyles[30].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[30].styles[2]": "BorderThickness=$BorderThickness",
"controlStyles[30].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[31].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Border#BackgroundElement",
"controlStyles[31].styles[0]": "Background:=$ElementBG",
"controlStyles[31].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[31].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[31].styles[3]": "CornerRadius=$ElementCornerRadius",
"controlStyles[32].target": "Rectangle#RunningIndicator",
"controlStyles[32].styles[0]": "Visibility=1",
"controlStyles[33].target": "Rectangle#ShowDesktopPipe",
"controlStyles[33].styles[0]": "Visibility=1",
"controlStyles[34].target": "Rectangle#RightOverflowButtonDivider",
"controlStyles[34].styles[0]": "Visibility=1",
"controlStyles[35].target": "SearchUx.SearchUI.SearchIconButton > SearchUx.SearchUI.SearchButtonRootGrid@CommonStates > Border#BackgroundElement",
"controlStyles[35].styles[0]": "Background:=Transparent",
"controlStyles[35].styles[1]": "BorderBrush:=Transparent",
"controlStyles[36].target": "SearchUx.SearchUI.SearchButtonRootGrid",
"controlStyles[36].styles[0]": "Background:=Transparent",
"controlStyles[36].styles[1]": "BorderBrush:=Transparent",
"controlStyles[37].target": "Border#SearchPillBackgroundElement",
"controlStyles[37].styles[0]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[37].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[37].styles[2]": "CornerRadius=$ElementCornerRadius",
"controlStyles[37].styles[3]": "Margin=0,1",
"controlStyles[38].target": "SearchUx.SearchUI.SearchBoxButton > SearchUx.SearchUI.SearchButtonRootGrid@CommonStates > Border#BackgroundElement",
"controlStyles[38].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[38].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[38].styles[2]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[38].styles[3]": "Background:=$ElementBG",
"controlStyles[38].styles[4]": "Margin=0,-4",
"controlStyles[39].target": "Canvas#HoverFlyoutCanvas > Grid#HoverFlyoutGrid > Border#HoverFlyoutBackground",
"controlStyles[39].styles[0]": "Shadow:=",
"controlStyles[39].styles[1]": "Background:=$Background",
"controlStyles[39].styles[2]": "BorderBrush:=$BorderBrush",
"controlStyles[39].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[39].styles[4]": "CornerRadius=$CornerRadius",
"controlStyles[40].target": "Border#BackgroundElement",
"controlStyles[40].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[40].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[40].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[40].styles[3]": "Background:=$ElementBG",
"controlStyles[41].target": "// Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Border#BackgroundElement",
"controlStyles[41].styles[0]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[41].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[41].styles[2]": "CornerRadius=$ElementCornerRadius",
"controlStyles[41].styles[3]": "Padding=18",
"controlStyles[41].styles[4]": "Background@Normal:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Normal.png\" />",
"controlStyles[41].styles[5]": "Background@PointerOver:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Hover.png\" />",
"controlStyles[41].styles[6]": "Background@Pressed:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Pressed.png\" />",
"controlStyles[41].styles[7]": "// This section is on hold until I have the correct images and have fleshed out the correct method to add them.",
"controlStyles[42].target": "// Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Microsoft.UI.Xaml.Controls.AnimatedVisualPlayer#Icon",
"controlStyles[42].styles[0]": "Visibility=1",
"controlStyles[42].styles[1]": "// This section is on hold until I have the correct images and have fleshed out the correct method to add them.",
"controlStyles[43].target": "SystemTray.SystemTrayFrame",
"controlStyles[43].styles[0]": "HorizontalAlignment=Right",
"controlStyles[44].target": "Grid#AugmentedEntryPointContentGrid",
"controlStyles[44].styles[0]": "HorizontalAlignment=Left",
"styleConstants[0]": "BorderThickness=0.3,1,0.3,0.3",
"styleConstants[1]": "ElementBorderThickness=0.3,0.3,0.3,1",
"styleConstants[2]": "Background=<WindhawkBlur BlurAmount=\"15\" TintColor=\"#25323232\" TintOpacity=\"0.2\" />",
"styleConstants[3]": "BorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"0.0\" /><GradientStop Color=\"#50404040\" Offset=\"0.25\" /><GradientStop Color=\"#50808080\" Offset=\"1\" /></LinearGradientBrush>",
"styleConstants[4]": "GlassBG=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeAltHighColor}\" TintOpacity=\"0.3\" FallbackColor=\"{ThemeResource SystemChromeAltHighColor}\" />",
"styleConstants[5]": "GlassBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"0.0\" /><GradientStop Color=\"{ThemeResource SystemChromeLowColor}\" Offset=\"0.25\" /><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"1\" /></LinearGradientBrush>",
"styleConstants[6]": "ElementBG=<WindhawkBlur BlurAmount=\"20\" TintColor=\"#202020\" TintOpacity=\"0.2\" />",
"styleConstants[7]": "ActiveBG=<WindhawkBlur BlurAmount=\"40\" TintColor=\"#FFFFFF\" TintOpacity=\"Opacity=\"0.8\" />",
"styleConstants[8]": "ElementBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"1\" /><GradientStop Color=\"#50606060\" Offset=\"0.15\" /></LinearGradientBrush>",
"styleConstants[9]": "CornerRadius=10",
"styleConstants[10]": "ElementCornerRadius=6",
"resourceVariables[0].variableKey": "",
"resourceVariables[0].value": ""
}
```

</details>

---

### Full Width Taskbar
This theme also includes a full width variant.

<img src="Full-Width-Preview.png" width="100%" height="auto" />

* Open the `Windows 11 Taskbar Styler` mod in Windhawk.
* Go to the `Advanced` tab and copy the code below into the `Mod settings` box and click `save`.

<details>
<summary>Content to import (click to expand)</summary>

```json
{
"theme": "",
"controlStyles[0].target": "Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid",
"controlStyles[0].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[0].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[0].styles[2]": "Background:=$Background",
"controlStyles[1].target": "Rectangle#BackgroundFill",
"controlStyles[1].styles[0]": "Visibility=1",
"controlStyles[2].target": "Rectangle#BackgroundStroke",
"controlStyles[2].styles[0]": "Visibility=1",
"controlStyles[3].target": "Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
"controlStyles[3].styles[0]": "Margin=-2,0",
"controlStyles[4].target": "Grid#SystemTrayFrameGrid",
"controlStyles[4].styles[0]": "Background:=$ElementBG",
"controlStyles[4].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[4].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[4].styles[3]": "CornerRadius=$ElementCornerRadius",
"controlStyles[4].styles[4]": "Margin=4",
"controlStyles[5].target": "SystemTray.ChevronIconView",
"controlStyles[5].styles[0]": "CornerRadius=$CornerRadius",
"controlStyles[6].target": "SystemTray.NotifyIconView#NotifyItemIcon",
"controlStyles[6].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[7].target": "SystemTray.OmniButton",
"controlStyles[7].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[8].target": "SystemTray.IconView#SystemTrayIcon > Grid#ContainerGrid > ContentPresenter#ContentPresenter > Grid#ContentGrid > SystemTray.TextIconContent > Grid#ContainerGrid",
"controlStyles[8].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[9].target": "Taskbar.Gripper#GripperControl",
"controlStyles[9].styles[0]": "Width=Auto",
"controlStyles[9].styles[1]": "MinWidth=24",
"controlStyles[9].styles[2]": "HorizontalAlignment=Left",
"controlStyles[10].target": "TextBlock#TimeInnerTextBlock",
"controlStyles[10].styles[0]": "FontSize=13",
"controlStyles[10].styles[1]": "FontFamily=vivo Sans EN VF",
"controlStyles[10].styles[2]": "Margin=0",
"controlStyles[10].styles[3]": "Padding=0",
"controlStyles[10].styles[4]": "RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />",
"controlStyles[11].target": "TextBlock#DateInnerTextBlock",
"controlStyles[11].styles[0]": "Visibility=1",
"controlStyles[12].target": "TextBlock#InnerTextBlock[Text=]",
"controlStyles[12].styles[0]": "Text=",
"controlStyles[13].target": "TextBlock#SearchBoxTextBlock",
"controlStyles[13].styles[0]": "Text=Search This PC",
"controlStyles[13].styles[1]": "FontSize=10",
"controlStyles[13].styles[2]": "FontFamily=vivo Sans EN VF",
"controlStyles[14].target": "SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon > Grid > Grid > SystemTray.TextIconContent",
"controlStyles[14].styles[0]": "Visibility=1",
"controlStyles[15].target": "Border#OverflowFlyoutBackgroundBorder",
"controlStyles[15].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[15].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[15].styles[2]": "Background:=$Background",
"controlStyles[15].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[16].target": "WindowsInternal.ComposableShell.Experiences.Switcher.AltTab > Grid#ModalRootGrid > Border",
"controlStyles[16].styles[0]": "BorderThickness=$BorderThickness",
"controlStyles[16].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[16].styles[2]": "Background:=$Background",
"controlStyles[16].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[17].target": "WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement#VirtualDesktopBar",
"controlStyles[17].styles[0]": "CornerRadius=$CornerRadius",
"controlStyles[17].styles[1]": "Background:=$Background",
"controlStyles[18].target": "Border#BackgroundDimmingLayer",
"controlStyles[18].styles[0]": "Background:=$Background",
"controlStyles[18].styles[1]": "CornerRadius=$CornerRadius",
"controlStyles[19].target": "Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel > Border#BackgroundElement",
"controlStyles[19].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[19].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[20].target": "Taskbar.TaskListButton#TaskListButton",
"controlStyles[20].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[20].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[21].target": "Border#SnapBarBorder",
"controlStyles[21].styles[0]": "Background:=$Background",
"controlStyles[21].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[21].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[21].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[21].styles[4]": "Margin=2",
"controlStyles[22].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Border#BackgroundElement",
"controlStyles[22].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[22].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[22].styles[2]": "Background@ActiveNormal:=$ActiveBG",
"controlStyles[22].styles[3]": "Background@ActivePointerOver:=$ActiveBG",
"controlStyles[22].styles[4]": "Background@ActivePressed:=$ActiveBG",
"controlStyles[22].styles[5]": "Background@InactivePointerOver:=$ElementBG",
"controlStyles[22].styles[6]": "Background@InactivePressed:=$ElementBG",
"controlStyles[22].styles[7]": "BorderBrush@ActiveNormal:=$ElementBorderBrush",
"controlStyles[22].styles[8]": "BorderBrush@ActivePointerOver:=$ElementBorderBrush",
"controlStyles[22].styles[9]": "BorderBrush@ActivePressed:=$ElementBorderBrush",
"controlStyles[22].styles[10]": "BorderBrush@InactivePointerOver:=$ElementBorderBrush",
"controlStyles[22].styles[11]": "BorderBrush@InactivePressed:=$ElementBorderBrush",
"controlStyles[22].styles[12]": "Margin=1",
"controlStyles[23].target": "ContentPresenter#ContentPresenter@CommonStates",
"controlStyles[23].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[23].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[23].styles[2]": "Background@ActiveNormal:=$ActiveBG",
"controlStyles[23].styles[3]": "Background@ActivePointerOver:=$ActiveBG",
"controlStyles[23].styles[4]": "Background@ActivePressed:=$ActiveBG",
"controlStyles[23].styles[5]": "Background@InactivePointerOver:=$ElementBG",
"controlStyles[23].styles[6]": "Background@InactivePressed:=$ElementBG",
"controlStyles[23].styles[7]": "BorderBrush@ActiveNormal:=$ElementBorderBrush",
"controlStyles[23].styles[8]": "BorderBrush@ActivePointerOver:=$ElementBorderBrush",
"controlStyles[23].styles[9]": "BorderBrush@ActivePressed:=$ElementBorderBrush",
"controlStyles[23].styles[10]": "BorderBrush@InactivePointerOver:=$ElementBorderBrush",
"controlStyles[23].styles[11]": "BorderBrush@InactivePressed:=$ElementBorderBrush",
"controlStyles[23].styles[12]": "Margin=1",
"controlStyles[24].target": "Border#SnapPickerBorder",
"controlStyles[24].styles[0]": "Background:=$Background",
"controlStyles[24].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[24].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[24].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[24].styles[4]": "Margin=2",
"controlStyles[25].target": "Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
"controlStyles[25].styles[0]": "Background:=Transparent",
"controlStyles[26].target": "ToolTip > ContentPresenter#LayoutRoot",
"controlStyles[26].styles[0]": "Background:=$Background",
"controlStyles[26].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[26].styles[2]": "BorderThickness:=$BorderThickness",
"controlStyles[26].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[27].target": "WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement > Grid#GridElement > Border#VirtualDesktopSwitcherBackground",
"controlStyles[27].styles[0]": "BorderBrush:=$BorderBrush",
"controlStyles[27].styles[1]": "BorderThickness=$BorderThickness",
"controlStyles[27].styles[2]": "CornerRadius=$CornerRadius",
"controlStyles[27].styles[3]": "Background=$Background",
"controlStyles[28].target": "WindowsInternal.ComposableShell.Experiences.Switcher.SwitchItemListViewItem > Grid > Border",
"controlStyles[28].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[29].target": "Border#VirtualDesktopBarBackground",
"controlStyles[29].styles[0]": "Background:=$Background",
"controlStyles[29].styles[1]": "BorderBrush:=$BorderBrush",
"controlStyles[29].styles[2]": "BorderThickness=$BorderThickness",
"controlStyles[29].styles[3]": "CornerRadius=$CornerRadius",
"controlStyles[30].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Border#BackgroundElement",
"controlStyles[30].styles[0]": "Background:=$ElementBG",
"controlStyles[30].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[30].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[30].styles[3]": "CornerRadius=$ElementCornerRadius",
"controlStyles[31].target": "Rectangle#RunningIndicator",
"controlStyles[31].styles[0]": "Visibility=1",
"controlStyles[32].target": "Rectangle#ShowDesktopPipe",
"controlStyles[32].styles[0]": "Visibility=1",
"controlStyles[33].target": "Rectangle#RightOverflowButtonDivider",
"controlStyles[33].styles[0]": "Visibility=1",
"controlStyles[34].target": "SearchUx.SearchUI.SearchIconButton > SearchUx.SearchUI.SearchButtonRootGrid@CommonStates > Border#BackgroundElement",
"controlStyles[34].styles[0]": "Background:=Transparent",
"controlStyles[34].styles[1]": "BorderBrush:=Transparent",
"controlStyles[35].target": "SearchUx.SearchUI.SearchButtonRootGrid",
"controlStyles[35].styles[0]": "Background:=Transparent",
"controlStyles[35].styles[1]": "BorderBrush:=Transparent",
"controlStyles[36].target": "Border#SearchPillBackgroundElement",
"controlStyles[36].styles[0]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[36].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[36].styles[2]": "CornerRadius=$ElementCornerRadius",
"controlStyles[36].styles[3]": "Margin=0,1",
"controlStyles[37].target": "SearchUx.SearchUI.SearchBoxButton > SearchUx.SearchUI.SearchButtonRootGrid@CommonStates > Border#BackgroundElement",
"controlStyles[37].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[37].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[37].styles[2]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[37].styles[3]": "Background:=$ElementBG",
"controlStyles[37].styles[4]": "Margin=0,-4",
"controlStyles[38].target": "Canvas#HoverFlyoutCanvas > Grid#HoverFlyoutGrid > Border#HoverFlyoutBackground",
"controlStyles[38].styles[0]": "Shadow:=",
"controlStyles[38].styles[1]": "Background:=$Background",
"controlStyles[38].styles[2]": "BorderBrush:=$BorderBrush",
"controlStyles[38].styles[3]": "BorderThickness=$BorderThickness",
"controlStyles[38].styles[4]": "CornerRadius=$CornerRadius",
"controlStyles[39].target": "Border#BackgroundElement",
"controlStyles[39].styles[0]": "CornerRadius=$ElementCornerRadius",
"controlStyles[39].styles[1]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[39].styles[2]": "BorderThickness=$ElementBorderThickness",
"controlStyles[39].styles[3]": "Background:=$ElementBG",
"controlStyles[40].target": "// Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Border#BackgroundElement",
"controlStyles[40].styles[0]": "BorderBrush:=$ElementBorderBrush",
"controlStyles[40].styles[1]": "BorderThickness=$ElementBorderThickness",
"controlStyles[40].styles[2]": "CornerRadius=$ElementCornerRadius",
"controlStyles[40].styles[3]": "Padding=18",
"controlStyles[40].styles[4]": "Background@Normal:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Normal.png\" />",
"controlStyles[40].styles[5]": "Background@PointerOver:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Hover.png\" />",
"controlStyles[40].styles[6]": "Background@Pressed:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"C:\\Resources\\Icons\\Start Orbs\\Windows Glass\\Pressed.png\" />",
"controlStyles[40].styles[7]": "// This section is on hold until I have the correct images and have fleshed out the correct method to add them.",
"controlStyles[41].target": "// Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Microsoft.UI.Xaml.Controls.AnimatedVisualPlayer#Icon",
"controlStyles[41].styles[0]": "Visibility=1",
"controlStyles[41].styles[1]": "// This section is on hold until I have the correct images and have fleshed out the correct method to add them.",
"styleConstants[0]": "BorderThickness=0.3,1,0.3,0.3",
"styleConstants[1]": "ElementBorderThickness=0.3,0.3,0.3,1",
"styleConstants[2]": "Background=<WindhawkBlur BlurAmount=\"15\" TintColor=\"#25323232\" TintOpacity=\"0.2\" />",
"styleConstants[3]": "BorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"0.0\" /><GradientStop Color=\"#50404040\" Offset=\"0.25\" /><GradientStop Color=\"#50808080\" Offset=\"1\" /></LinearGradientBrush>",
"styleConstants[4]": "GlassBG=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeAltHighColor}\" TintOpacity=\"0.3\" FallbackColor=\"{ThemeResource SystemChromeAltHighColor}\" />",
"styleConstants[5]": "GlassBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"0.0\" /><GradientStop Color=\"{ThemeResource SystemChromeLowColor}\" Offset=\"0.25\" /><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"1\" /></LinearGradientBrush>",
"styleConstants[6]": "ElementBG=<WindhawkBlur BlurAmount=\"20\" TintColor=\"#202020\" TintOpacity=\"0.2\" />",
"styleConstants[7]": "ActiveBG=<WindhawkBlur BlurAmount=\"40\" TintColor=\"#FFFFFF\" TintOpacity=\"Opacity=\"0.8\" />",
"styleConstants[8]": "ElementBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"1\" /><GradientStop Color=\"#50606060\" Offset=\"0.15\" /></LinearGradientBrush>",
"styleConstants[9]": "CornerRadius=10",
"styleConstants[10]": "ElementCornerRadius=6",
"resourceVariables[0].variableKey": "",
"resourceVariables[0].value": ""
}
```

</details>

---

### Taskbar Clock Customization (Optional)

* Open the `Taskbar Clock Customization` mod in Windhawk.
* Go to the `Advanced` tab and copy the code below into the `Mod settings` box and click `save`.

<details>
<summary>Content to import (click to expand)</summary>

```json
{
"ShowSeconds": 0,
"TimeFormat": "hh':'mm tt",
"DateFormat": "MMM dd",
"WeekdayFormat": "dddd",
"WeekdayFormatCustom": "Sun, Mon, Tue, Wed, Thu, Fri, Sat",
"TopLine": "📅 %date% 🕒 %time%",
"BottomLine": "%web1%",
"MiddleLine": "%weekday%",
"TooltipLine": "%web1_full%%n%%n%%media_status% %media_artist% - %media_title%",
"TooltipLineMode": "append",
"Width": 180,
"Height": 60,
"MaxWidth": 0,
"TextSpacing": 0,
"DataCollection.NetworkMetricsFormat": "mbsDynamic",
"DataCollection.NetworkMetricsFixedDecimals": -1,
"DataCollection.PercentageFormat": "spacePaddingAndSymbol",
"DataCollection.UpdateInterval": 1,
"DataCollection.NetworkAdapterName": "",
"DataCollection.GpuAdapterName": "",
"MediaPlayer.IgnoredPlayers[0]": "",
"MediaPlayer.MaxLength": 28,
"MediaPlayer.NoMediaText": "No media",
"MediaPlayer.RemoveBrackets": 1,
"WebContentWeatherLocation": "",
"WebContentWeatherFormat": "%c 🌡️%t 🌬️%w",
"WebContentWeatherUnits": "autoDetect",
"WebContentsItems[0].Url": "https://rss.nytimes.com/services/xml/rss/nyt/World.xml",
"WebContentsItems[0].BlockStart": "<item>",
"WebContentsItems[0].Start": "<title>",
"WebContentsItems[0].End": "</title>",
"WebContentsItems[0].ContentMode": "xmlHtml",
"WebContentsItems[0].SearchReplace[0].Search": "",
"WebContentsItems[0].SearchReplace[0].Replace": "",
"WebContentsItems[0].MaxLength": 28,
"WebContentsUpdateInterval": 10,
"TimeZones[0]": "",
"TimeStyle.Hidden": 0,
"TimeStyle.TextColor": "",
"TimeStyle.TextAlignment": "Center",
"TimeStyle.FontSize": 0,
"TimeStyle.FontFamily": "",
"TimeStyle.FontWeight": "",
"TimeStyle.FontStyle": "",
"TimeStyle.FontStretch": "",
"TimeStyle.CharacterSpacing": 0,
"DateStyle.Hidden": 0,
"DateStyle.TextColor": "",
"DateStyle.TextAlignment": "Center",
"DateStyle.FontSize": 0,
"DateStyle.FontFamily": "",
"DateStyle.FontWeight": "",
"DateStyle.FontStyle": "",
"DateStyle.FontStretch": "",
"DateStyle.CharacterSpacing": 0,
"oldTaskbarOnWin11": 0
}
```

</details>

---

### Taskbar tray system icon tweaks (Optional)

* Open the `Taskbar tray system icon tweaks` mod in Windhawk.
* Go to the `Advanced` tab and copy the code below into the `Mod settings` box and click `save`.

<details>
<summary>Content to import (click to expand)</summary>

```json
{
"hideVolumeIcon": 0,
"hideNetworkIcon": 0,
"hideBatteryIcon": 0,
"hideMicrophoneIcon": 0,
"hideGeolocationIcon": 1,
"hideStudioEffectsIcon": 1,
"hideLanguageBar": 1,
"hideLanguageSupplementaryIcons": 1,
"hideBellIcon": "whenInactiveAndNoDnd",
"showDesktopButtonWidth": 12
}
```

</details>

---

### Taskbar Music Lounge - Fork (Optional)
Optional feature to add a native music player widget to the taskbar. Replaces the taskbar widgets pane.  
Uses a forked version of the Taskbar Music Lounge with various tweaks and improvements in place of the official.

<img src="Taskbar-Music-Lounge-Preview.png" width="100%" height="auto" />

#### Installation

- Got to `Windhawk > Settings` and turn on Developer mode.
- Return to `Windhawk > Home` and click the `Create a New Mod` button on the bottom right of the window.
- Copy and paste the code below into the `mod.wh.cpp` window that opens. *(make sure to overwrite all code in the window with the code below)*.
- Click `Compile` and wait for it to finish compiling. Then click `Exit Editing Mode`. *(If the `Taskbar Music Lounge - Fork` mod isn't enabled at this point, enable it)*.

<details>
<summary>Content to import (click to expand)</summary>

```cpp
// ==WindhawkMod==
// @id              taskbar-music-lounge-fork
// @name            Taskbar Music Lounge - Fork
// @description     A native-style music ticker with media controls.
// @version         4.6.2
// @author          Hashah2311
// @github          https://github.com/Hashah2311
// @include         explorer.exe
// @compilerOptions -lole32 -ldwmapi -lgdi32 -luser32 -lwindowsapp -lshcore -lgdiplus -lshell32 -lpsapi
// ==/WindhawkMod==

// ==WindhawkModReadme==
/*
# Taskbar Music Lounge (v4.6.2)

A media controller that uses Windows 11 native DWM styling for a seamless look.

## ✨ Features
* **Universal Support:** Works with any media player via GSMTC.
* **Album Art:** Displays current track cover art.
* **Native Look:** Uses Windows 11 hardware-accelerated rounding and acrylic blur.
* **Controls:** Play/Pause, Next, Previous.
* **Volume:** Scroll over widget to adjust volume.
* **--------------------------------- Cinabutts Enhancements: ---------------------------------**
* **True High-DPI Support:** Automatically scales UI elements to look perfect on 4K/1440p monitors.
* **Smart Game Detection:** Automatically hides when playing Fullscreen games.
* **Whitelist:** Keep the widget visible in specific Fullscreen apps (e.g., Firefox).
* **Slide Animations:** Smoothly slides out AND back in when entering/exiting games.
* **Smart Docking:** Sits unobtrusively at the screen edge on boot/shutdown or if Explorer crashes.
* **Advanced Background Control:** Manually override Background RGB - Toggle Auto/Invert themes, etc.

## ⚠️ Requirements
* **Disable Widgets:** Taskbar Settings -> Widgets -> Off.
* **Windows 11:** Required for rounded corners.
*/
// ==/WindhawkModReadme==

// ==WindhawkModSettings==
/*
- PanelWidth: 300
  $name: Panel Width
- PanelHeight: 35
  $name: Panel Height
- FontSize: 11
  $name: Font Size
- OffsetX: 140
  $name: X Offset
- OffsetY: 0
  $name: Y Offset
- AutoTheme: true
  $name: Auto Theme
  $description: ✓ Enabled | B/W  Text & Icons based on System Light/Dark mode. ✕ Disabled | Use Custom theme below ↓
- InvertTheme: false
  $name: Invert System Light/Dark (Background)
  $description: ✓ Enabled | Dark Background. ✕ Disabled | Light Background. (Auto Theme must be OFF)
- BgColor: "0, 0, 0"
  $name: Manual Background Color Override (R, G, B)
  $description: Set to 0,0,0 to not override. Enter RGB values separated by commas (e.g; "102, 255, 255"). Alpha controlled below ↓
- BgOpacity: 0
  $name: Acrylic Tint Opacity (0-255).
  $description: Keep 0 for pure glass. Controls Alpha for Manual Background Color.
- TextColor: "255, 255, 255"
  $name: Manual Text Color (R, G, B, [A])
  $description: Enter RGB or RGBA values separated by commas (e.g; "102, 255, 255" or "255, 0, 0, 128")
- EnableSlide: true
  $name: Enable Slide Animations
  $description: ✓ Enabled | the widget slides down/up for games. ✕ Disabled | Instantly hides.
- EnableGameDetection: true
  $name: Enable Game Detection
  $description: ✓ Enabled | Widget hides on game detection. ✕ Disabled | The widget will NEVER hide for games. (overrides all below ↓)
- FullscreenCheckInterval: 2
  $name: Fullscreen Check Interval (Seconds)
  $description: How often to check for borderless games.
- IgnoredApps: firefox.exe;chrome.exe;msedge.exe;vlc.exe
  $name: Fullscreen Whitelist
  $description: Semicolon-separated list of executables to IGNORE (keep widget visible).
*/
// ==/WindhawkModSettings==

#include <windows.h>
#include <shellapi.h>
#include <dwmapi.h>
#include <gdiplus.h>
#include <shcore.h> 
#include <string>
#include <vector>
#include <atomic>
#include <thread>
#include <mutex>
#include <cstdio>
#include <psapi.h>
#include <shobjidl.h>

// WinRT
#include <winrt/Windows.Foundation.h>
#include <winrt/Windows.Media.Control.h>
#include <winrt/Windows.Storage.Streams.h>

using namespace Gdiplus;
using namespace std;
using namespace winrt;
using namespace Windows::Media::Control;
using namespace Windows::Storage::Streams;

// --- Constants ---
const WCHAR* FONT_NAME = L"Segoe UI Variable Display"; 

// --- DWM API ---
typedef enum _WINDOWCOMPOSITIONATTRIB { WCA_ACCENT_POLICY = 19 } WINDOWCOMPOSITIONATTRIB;
typedef enum _ACCENT_STATE {
    ACCENT_DISABLED = 0,
    ACCENT_ENABLE_BLURBEHIND = 3,
    ACCENT_ENABLE_ACRYLICBLURBEHIND = 4, 
    ACCENT_INVALID_STATE = 5
} ACCENT_STATE;
typedef struct _ACCENT_POLICY {
    ACCENT_STATE AccentState;
    DWORD AccentFlags;
    DWORD GradientColor;
    DWORD AnimationId;
} ACCENT_POLICY;
typedef struct _WINDOWCOMPOSITIONATTRIBDATA {
    WINDOWCOMPOSITIONATTRIB Attribute;
    PVOID Data;
    SIZE_T SizeOfData;
} WINDOWCOMPOSITIONATTRIBDATA;
typedef BOOL(WINAPI* pSetWindowCompositionAttribute)(HWND, WINDOWCOMPOSITIONATTRIBDATA*);

// --- Z-Band API ---
typedef HWND(WINAPI* pCreateWindowInBand)(DWORD, LPCWSTR, LPCWSTR, DWORD, int, int, int, int, HWND, HMENU, HINSTANCE, LPVOID, DWORD);
enum ZBID { ZBID_IMMERSIVE_NOTIFICATION = 4 };

// --- Configurable State ---
struct ModSettings {
    int width = 300;
    int height = 35;
    int fontSize = 11;
    int offsetX = 140;
    int offsetY = 0;
    bool autoTheme = true;
    bool invertTheme = false;
    DWORD manualTextColor = 0xFFFFFFFF; 
    DWORD manualBgColorRGB = 0; // Stores BGR for DWM
    int bgOpacity = 0;
    int fsInterval = 2;
    bool enableSlide = true;
    bool enableGameDetect = true;
    wstring ignoredApps;
} g_Settings;

// --- Global State ---
HWND g_hMediaWindow = NULL;
HWND g_hTaskbar = NULL;
HWINEVENTHOOK g_hVisibilityHook = NULL;
bool g_Running = true; 
int g_HoverState = 0; 
float g_ScaleFactor = 1.0f; // DPI Scale

// Detection & Animation State
bool g_IsGameDetected = false;
int g_FsCheckTick = 0;
int g_AnimState = 0; // 0=Sync, 1=Hiding, 2=Showing, 3=Shutdown/Parked
int g_CurrentAnimY = 0;
bool g_ShutdownMode = false;

struct MediaState {
    wstring title = L"Waiting for media...";
    wstring artist = L"";
    bool isPlaying = false;
    bool hasMedia = false;
    Bitmap* albumArt = nullptr;
    mutex lock;
} g_MediaState;

int g_ScrollOffset = 0;
int g_TextWidth = 0;
bool g_IsScrolling = false;
int g_ScrollWait = 60;

// --- Helper: Whitelist Check ---
bool IsAppIgnored(HWND hFg) {
    if (!hFg) return false;
    DWORD pid = 0;
    GetWindowThreadProcessId(hFg, &pid);
    if (pid == 0) return false;

    HANDLE hProcess = OpenProcess(PROCESS_QUERY_LIMITED_INFORMATION, FALSE, pid);
    if (!hProcess) return false;

    WCHAR buffer[MAX_PATH];
    bool match = false;
    if (GetModuleFileNameExW(hProcess, NULL, buffer, MAX_PATH)) {
        wstring fullPath = buffer;
        size_t lastSlash = fullPath.find_last_of(L"\\");
        wstring exeName = (lastSlash == wstring::npos) ? fullPath : fullPath.substr(lastSlash + 1);
        
        for (auto & c: exeName) c = tolower(c);
        wstring list = g_Settings.ignoredApps;
        for (auto & c: list) c = tolower(c);
        
        if (list.find(exeName) != wstring::npos) match = true;
    }
    CloseHandle(hProcess);
    return match;
}

// --- Sync Logic ---

bool CheckBorderlessFullscreen() {
    HWND hFg = GetForegroundWindow();
    if (!hFg || hFg == GetDesktopWindow() || hFg == GetShellWindow()) return false;
    if (IsAppIgnored(hFg)) return false;

    WCHAR clsName[256];
    GetClassNameW(hFg, clsName, 256);
    if (wcscmp(clsName, L"WorkerW") == 0 || wcscmp(clsName, L"Progman") == 0) return false;

    HMONITOR hMon = MonitorFromWindow(hFg, MONITOR_DEFAULTTOPRIMARY);
    MONITORINFO mi = { sizeof(mi) };
    if (!GetMonitorInfo(hMon, &mi)) return false;

    RECT rcWin;
    GetWindowRect(hFg, &rcWin);

    return (rcWin.left <= mi.rcMonitor.left && 
            rcWin.top <= mi.rcMonitor.top && 
            rcWin.right >= mi.rcMonitor.right && 
            rcWin.bottom >= mi.rcMonitor.bottom);
}

#define IDT_VIS_ANIM 1003

void UpdateScaleFactor() {
    if (g_hTaskbar) {
        UINT dpi = GetDpiForWindow(g_hTaskbar);
        if (dpi == 0) dpi = 96;
        g_ScaleFactor = dpi / 96.0f;
    }
}

void ForceParkedState() {
    int screenH = GetSystemMetrics(SM_CYSCREEN);
    SetWindowPos(g_hMediaWindow, HWND_TOPMOST, 0, screenH - 2, g_Settings.width, g_Settings.height, SWP_NOACTIVATE | SWP_SHOWWINDOW);
    g_AnimState = 3; // Parked Mode
}

void SyncPositionWithTaskbar() {
    if (!g_hMediaWindow || g_ShutdownMode) return;
    
    // 1. Startup / Crash Recovery
    if (!g_hTaskbar || !IsWindow(g_hTaskbar)) {
        g_hTaskbar = FindWindowW(L"Shell_TrayWnd", NULL);
        if (!g_hTaskbar) {
            if (g_AnimState != 3) ForceParkedState();
            return;
        }
    }

    if (g_hTaskbar) {
        UpdateScaleFactor(); 

        // --- 2. Smart Fullscreen Detection ---
        bool shouldHide = false;
        
        if (g_Settings.enableGameDetect) {
            if (IsAppIgnored(GetForegroundWindow())) {
                shouldHide = false;
                g_FsCheckTick = 0;
            } else {
                QUERY_USER_NOTIFICATION_STATE qState;
                if (SHQueryUserNotificationState(&qState) == S_OK) {
                    if (qState == QUNS_RUNNING_D3D_FULL_SCREEN || 
                        qState == QUNS_PRESENTATION_MODE) {
                        shouldHide = true;
                        g_FsCheckTick = 0;
                    }
                }
                if (!shouldHide) {
                    g_FsCheckTick++;
                    if (g_FsCheckTick >= g_Settings.fsInterval) {
                        g_FsCheckTick = 0;
                        if (CheckBorderlessFullscreen()) shouldHide = true;
                    } else {
                        if (g_IsGameDetected) shouldHide = true;
                    }
                }
            }
        }

        g_IsGameDetected = shouldHide;

        // --- 3. Animation Logic ---
        if (g_AnimState == 1 || g_AnimState == 2) return; 

        BOOL isTaskbarVisible = IsWindowVisible(g_hTaskbar);
        
        // CASE: Hide
        if (!isTaskbarVisible || g_IsGameDetected) {
            if (g_AnimState != 1 && g_AnimState != 3) {
                if (g_Settings.enableSlide) {
                    RECT rcMe; GetWindowRect(g_hMediaWindow, &rcMe);
                    g_CurrentAnimY = rcMe.top;
                    g_AnimState = 1; // Hiding
                    SetTimer(g_hMediaWindow, IDT_VIS_ANIM, 16, NULL);
                } else {
                    ShowWindow(g_hMediaWindow, SW_HIDE);
                }
            }
            return;
        }

        // CASE: Restore
        if (g_AnimState == 3 || !IsWindowVisible(g_hMediaWindow)) {
            if (g_Settings.enableSlide) {
                 int screenH = GetSystemMetrics(SM_CYSCREEN);
                 g_CurrentAnimY = (g_AnimState == 3) ? (screenH - 2) : screenH; 
                 
                 RECT rcTb; GetWindowRect(g_hTaskbar, &rcTb);
                 int scaledOffX = (int)(g_Settings.offsetX * g_ScaleFactor);
                 int scaledW = (int)(g_Settings.width * g_ScaleFactor);
                 int scaledH = (int)(g_Settings.height * g_ScaleFactor);
                 int targetX = rcTb.left + scaledOffX;

                 SetWindowPos(g_hMediaWindow, HWND_TOPMOST, targetX, g_CurrentAnimY, scaledW, scaledH, SWP_NOACTIVATE | SWP_SHOWWINDOW);
                 g_AnimState = 2; // Showing
                 SetTimer(g_hMediaWindow, IDT_VIS_ANIM, 16, NULL);
                 return;
            } else {
                ShowWindow(g_hMediaWindow, SW_SHOWNOACTIVATE);
            }
        }

        // Normal Sync
        RECT rc;
        if (GetWindowRect(g_hTaskbar, &rc)) {
            int taskbarHeight = rc.bottom - rc.top;
            if (taskbarHeight <= 0) return; 

            int scaledW = (int)(g_Settings.width * g_ScaleFactor);
            int scaledH = (int)(g_Settings.height * g_ScaleFactor);
            int scaledOffX = (int)(g_Settings.offsetX * g_ScaleFactor);
            int scaledOffY = (int)(g_Settings.offsetY * g_ScaleFactor);

            int x = rc.left + scaledOffX; 
            int y = rc.top + (taskbarHeight / 2) - (scaledH / 2) + scaledOffY;

            SetWindowPos(g_hMediaWindow, HWND_TOPMOST, x, y, scaledW, scaledH, SWP_NOACTIVATE | SWP_SHOWWINDOW);
            g_AnimState = 0; // Synced
        }
    }
}

void CALLBACK WinEventProc(HWINEVENTHOOK hWinEventHook, DWORD event, HWND hwnd, LONG idObject, LONG idChild, DWORD dwEventThread, DWORD dwmsEventTime) {
    if (hwnd == g_hTaskbar && idObject == OBJID_WINDOW) {
        SyncPositionWithTaskbar();
    }
}

// --- Settings ---
void LoadSettings() {
    g_Settings.width = Wh_GetIntSetting(L"PanelWidth");
    g_Settings.height = Wh_GetIntSetting(L"PanelHeight");
    g_Settings.fontSize = Wh_GetIntSetting(L"FontSize");
    g_Settings.offsetX = Wh_GetIntSetting(L"OffsetX");
    g_Settings.offsetY = Wh_GetIntSetting(L"OffsetY");
    g_Settings.autoTheme = Wh_GetIntSetting(L"AutoTheme") != 0;
    g_Settings.invertTheme = Wh_GetIntSetting(L"InvertTheme") != 0;
    g_Settings.bgOpacity = Wh_GetIntSetting(L"BgOpacity");

    // Text Color (RGB/RGBA) -> GDI uses ARGB
    PCWSTR textColorStr = Wh_GetStringSetting(L"TextColor");
    if (textColorStr) {
        int r = 255, g = 255, b = 255, a = 255;
        int count = swscanf_s(textColorStr, L"%d,%d,%d,%d", &r, &g, &b, &a);
        if(r>255) r=255; if(g>255) g=255; if(b>255) b=255; if(a>255) a=255;
        if(r<0) r=0; if(g<0) g=0; if(b<0) b=0; if(a<0) a=0;
        
        if (count >= 3) {
            g_Settings.manualTextColor = ((DWORD)a << 24) | ((DWORD)r << 16) | ((DWORD)g << 8) | (DWORD)b;
        } else {
            g_Settings.manualTextColor = 0xFFFFFFFF;
        }
        Wh_FreeStringSetting(textColorStr);
    } else {
        g_Settings.manualTextColor = 0xFFFFFFFF;
    }

    // Bg Color (RGB Only) -> DWM uses ABGR (Swap R/B)
    PCWSTR bgColorStr = Wh_GetStringSetting(L"BgColor");
    if (bgColorStr) {
        int r = 0, g = 0, b = 0, a = 0;
        int count = swscanf_s(bgColorStr, L"%d,%d,%d,%d", &r, &g, &b, &a);
        
        if(r>255) r=255; if(g>255) g=255; if(b>255) b=255;
        if(r<0) r=0; if(g<0) g=0; if(b<0) b=0;

        if (count >= 3 && !(r==0 && g==0 && b==0)) {
            // FIX: SWAP RED AND BLUE for DWM API
            // BGR Format: 0x00BBGGRR
            g_Settings.manualBgColorRGB = ((DWORD)b << 16) | ((DWORD)g << 8) | (DWORD)r;
        } else {
            g_Settings.manualBgColorRGB = 0; 
        }
        Wh_FreeStringSetting(bgColorStr);
    } else {
        g_Settings.manualBgColorRGB = 0;
    }
    
    g_Settings.fsInterval = Wh_GetIntSetting(L"FullscreenCheckInterval");
    if (g_Settings.fsInterval < 1) g_Settings.fsInterval = 1;

    g_Settings.enableSlide = Wh_GetIntSetting(L"EnableSlide") != 0;
    g_Settings.enableGameDetect = Wh_GetIntSetting(L"EnableGameDetection") != 0;

    PCWSTR apps = Wh_GetStringSetting(L"IgnoredApps");
    if (apps) {
        g_Settings.ignoredApps = apps;
        Wh_FreeStringSetting(apps);
    } else {
        g_Settings.ignoredApps = L"firefox.exe;chrome.exe;msedge.exe";
    }

    if (g_Settings.bgOpacity < 0) g_Settings.bgOpacity = 0;
    if (g_Settings.bgOpacity > 255) g_Settings.bgOpacity = 255;
    if (g_Settings.width < 100) g_Settings.width = 300;
    if (g_Settings.height < 24) g_Settings.height = 48;
}

// --- WinRT / GSMTC ---
GlobalSystemMediaTransportControlsSessionManager g_SessionManager = nullptr;

Bitmap* StreamToBitmap(IRandomAccessStreamWithContentType const& stream) {
    if (!stream) return nullptr;
    IStream* nativeStream = nullptr;
    if (SUCCEEDED(CreateStreamOverRandomAccessStream(reinterpret_cast<IUnknown*>(winrt::get_abi(stream)), IID_PPV_ARGS(&nativeStream)))) {
        Bitmap* bmp = Bitmap::FromStream(nativeStream);
        nativeStream->Release();
        if (bmp && bmp->GetLastStatus() == Ok) return bmp;
        delete bmp;
    }
    return nullptr;
}

void UpdateMediaInfo() {
    try {
        if (!g_SessionManager) {
            g_SessionManager = GlobalSystemMediaTransportControlsSessionManager::RequestAsync().get();
        }
        if (!g_SessionManager) return;

        auto session = g_SessionManager.GetCurrentSession();
        if (session) {
            auto props = session.TryGetMediaPropertiesAsync().get();
            auto info = session.GetPlaybackInfo();

            lock_guard<mutex> guard(g_MediaState.lock);
            wstring newTitle = props.Title().c_str();
            if (newTitle != g_MediaState.title || g_MediaState.albumArt == nullptr) {
                if (g_MediaState.albumArt) { delete g_MediaState.albumArt; g_MediaState.albumArt = nullptr; }
                auto thumbRef = props.Thumbnail();
                if (thumbRef) {
                    auto stream = thumbRef.OpenReadAsync().get();
                    g_MediaState.albumArt = StreamToBitmap(stream);
                }
            }
            g_MediaState.title = newTitle;
            g_MediaState.artist = props.Artist().c_str();
            g_MediaState.isPlaying = (info.PlaybackStatus() == GlobalSystemMediaTransportControlsSessionPlaybackStatus::Playing);
            g_MediaState.hasMedia = true;
        } else {
            lock_guard<mutex> guard(g_MediaState.lock);
            g_MediaState.hasMedia = false;
            g_MediaState.title = L"No Media";
            g_MediaState.artist = L"";
            if (g_MediaState.albumArt) { delete g_MediaState.albumArt; g_MediaState.albumArt = nullptr; }
        }
    } catch (...) {
        lock_guard<mutex> guard(g_MediaState.lock);
        g_MediaState.hasMedia = false;
    }
}

void SendMediaCommand(int cmd) {
    try {
        if (!g_SessionManager) return;
        auto session = g_SessionManager.GetCurrentSession();
        if (session) {
            if (cmd == 1) session.TrySkipPreviousAsync();
            else if (cmd == 2) session.TryTogglePlayPauseAsync();
            else if (cmd == 3) session.TrySkipNextAsync();
        }
    } catch (...) {}
}

// --- Visuals ---
bool IsSystemLightMode() {
    DWORD value = 0; DWORD size = sizeof(value);
    if (RegGetValueW(HKEY_CURRENT_USER, L"Software\\Microsoft\\Windows\\CurrentVersion\\Themes\\Personalize", L"SystemUsesLightTheme", RRF_RT_DWORD, nullptr, &value, &size) == ERROR_SUCCESS) {
        return value != 0;
    }
    return false;
}

DWORD GetCurrentTextColor() {
    if (g_Settings.autoTheme) return IsSystemLightMode() ? 0xFF000000 : 0xFFFFFFFF;
    return g_Settings.manualTextColor;
}

void UpdateAppearance(HWND hwnd) {
    DWM_WINDOW_CORNER_PREFERENCE preference = DWMWCP_ROUND;
    DwmSetWindowAttribute(hwnd, DWMWA_WINDOW_CORNER_PREFERENCE, &preference, sizeof(preference));

    HMODULE hUser = GetModuleHandle(L"user32.dll");
    if (hUser) {
        auto SetComp = (pSetWindowCompositionAttribute)GetProcAddress(hUser, "SetWindowCompositionAttribute");
        if (SetComp) {
            DWORD tint = 0; 

            // LOGIC:
            if (g_Settings.manualBgColorRGB != 0) {
                // Manual Background Color is Active: Use its RGB + BgOpacity for Alpha
                tint = ((DWORD)g_Settings.bgOpacity << 24) | g_Settings.manualBgColorRGB;
            } else if (g_Settings.autoTheme) {
                // Auto Theme is Active: Use system light/dark
                tint = IsSystemLightMode() ? 0x40FFFFFF : 0x40000000; 
            } else {
                // Auto Theme is OFF, Manual BgColor is OFF: Use InvertTheme + BgOpacity
                DWORD baseColor = g_Settings.invertTheme ? 0x000000 : 0xFFFFFF; 
                tint = ((DWORD)g_Settings.bgOpacity << 24) | baseColor;
            }
            
            ACCENT_POLICY policy = { ACCENT_ENABLE_ACRYLICBLURBEHIND, 0, tint, 0 };
            WINDOWCOMPOSITIONATTRIBDATA data = { WCA_ACCENT_POLICY, &policy, sizeof(ACCENT_POLICY) };
            SetComp(hwnd, &data);
        }
    }
}

void DrawMediaPanel(HDC hdc, int width, int height) {
    Graphics graphics(hdc);
    graphics.SetSmoothingMode(SmoothingModeAntiAlias);
    graphics.SetTextRenderingHint(TextRenderingHintAntiAlias);
    graphics.Clear(Color(0, 0, 0, 0)); 

    // APPLY DPI SCALING
    graphics.ScaleTransform(g_ScaleFactor, g_ScaleFactor);

    Color mainColor{GetCurrentTextColor()};
    
    MediaState state;
    {
        lock_guard<mutex> guard(g_MediaState.lock);
        state.title = g_MediaState.title;
        state.artist = g_MediaState.artist;
        state.albumArt = g_MediaState.albumArt ? g_MediaState.albumArt->Clone() : nullptr;
        state.hasMedia = g_MediaState.hasMedia;
        state.isPlaying = g_MediaState.isPlaying;
    }

    // USE LOGICAL DIMENSIONS
    int logicalH = g_Settings.height;
    int logicalW = g_Settings.width;

    int artSize = logicalH - 12;
    int artX = 6, artY = 6;
    
    if (state.albumArt) {
        graphics.DrawImage(state.albumArt, artX, artY, artSize, artSize);
        delete state.albumArt;
    } else {
        SolidBrush placeBrush{Color(40, 128, 128, 128)};
        graphics.FillRectangle(&placeBrush, artX, artY, artSize, artSize);
    }

    int startControlX = artX + artSize + 12;
    int controlY = logicalH / 2;
    SolidBrush iconBrush{mainColor};
    SolidBrush hoverBrush{Color(255, mainColor.GetRed(), mainColor.GetGreen(), mainColor.GetBlue())};
    SolidBrush activeBg{Color(40, mainColor.GetRed(), mainColor.GetGreen(), mainColor.GetBlue())};

    int pX = startControlX;
    if (g_HoverState == 1) graphics.FillEllipse(&activeBg, pX - 8, controlY - 12, 24, 24);
    Point prevPts[3] = { Point(pX + 8, controlY - 6), Point(pX + 8, controlY + 6), Point(pX, controlY) };
    graphics.FillPolygon(g_HoverState == 1 ? &hoverBrush : &iconBrush, prevPts, 3);
    graphics.FillRectangle(g_HoverState == 1 ? &hoverBrush : &iconBrush, pX, controlY - 6, 2, 12);

    int plX = startControlX + 28;
    if (g_HoverState == 2) graphics.FillEllipse(&activeBg, plX - 8, controlY - 12, 24, 24);
    if (state.isPlaying) {
        graphics.FillRectangle(g_HoverState == 2 ? &hoverBrush : &iconBrush, plX, controlY - 7, 3, 14);
        graphics.FillRectangle(g_HoverState == 2 ? &hoverBrush : &iconBrush, plX + 6, controlY - 7, 3, 14);
    } else {
        Point playPts[3] = { Point(plX, controlY - 8), Point(plX, controlY + 8), Point(plX + 10, controlY) };
        graphics.FillPolygon(g_HoverState == 2 ? &hoverBrush : &iconBrush, playPts, 3);
    }

    int nX = startControlX + 56;
    if (g_HoverState == 3) graphics.FillEllipse(&activeBg, nX - 8, controlY - 12, 24, 24);
    Point nextPts[3] = { Point(nX, controlY - 6), Point(nX, controlY + 6), Point(nX + 8, controlY) };
    graphics.FillPolygon(g_HoverState == 3 ? &hoverBrush : &iconBrush, nextPts, 3);
    graphics.FillRectangle(g_HoverState == 3 ? &hoverBrush : &iconBrush, nX + 8, controlY - 6, 2, 12);

    int textX = nX + 20;
    int textMaxW = logicalW - textX - 10;
    wstring fullText = state.title;
    if (!state.artist.empty()) fullText += L" • " + state.artist;

    FontFamily fontFamily(FONT_NAME, nullptr);
    Font font(&fontFamily, (REAL)g_Settings.fontSize, FontStyleBold, UnitPixel);
    SolidBrush textBrush{mainColor};
    
    RectF layoutRect(0, 0, 2000, 100), boundRect;
    graphics.MeasureString(fullText.c_str(), -1, &font, layoutRect, &boundRect);
    g_TextWidth = (int)boundRect.Width;

    Region textClip(Rect(textX, 0, textMaxW, logicalH));
    graphics.SetClip(&textClip);
    float textY = (logicalH - boundRect.Height) / 2.0f;

    if (g_TextWidth > textMaxW) {
        g_IsScrolling = true;
        float drawX = (float)(textX - g_ScrollOffset);
        graphics.DrawString(fullText.c_str(), -1, &font, PointF(drawX, textY), &textBrush);
        if (drawX + g_TextWidth < logicalW) {
             graphics.DrawString(fullText.c_str(), -1, &font, PointF(drawX + g_TextWidth + 40, textY), &textBrush);
        }
    } else {
        g_IsScrolling = false;
        g_ScrollOffset = 0;
        graphics.DrawString(fullText.c_str(), -1, &font, PointF((float)textX, textY), &textBrush);
    }
}

// --- Window Procedure ---
#define IDT_POLL_MEDIA 1001
#define IDT_TEXT_ANIM  1002
#define APP_WM_CLOSE   WM_APP

LRESULT CALLBACK MediaWndProc(HWND hwnd, UINT msg, WPARAM wParam, LPARAM lParam) {
    switch (msg) {
        case WM_CREATE: 
            UpdateAppearance(hwnd);
            SetTimer(hwnd, IDT_POLL_MEDIA, 1000, NULL); 
            return 0;
        case WM_ERASEBKGND: return 1;
        case APP_WM_CLOSE: DestroyWindow(hwnd); return 0;
        case WM_DESTROY: g_SessionManager = nullptr; PostQuitMessage(0); return 0;
        case WM_SETTINGCHANGE: UpdateAppearance(hwnd); InvalidateRect(hwnd, NULL, TRUE); return 0;
        case WM_QUERYENDSESSION:
            g_ShutdownMode = true;
            ForceParkedState();
            return TRUE;
        case WM_TIMER:
            if (wParam == IDT_POLL_MEDIA) {
                SyncPositionWithTaskbar(); 
                UpdateMediaInfo();
                InvalidateRect(hwnd, NULL, FALSE);
            }
            else if (wParam == IDT_TEXT_ANIM) {
                if (g_IsScrolling) {
                    if (g_ScrollWait > 0) g_ScrollWait--;
                    else {
                        g_ScrollOffset++;
                        if (g_ScrollOffset > g_TextWidth + 40) { g_ScrollOffset = 0; g_ScrollWait = 60; }
                        InvalidateRect(hwnd, NULL, FALSE);
                    }
                } else KillTimer(hwnd, IDT_TEXT_ANIM);
            }
            else if (wParam == IDT_VIS_ANIM) {
                int screenH = GetSystemMetrics(SM_CYSCREEN);
                RECT rcTb; GetWindowRect(g_hTaskbar, &rcTb);
                int scaledH = (int)(g_Settings.height * g_ScaleFactor);
                int scaledOffY = (int)(g_Settings.offsetY * g_ScaleFactor);
                int targetY = rcTb.top + ((rcTb.bottom - rcTb.top) / 2) - (scaledH / 2) + scaledOffY;
                
                if (g_AnimState == 1) { // Hide
                    if (!g_IsGameDetected) { g_AnimState = 2; return 0; }
                    g_CurrentAnimY += 8;
                    if (g_CurrentAnimY > screenH) {
                        ShowWindow(hwnd, SW_HIDE);
                        KillTimer(hwnd, IDT_VIS_ANIM);
                        g_AnimState = 0;
                    } else {
                        RECT rc; GetWindowRect(hwnd, &rc);
                        SetWindowPos(hwnd, HWND_TOPMOST, rc.left, g_CurrentAnimY, 0, 0, SWP_NOSIZE | SWP_NOACTIVATE);
                    }
                }
                else if (g_AnimState == 2) { // Show
                    if (g_IsGameDetected) { g_AnimState = 1; return 0; }
                    g_CurrentAnimY -= 8;
                    if (g_CurrentAnimY <= targetY) {
                        g_CurrentAnimY = targetY;
                        RECT rc; GetWindowRect(hwnd, &rc);
                        SetWindowPos(hwnd, HWND_TOPMOST, rc.left, g_CurrentAnimY, 0, 0, SWP_NOSIZE | SWP_NOACTIVATE);
                        KillTimer(hwnd, IDT_VIS_ANIM);
                        g_AnimState = 0;
                    } else {
                        RECT rc; GetWindowRect(hwnd, &rc);
                        SetWindowPos(hwnd, HWND_TOPMOST, rc.left, g_CurrentAnimY, 0, 0, SWP_NOSIZE | SWP_NOACTIVATE);
                    }
                }
            }
            return 0;
        case WM_MOUSEMOVE: {
            // UNSCALE INPUT COORDINATES
            int x = (int)(LOWORD(lParam) / g_ScaleFactor);
            int y = (int)(HIWORD(lParam) / g_ScaleFactor);
            
            // USE LOGICAL HEIGHT
            int logicalH = g_Settings.height;
            int artSize = logicalH - 12;
            int startControlX = 6 + artSize + 12;
            int newState = 0;
            if (y > 10 && y < logicalH - 10) {
                if (x >= startControlX - 10 && x < startControlX + 14) newState = 1;
                else if (x >= startControlX + 14 && x < startControlX + 42) newState = 2;
                else if (x >= startControlX + 42 && x < startControlX + 66) newState = 3;
            }
            if (newState != g_HoverState) { g_HoverState = newState; InvalidateRect(hwnd, NULL, FALSE); }
            TRACKMOUSEEVENT tme = { sizeof(TRACKMOUSEEVENT), TME_LEAVE, hwnd, 0 };
            TrackMouseEvent(&tme);
            return 0;
        }
        case WM_MOUSELEAVE: g_HoverState = 0; InvalidateRect(hwnd, NULL, FALSE); break;
        case WM_LBUTTONUP: if (g_HoverState > 0) SendMediaCommand(g_HoverState); return 0;
        case WM_MOUSEWHEEL: {
            short zDelta = GET_WHEEL_DELTA_WPARAM(wParam);
            keybd_event(zDelta > 0 ? VK_VOLUME_UP : VK_VOLUME_DOWN, 0, 0, 0);
            keybd_event(zDelta > 0 ? VK_VOLUME_UP : VK_VOLUME_DOWN, 0, KEYEVENTF_KEYUP, 0);
            return 0;
        }
        case WM_PAINT: {
            PAINTSTRUCT ps; HDC hdc = BeginPaint(hwnd, &ps);
            RECT rc; GetClientRect(hwnd, &rc);
            HDC memDC = CreateCompatibleDC(hdc);
            HBITMAP memBitmap = CreateCompatibleBitmap(hdc, rc.right, rc.bottom);
            HBITMAP oldBitmap = (HBITMAP)SelectObject(memDC, memBitmap);
            DrawMediaPanel(memDC, rc.right, rc.bottom);
            if (g_IsScrolling) SetTimer(hwnd, IDT_TEXT_ANIM, 16, NULL);
            BitBlt(hdc, 0, 0, rc.right, rc.bottom, memDC, 0, 0, SRCCOPY);
            SelectObject(memDC, oldBitmap); DeleteObject(memBitmap); DeleteDC(memDC);
            EndPaint(hwnd, &ps);
            return 0;
        }
    }
    return DefWindowProc(hwnd, msg, wParam, lParam);
}

void MediaThread() {
    SetProcessDpiAwarenessContext(DPI_AWARENESS_CONTEXT_PER_MONITOR_AWARE_V2);

    winrt::init_apartment();
    GdiplusStartupInput gdiplusStartupInput;
    ULONG_PTR gdiplusToken;
    GdiplusStartup(&gdiplusToken, &gdiplusStartupInput, NULL);

    WNDCLASS wc = {0};
    wc.lpfnWndProc = MediaWndProc;
    wc.hInstance = GetModuleHandle(NULL);
    wc.lpszClassName = TEXT("WindhawkMusicLounge_GSMTC");
    wc.hCursor = LoadCursor(NULL, IDC_HAND);
    RegisterClass(&wc);

    HMODULE hUser32 = GetModuleHandle(L"user32.dll");
    pCreateWindowInBand CreateWindowInBand = (pCreateWindowInBand)GetProcAddress(hUser32, "CreateWindowInBand");

    if (CreateWindowInBand) {
        g_hMediaWindow = CreateWindowInBand(WS_EX_LAYERED | WS_EX_TOOLWINDOW | WS_EX_TOPMOST, wc.lpszClassName, TEXT("MusicLounge"), WS_POPUP | WS_VISIBLE, 0, 0, g_Settings.width, g_Settings.height, NULL, NULL, wc.hInstance, NULL, ZBID_IMMERSIVE_NOTIFICATION);
    } else {
        g_hMediaWindow = CreateWindowEx(WS_EX_LAYERED | WS_EX_TOOLWINDOW | WS_EX_TOPMOST, wc.lpszClassName, TEXT("MusicLounge"), WS_POPUP | WS_VISIBLE, 0, 0, g_Settings.width, g_Settings.height, NULL, NULL, wc.hInstance, NULL);
    }

    SetLayeredWindowAttributes(g_hMediaWindow, 0, 255, LWA_ALPHA);

    // Initial State: PARKED (2px visible at bottom)
    UpdateScaleFactor();
    int screenH = GetSystemMetrics(SM_CYSCREEN);
    int scaledW = (int)(g_Settings.width * g_ScaleFactor);
    int scaledH = (int)(g_Settings.height * g_ScaleFactor);
    SetWindowPos(g_hMediaWindow, HWND_TOPMOST, 0, screenH - 2, scaledW, scaledH, SWP_NOACTIVATE | SWP_SHOWWINDOW);
    g_AnimState = 3; // Parked

    // Setup Visibility Hook
    g_hVisibilityHook = SetWinEventHook(EVENT_OBJECT_LOCATIONCHANGE, EVENT_OBJECT_LOCATIONCHANGE, NULL, WinEventProc, 0, 0, WINEVENT_OUTOFCONTEXT);

    MSG msg;
    while (GetMessage(&msg, NULL, 0, 0)) { TranslateMessage(&msg); DispatchMessage(&msg); }

    if (g_hVisibilityHook) UnhookWinEvent(g_hVisibilityHook);
    UnregisterClass(wc.lpszClassName, wc.hInstance);
    GdiplusShutdown(gdiplusToken);
    winrt::uninit_apartment();
}

std::thread* g_pMediaThread = nullptr;

BOOL WhTool_ModInit() {
    SetCurrentProcessExplicitAppUserModelID(L"taskbar-music-lounge");
    LoadSettings(); 
    g_Running = true;
    g_pMediaThread = new std::thread(MediaThread);
    return TRUE;
}

void WhTool_ModUninit() {
    g_Running = false;
    if (g_hMediaWindow) SendMessage(g_hMediaWindow, APP_WM_CLOSE, 0, 0);
    if (g_pMediaThread) {
        if (g_pMediaThread->joinable()) g_pMediaThread->join();
        delete g_pMediaThread;
        g_pMediaThread = nullptr;
    }
}

void WhTool_ModSettingsChanged() {
    LoadSettings();
    if (g_hMediaWindow) {
         SyncPositionWithTaskbar();
         SendMessage(g_hMediaWindow, WM_SETTINGCHANGE, 0, 0); 
    }
}

// --- Launcher Boilerplate ---
bool g_isToolModProcessLauncher;
HANDLE g_toolModProcessMutex;
void WINAPI EntryPoint_Hook() { ExitThread(0); }

BOOL Wh_ModInit() {
    bool isService = false, isCurrentToolModProcess = false;
    int argc; LPWSTR* argv = CommandLineToArgvW(GetCommandLine(), &argc);
    if (!argv) return FALSE;
    for (int i = 1; i < argc; i++) { if (wcscmp(argv[i], L"-service") == 0) isService = true; }
    for (int i = 1; i < argc - 1; i++) { if (wcscmp(argv[i], L"-tool-mod") == 0 && wcscmp(argv[i + 1], WH_MOD_ID) == 0) isCurrentToolModProcess = true; }
    LocalFree(argv);
    if (isService) return FALSE;

    if (isCurrentToolModProcess) {
        g_toolModProcessMutex = CreateMutex(nullptr, TRUE, L"windhawk-tool-mod_" WH_MOD_ID);
        if (!g_toolModProcessMutex || GetLastError() == ERROR_ALREADY_EXISTS) ExitProcess(1);
        if (!WhTool_ModInit()) ExitProcess(1);
        IMAGE_DOS_HEADER* dosHeader = (IMAGE_DOS_HEADER*)GetModuleHandle(nullptr);
        IMAGE_NT_HEADERS* ntHeaders = (IMAGE_NT_HEADERS*)((BYTE*)dosHeader + dosHeader->e_lfanew);
        Wh_SetFunctionHook((BYTE*)dosHeader + ntHeaders->OptionalHeader.AddressOfEntryPoint, (void*)EntryPoint_Hook, nullptr);
        return TRUE;
    }
    g_isToolModProcessLauncher = true; return TRUE;
}

void Wh_ModAfterInit() {
    if (!g_isToolModProcessLauncher) return;
    WCHAR path[MAX_PATH], cmd[MAX_PATH + 100];
    GetModuleFileName(nullptr, path, MAX_PATH);
    swprintf_s(cmd, L"\"%s\" -tool-mod \"%s\"", path, WH_MOD_ID);
    STARTUPINFO si = { sizeof(si) }; PROCESS_INFORMATION pi;
    if (CreateProcess(nullptr, cmd, nullptr, nullptr, FALSE, NORMAL_PRIORITY_CLASS, nullptr, nullptr, &si, &pi)) {
        CloseHandle(pi.hProcess); CloseHandle(pi.hThread);
    }
}

void Wh_ModSettingsChanged() { if (!g_isToolModProcessLauncher) WhTool_ModSettingsChanged(); }
void Wh_ModUninit() { if (!g_isToolModProcessLauncher) { WhTool_ModUninit(); ExitProcess(0); } }
```

</details>

#### Default Taskbar

* Disable Widgets in your system Taskbar settings and set your Taskbar alignment to `Center`.
* Open the `Taskbar Music Lounge` mod in Windhawk.
* Go to the `Advanced` tab and copy the code below into the `Mod settings` box and click `save`.

<details>
<summary>Content to import (click to expand)</summary>

```json
{
  "PanelWidth": 300,
  "PanelHeight": 38,
  "FontSize": 14,
  "OffsetX": 302,
  "OffsetY": 0,
  "AutoTheme": 1,
  "InvertTheme": 1,
  "BgColor": "0, 0, 0",
  "BgOpacity": 0,
  "TextColor": "255, 255, 255",
  "EnableSlide": 0,
  "EnableGameDetection": 1,
  "FullscreenCheckInterval": 2,
  "IgnoredApps": ""
}
```

</details>

#### High DPI Taskbar

* Disable Widgets in your system Taskbar settings and set your Taskbar alignment to `Center`.
* Open the `Taskbar Music Lounge` mod in Windhawk.
* Go to the `Advanced` tab and copy the code below into the `Mod settings` box and click `save`.

<details>
<summary>Content to import (click to expand)</summary>

```json
{
  "PanelWidth": 300,
  "PanelHeight": 38,
  "FontSize": 14,
  "OffsetX": 110,
  "OffsetY": 0,
  "AutoTheme": 1,
  "InvertTheme": 1,
  "BgColor": "0, 0, 0",
  "BgOpacity": 0,
  "TextColor": "255, 255, 255",
  "EnableSlide": 0,
  "EnableGameDetection": 1,
  "FullscreenCheckInterval": 2,
  "IgnoredApps": ""
}
```

</details>


#### Full Width Taskbar

* Disable Widgets in your system Taskbar settings and set your Taskbar alignment to `Center`.
* Open the `Taskbar Music Lounge` mod in Windhawk.
* Go to the `Advanced` tab and copy the code below into the `Mod settings` box and click `save`.

<details>
<summary>Content to import (click to expand)</summary>

```json
{
  "PanelWidth": 300,
  "PanelHeight": 38,
  "FontSize": 14,
  "OffsetX": 5,
  "OffsetY": 0,
  "AutoTheme": 1,
  "InvertTheme": 1,
  "BgColor": "0, 0, 0",
  "BgOpacity": 0,
  "TextColor": "255, 255, 255",
  "EnableSlide": 0,
  "EnableGameDetection": 1,
  "FullscreenCheckInterval": 2,
  "IgnoredApps": ""
}
```

</details>


