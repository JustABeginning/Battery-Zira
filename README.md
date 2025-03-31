# Battery-Zira

<p align=left>
  <a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="https://img.shields.io/badge/platform-windows-blue" alt="Platform Support"></a>
  <a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="https://img.shields.io/badge/support-%3C%3D%20windows_10-darkgreen" alt="Platform Version"></a>
  <a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="https://img.shields.io/badge/device-laptop-orange" alt="Device Support"></a>
  <a href="https://dev.to/justabeginning/battery-zira-windows-8m0"><img src="https://img.shields.io/badge/article-dev.to-brightgreen" alt="Brief Article"></a>
</p>

<p align=left>
  <a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="https://img.shields.io/badge/language-Batch%20Script%2C%20VBScript-green" alt="Language Used"></a>
  <a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/JustABeginning/Battery-Zira"></a>
</p>

A Windows based program that gives voice reminder based on _low_, _critical_, _maximum_ and _fully charged_ battery levels in a laptop

<table align=center>
  <tr align=center valign=middle>
    <td><a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="Images/Battery_Low_Notify.jpg" alt="Battery Low Notification"></a></td>
    <td><a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="Images/Battery_Critical_Notify.jpg" alt="Battery Critical Notification"></a></td>
  <tr>
  <tr align=center valign=middle>
    <td><a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="Images/Battery_Max_Notify.jpg" alt="Battery Maximum Notification"></a></td>
    <td><a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="Images/Battery_Full_Notify.jpg" alt="Battery Full Notification"></td>
  <tr>
</table>

<p align=left>
  <a href="https://www.producthunt.com/posts/battery-zira-windows?utm_source=badge-review&utm_medium=badge&utm_souce=badge-battery-zira-windows#discussion-body" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/review.svg?post_id=309402&theme=light" alt="Battery Zira (Windows) - An incredible assistant for laptop battery | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
</p>

## Install

- [Download](https://github.com/JustABeginning/Battery-Zira/releases) the zip file and extract/save it in a folder (Give it any name) [All the extracted components must be in the same folder].

### Auto

1. Go to the extracted folder.
1. Click on `Install.bat` file.

### Manual

1. Go to the extracted folder.
1. Create a _shortcut_ of `Launch_BAT.bat` file.
1. Press `Win+R` from keyboard or, open windows run menu, then type `shell:startup` and press enter.
1. Save the shortcut created in **step-2** in the location which opens in **step-3**.
1. Return back to the folder of **step-1** and click on `Launch_BAT.bat` file.

## Note

- In order to set custom values, use `Custom_Battery_Level.bat` file.

<p align=center>
  <a href="https://github.com/JustABeginning/Battery-Zira#JAB"><img src="Images/Custom_Value.jpg" alt="Set Custom Values"></a>
</p>

- To skip the value of a parameter, press enter. This will accept the default/recently saved (if any) value for that parameter.
- For a parameter accepting numerical values, only _non-zero_ **positive** _integral_ values are allowed.
- The DEFAULT VALUES are:
  - Stop Battery-Zira - no
  - Low battery level - 40 %
  - Critical battery level - 20 %
  - Maximum battery level - 80 %
  - Snooze time - 1 minute
  - Enable voice - no
  - Voice assistant - Zira
  - Voice rate - 2
- If the program has been stopped, it can be re-triggered using `Install.bat` file.

## Uninstall

### Auto

1. Click on `Uninstall.bat` file.

### Manual

1. Delete the `Launch_BAT.bat` _shortcut_ from the location which opens in **step-3** of **_Install_**.
1. Restart the Computer.

## 🧋 Contribution

Pull requests, issue reports and suggestions are welcome 😊 !

## :clap: A Big Thanks To

### Stargazers

[![Stargazers repo roster for @JustABeginning/Battery-Zira](https://reporoster.com/stars/JustABeginning/Battery-Zira)](https://github.com/JustABeginning/Battery-Zira/stargazers)
