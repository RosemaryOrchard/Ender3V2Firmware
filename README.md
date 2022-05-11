This repo is intended to document how **I** update/configure my Creality Ender 3 V2. It is not intended to serve directly as a method to update it yourself, but you are welcome to use my configuration and extend it yourself.

## Required Tools
- [Visual Studio Code](https://marlinfw.org/docs/basics/install_platformio_vscode.html) with the PlatformIO plugin. (I prefer to [install VS Code with Homebrew](https://formulae.brew.sh/cask/visual-studio-code).)
- 8GB MicroSD card, and some way of connecting it to your machine. This should be formatted as FAT32 (Disk Utility: `MS-DOS (FAT)`). I personally recommend having a separate MicroSD card you use for firmware updates, and the one that you leave in your printer day to day. This way you know that the only one with firmware on (which is read automatically when the machine powers on) is the one _not_ in your printer unless you put it there.
- [Marlin Firmware](https://github.com/MarlinFirmware/Marlin).
- [Configuration Files](https://github.com/MarlinFirmware/Configurations) - You can either start with mine, documented below, or with the basic configuration for the printer. 

## Useful tools:
- [Wowstick](https://amzn.to/3vTLxMg) or other similar electric screwdriver for electronics (if you get the Wowstick keep an eye out for deals, and get the 1F which is rechargeable). You can mess with your 3D printer without this, but it's much less tiresome with an electric screwdriver.
- [Paint palettes](https://amzn.to/3sljeUS) or similar for putting screws in when you take them out. Label with dips with masking tape and a pen. Or get fancy and have one dedicated to your 3D Printer and use your label maker.
- A stretch of free time in which you are not likely to be interrupted. 
- Chocolate.
- A system for storing your firmware files. Feel free to fork this repo, and put your own firmware files in the fork, or make your own. You could store the files in Dropbox/iCloud or whatever cloud system you like, but do yourself a favour and store them!

## Customising the configuration.
- I started with the [Creality Ender 3 V2](https://github.com/MarlinFirmware/Configurations/tree/import-2.0.x/config/examples/Creality/Ender-3%20V2) config sample, specifically the `CrealityV422/CrealityUI` one. 
- I went through the recommendations on the [OctoPrint forums](https://community.octoprint.org/t/a-list-of-recommended-marlin-features/39048). 

I also updated the screen firmware separately. (Tip: To take the back of the screen of, just slide it up off the angled holder, undo the 4 bolts, and then use a very thin flat headed screwdriver or a spudger on the narrow sides to pop off the back casing.)
