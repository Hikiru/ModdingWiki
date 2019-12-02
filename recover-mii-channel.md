# Recover your lost or corrupted Mii Channel

This page will guide you through the process of restoring your Mii Channel to a working state.

### What you need

> - A working [Homebrew installation](introduction) on Wii U side
> - This release of [FTPiiU Everywhere](http://wiiubru.com/appstore/#/app/fpiiu-cbhc)
> - The latest release of [Python](https://www.python.org/downloads/)
> - An FTP client such as [FileZilla](https://filezilla-project.org/download.php?type=client)
> - [This Python script](/file/overwrite-wiiu-titlehash.py)

### Instructions

> 1. Extract the `fpiiu-cbhc.zip` file to the root of your SD Card
> 2. Install FileZilla on your computer
> 3. Install Python on your computer

### Recovering the channel

!> If you are using a system update blocking method, please [remove it](unblock-updates).

> 1. Power on your Wii U and launch the CFW of your choice (Mocha, Haxchi or CBHC)
> 2. Launch the Homebrew Launcher and FTPiiU Everywhere
> 3. Launch FileZilla on your computer
> 4. In FileZilla, type in the IP address displayed by your Wii U in the `Host` field at the top of the window and click on `Quickconnect`
> 5. Navigate to `/slccmpt01/title/00010002`
> 6. Delete the `48414341` folder
> 7. On your computer, double click the previously downloaded `.py` file
> 8. Type in your Wii U's IP address and press Enter
> 9. Wait for it to finish what it's doing
>  - If an `err.log` file has been generated, please visit us in **#wiiu-assistance** on [Nintendo Homebrew Discord](https://discord.gg/C29hYvh)
> 10. Exit FTPiiU Everywhere and the Homebrew Launcher
> 11. Launch the System Settings
> 12. Perform a System Update

You should now have a working Mii Channel.

?> You can now re-enable your [system update blocking method](block-updates).