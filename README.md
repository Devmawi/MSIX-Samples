# Multi App Configuration

Demonstrates how to provide multiple `App.configs`
for different project configurations.

## Useful tools

* [Markdown Editor v2](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.MarkdownEditor2)
* [SlowCheetah](https://github.com/microsoft/slow-cheetah)
* [Install app for all users](https://www.advancedinstaller.com/per-machine-msix.html)

## Hints

If you want to install the app, you have to install the certificate at first.
You can provide a shortcut for all users by copying the shortcut to `C:\Users\Public\Desktop`.

See more on: https://superuser.com/questions/984866/how-to-make-a-desktop-shortcut-available-for-all-users-in-windows-10.

Command for instaling the package for all users:

``` powershell
Add-AppProvisionedPackage -online -packagepath "YOUR_BUNDLE.appxbundle" -skiplicense
```
