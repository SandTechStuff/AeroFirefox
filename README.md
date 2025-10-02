# Aero Firefox

![GitHub Release](https://img.shields.io/github/v/release/SandTechStuff/AeroFirefox)
![GitHub Release Date](https://img.shields.io/github/release-date/SandTechStuff/AeroFirefox)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/SandTechStuff/AeroFirefox/total)

> [!WARNING]
> The latest release no longer works on Firefox 141 and over.
> If you want to use the theme on newer versions, download it from the [3.0-test](https://github.com/SandTechStuff/AeroFirefox/tree/3.0-test) branch.

Brings the Aero titlebar buttons from Windows 7, transparency support, and more to the latest version of Firefox.

This theme uses images extracted from the official Windows 7 msstyles theme file, so the buttons are as accurate as possible (besides the hover glow).

|Operating System|Supported?  |
|:---------------|:----------:|
|Windows 11      |✅          |
|Windows 10      |✅          |
|MacOS           |❌          |
|Linux           |Maybe       |

## Installation

Install like any other Firefox CSS theme.
1. Check for compatibility issues in the chart below.
2. Open `about:config`
3. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to true.
4. Open `about:profiles`
5. Click `Open Folder` next to the root directory of your currently selected profile.
6. Copy the `chrome` folder from this repository into your Firefox profile folder.

## Preferences

* `AeroFirefox.disable-titlebar-buttons`: Disables all modifications of the titlebar buttons (close, maximize, restore, and minimize).

* `AeroFirefox.no-caption-padding`: Removes the 4 pixels for padding added to the close button, useful when you are using a theme with thick borders.

* `AeroFirefox.transparency`: Makes the tab bar transparent, which when paired with other tools allows you to restore Aero Glass.

    * `AeroFirefox.transparency.disable-when-maximized`: Makes the tab bar the standard theme color when the browser is maximized.

    * `AeroFirefox.transparency.transparent-toolbar`: Makes the entire toolbar (tabs, navigation, bookmarks) slightly transparent, allowing glass to show through but keeping your Firefox theme in place.

    * `AeroFirefox.transparency.fully-transparent-toolbar`: Makes the entire toolbar (tabs, navigation, bookmarks) transparent, allowing glass to show through when using other tools.

* `AeroFirefox.text-glow`: Enables a white shadow on text elements that are shown above transparency, mimicking Windows 7 and improving legibility.

* `AeroFirefox.remove-navbar-borders`: Removes the borders around the navigation bar set by some Firefox themes, which can improve the look of glass.

* `AeroFirefox.fix-borders`: When using a Windows 7 or other theme with thick borders, this option fixes those borders being too long and going behind the browser.

    * `AeroFirefox.fix-borders.no-padding`: Removes the left and right padding in the navigation bar and bookmarks bar.

## Screenshots

_Currently Outdated (Pre-2.0)_

> Dark Mode
![image](/screenshots/screen1.png)

>Light Mode
![image](/screenshots/screen2.png)

>Alphenglow
![image](/screenshots/screen3.png)
