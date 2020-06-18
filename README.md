# DeadSpaceman Minecraft Modpack

This is the repository for the Dead Spaceman minecraft modpack.

## Installing

1. Download [MultiMC](https://multimc.org/#Download), a tool for managing multiple minecraft installations and modpacks. Extract the folder to a directory of your choosing, and run ``MultiMC.exe``
    * Select your preferred language
    * Select a Java 1.8 installation, and set the default RAM allocation. You will generally want to increase this. Depending on how much RAM you have, allocating 4-6 gigabytes is not a bad idea. Those with higher end machines can allocate higher amounts, but there are diminishing returns as Java garbage collection starts to cause performance issues at high RAM allocation.
2. Click 'Add Instance' in your MultiMC launcher, select 'Import from zip' on the left-hand side of the window, and enter ``https://github.com/bobbahbrown/deadspaceman-minecraft/releases/latest/download/deadspaceman-minecraft.zip``
3. Launch the installed instance

## Connecting

Bobbahbrown is hosting a server at ``mc.melonmesa.com``

## Problems

**My MC won't start when I set it to use more than 4GB of RAM!**
Check that you are using 64-bit Java. In MultiMC, go to ``Settings`` -> ``Java`` -> ``Auto-detect...``, if the version that is starred says ``32`` under architecture, this is 32-bit Java and you must install 64-bit Java. [A download can be found here. Make sure you download the 64-bit version!](https://www.java.com/en/download/manual.jsp)

## Contributing

Contributions can be made VIA PRs to this repository.