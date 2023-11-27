# Installation Instructions
Here's how to install the Fabric Mod Launcher and install all the required mods.

## 1. Install Fabric
Install Fabric Installer here:
 * [Fabric Installer](https://fabricmc.net/use/installer/)

![Alt Text](https://github.com/Aviator2276/Phasmo-Mod-Repository/blob/main/images/img1.png?raw=true)

Once downloaded, double click the Fabric Installer. Ensure you are on the client tab and select 1.20.1 for the Minecraft Version. Leave everything else default and click install. (Make sure the Minecraft Launcher is closed before doing this)

![Alt Text](https://github.com/Aviator2276/Phasmo-Mod-Repository/blob/main/images/img2.png?raw=true)

Now open up the Minecraft Launcher and you should see a new installation. Click the "Installations" tab right next to the Play tab at the top. You should see a list of Installations.

![Alt Text](https://github.com/Aviator2276/Phasmo-Mod-Repository/blob/main/images/img3.png?raw=true)

Click the three dots on the Installation we just installed (fabric-loader-1.20.1) and click "Edit." Here we're going to do 2 things.

1. In the GAME DIRECTORY, it may be empty as it's using the default minecraft folder. Although you may have other installations that use other mods. E.g. other Forge or Fabric installations. You can change this folder to another to create a new Minecraft Folder for this specific Installation. **This can be skipped if you don't have any other modded installation. (leave it to default setting)**

![Alt Text](https://github.com/Aviator2276/Phasmo-Mod-Repository/blob/main/images/img4.png?raw=true)

2. Click the "MORE OPTIONS" dropdown to reveal two textboxes. Within the "JVM ARGUMENTS" you should see the following"
```
-Xmx4G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
```
With some cutoff. We're focused on the ```-Xmx4G``` or whatever number it is set. Set it to ```-Xmx6G``` or ```-Xmx8G``` depending on how many GB of RAM you have. DON'T set it to the amount you have, always leave headroom. So now it should look like this.

![Alt Text](https://github.com/Aviator2276/Phasmo-Mod-Repository/blob/main/images/img5.png?raw=true)

Click "Save" to save the settings you set.

Now click "PLAY" on that installation. This is nececssary to generate the required files of Fabric. You can close it once it reaches the menu page of Minecraft.

## 2. Install Mods
Download the mods from this GitHub Repository:
 * [Download from GitHub](https://github.com/Aviator2276/Phasmo-Mod-Repository/archive/refs/heads/main.zip) - 305 MB

Then extract all the contents of the downloaded folder. After that, locate the "ClientMods" within the folders. Select all 53 mods (the files with .jar at the end) and CUT.

Locate the "GAME DIRECTORY" that you set or the default Minecraft location. It should have these files within.

![Alt Text](https://github.com/Aviator2276/Phasmo-Mod-Repository/blob/main/images/img6.png?raw=true)

Enter the "mods" folder where you can then PASTE all 53 mods into.

![Alt Text](https://github.com/Aviator2276/Phasmo-Mod-Repository/blob/main/images/img7.png?raw=true)

You're now done! Congrats!

## 3. Play the Game!
Now that you've installed Fabric & the Mods, you can play the Installation. Enter in the IP given to you to join the server.