# Multi App Configuration

Demonstrates how to provide multiple `App.configs`
for different project configurations.

## Useful tools

* [Markdown Editor v2](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.MarkdownEditor2)
* [SlowCheetah](https://github.com/microsoft/slow-cheetah)
* [Install app for all users](https://www.advancedinstaller.com/per-machine-msix.html)
* [orca.exe](https://learn.microsoft.com/en-us/windows/win32/msi/orca-exe)

## Hints

If you want to install the app, you have to install the certificate at first.
You can provide a shortcut for all users by copying the shortcut to `C:\Users\Public\Desktop`.

See more on: https://superuser.com/questions/984866/how-to-make-a-desktop-shortcut-available-for-all-users-in-windows-10.

Command for instaling the package for all users:

``` powershell
Add-AppProvisionedPackage -online -packagepath "YOUR_BUNDLE.appxbundle" -skiplicense
```

## Useful links

* https://www.c-sharpcorner.com/article/customize-user-interfaces-and-pass-user-input-to-installer-c/
* https://learn.microsoft.com/en-us/previous-versions/visualstudio/visual-studio-2010/2w2fhwzz(v=vs.100)?redirectedfrom=MSDN
* https://www.codeproject.com/Articles/1028052/Create-custom-dialogs-for-an-Setup-project-in-Visu
* "C:\Program Files (x86)\Windows Kits\10\bin\10.0.22000.0\x86\Orca-x86_en-us.msi"
