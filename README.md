#Class Ps1
For installing default apps on Student Laptops with a fresh install
               

Because I'm Tired of bloatware on Dell laptops 
# Darc Debloater

winGet Darc Debloater using the [winget package manager](https://github.com/microsoft/winget-cli)

## Winget
Update or install winget [here](https://www.microsoft.com/p/app-installer/9nblggh4nns1)

Copy and paste this command into a command prompt with Administrator rights:

    powershell iwr https://raw.githubusercontent.com/DracV/drac/blob/main/DarcDebloater.bat -o DarcDebloater.bat && DarcDebloater.bat

### Remove:
If debloater is no longer needed remove it with:
    
    del DarcDebloater.bat
    
## What will it remove?

<details>
  <summary>Windows 10</summary>

```
Edge (Will ask first)
Camera App (Will ask first)
Snipping Tool (Will ask first)
Skype
Microsoft Teams
Xbox Applications
Groove-Music
Feedback-Hub
Microsoft Tips
3D-Viewer
Paint-3D
Weather
Mail and Calendar
Your Phone
Contacts App
Microsoft Pay
Microsoft Maps
Office
OneNote
Windows Sound Recorder
Movies & TV App
Mixed Reality-Portal
Sticky Notes
Get Help
OneDrive
Microsoft Solitaire Collection
Calculator
Microsoft Edge WebView2 Runtime
```

</details>

<details>
<summary>Windows 11+</summary>


All of the Windows 10 Applications and:

```
Microsoft To do
Power Automate
Microsoft News
Disney+
Microsoft Family 
Quick Assist
Clipchamp
...
```
</details>

## The script accidentally deleted an app that I wanted to keep.

You can get the app you want back by using `winget install <package name>`. If you wanted to keep the calculator app you can just do `winget install calculator`. 

Please don't use this. Experimenting for my own purposes.
