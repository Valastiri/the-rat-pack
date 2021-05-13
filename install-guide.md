## GD Launcher Config

To install The Rat Pack download the `gd-launcher.zip` below and save it. Follow these instructions:

1. Open GD Launcher
2. (First time?) Setup Java -*automatically*- through GD Launcher
3. Find the `+` sign in the bottom left and open it.
4. In the following window click on `Import Zip`
5. Click browse and find `gd-launcher.zip` you downloaded.
6. Select it and press open.

The pack will install and download all the mods from CurseForge for you. 

### Java Arguments

Once the pack is fully installed, please setup the following java arguments to have a smooth experience. Steps:

1. In GD Launcher find your installed instance and `right click`
2. Click on `Manage`
3. Scroll down in this window and click on the slider for `Override Java Arguments`
4. Copy past the arguments below into the new box that shows up. 

```
-Dfml.ignorePatchDiscrepancies=true -Dfml.ignoreInvalidMinecraftCertificates=true -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx6G -Xms6G -XX:-UseParallelGC -XX:-UseConcMarkSweepGC -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M -Dsun.rmi.dgc.server.gcInterval=2147483646
```

**NOTE:** `-Xmx6G -Xms6G` These two arguments define how much RAM Minecraft will use on your PC. Change the number value (6G in this case) to the amount of Gigabytes you want to use. If you want to have Minecraft use 4GB - `-Xmx4G -Xms4G` for example.

## Updating

To update your local config (if you already have the pack installed) download the `instance-update.zip`

1. Open GD launcher
2. Right Click on the instance
3. Click on `Open Folder`
4. Find the `config` folder and open it.
5. Drag and drop the contents of `instance-update.zip` into the `config` folder. 
6. Replace all files.

## Changelog

- All configs are release ready.