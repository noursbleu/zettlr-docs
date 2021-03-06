# Installation

The installation of Zettlr is very easy and takes only a step on every operating system. Zettlr is cross-platform, so it will run on most computers. Zettlr comes pre-built for macOS, Windows and many Linux systems.

## Windows (7 or newer)

To install Zettlr on Windows, just download the app from the [download page](https://www.zettlr.com/download) and double click to open the installer. If you wish to install Zettlr for all users, it is installed to the main `Program Files` directory and in this case you'd have to give it elevated rights during setup (it will automatically ask for your permission). You don't need any rights if you install it for the logged in user.

To uninstall Zettlr, simply run the Uninstall.exe either from the directory itself or use the appropriate add/remove program interface in your system's settings. If you want to completely remove all data associated with the app, also remove the directory `C:\Users\<your-user-name>\AppData\Roaming\Zettlr`.

> The Windows installer contains both a 32-bit version and a 64-bit version of the program, and will install whichever fits your operating system.

## macOS (10.10 or newer)

To install Zettlr on macOS, simply download the dmg-file from the latest release and mount it. Then drag the Zettlr icon into your Applications directory and you're done!

To uninstall Zettlr, simply remove the Zettlr.app from your Applications directory. If you want to completely remove all data associated with the app, also remove the directory `/Users/<your-user-name>/Library/Application Support/Zettlr`.

> You can also install Zettlr using [Homebrew](https://formulae.brew.sh/cask/zettlr): `$ brew cask install zettlr`

## Linux (Debian 8/Ubuntu 12.04/Fedora 21 or newer)

There are prebuilt `deb` and `rpm` packages for linux systems. Simply install the package on your system.

To uninstall, follow the usual steps it takes to remove a package (usually through the graphical installer application or via `dpkg`). If you also want to remove all data associated with the app, also delete the `/home/<your-user-name>/.config/Zettlr` directory.

> There is a community-maintained package for Arch Linux available. [You can find it on the official AUR repositories](https://aur.archlinux.org/packages/zettlr-bin/). Please note that this package is community-maintained and we do not take any responsibility in its stability, safety or offered version.

## AppImages

In case you use neither a Debian nor Fedora based Linux distribution, you can always install AppImage files. Please [refer to their guide on how to install them](https://appimage.org/). AppImages are provided for both 32-bit and 64-bit systems.

## Updating the app

The application checks for new updates each time you start the app. You can also manually trigger the search for updates by using the respective menu item from the Help menu. If a new version is available, Zettlr will show you a dialog that contains the new version's number, your current version and a changelog with all features and bug fixes the new version contains. You can then open the download page to download the new package. Simply install it over your current installation, it will take care of removing the old version first. All data will be retained and migrated to the new version.

> If you are interested in cutting-edge releases, make sure to tick the checkbox "Notify me about beta releases" in the Advanced tab of the preferences dialog!
