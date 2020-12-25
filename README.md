**FTB Installation Instructions** 
1) Download curse forge: https://curseforge.overwolf.com
2) Open curse forge, click Minecraft under the "choose a game" tab. 
3) Search "Enigmatica 2" in search bar. 
4) Click install for 3rd entry (Enigmatica 2 - E2, NOT Enigmatica 2: Expert - E2) 
5) Wait for install to finish and click the gear in the lower left. 
6) Click "Minecraft" under "Game Specific" on left. 
7) Scroll down to java settings and change allocated memory to ~6gb (~6000mb). You can use more if you have more memory (I use 10gb, but 6 should be fine.) 
8) Copy paste the following into "Additional Arguments": 
```-XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M ```
9) Close settings, click minecraft tab on left, and click "Play" under enigmatica 2. 
10) Make sure it says "Enigmatica 2 - E2" in bottom left of MC client and click "Play". Accept the disclaimer. 
11) It takes a long time to load from here, just wait even if it's taking a while or looks laggy. It can take as long as 20mins depending on your computer. If it crashes you probably need to allocate more memory or close some programs.
12) [Optional to reduce lag] Go into options: BetterFps Options: 
- Preallocate Memory = On (Have to restart after setting this, but I think it's worth it) 
- Fog = Fast Video Options
- Graphics = Fast 
- Smooth Lighting = Minimum
- Particles = Decreased 
- Entity Shadows = off
- Brightness = max (doesn't reduce lag, but is a good setting)
- If it's still laggy after this, first try turning down render distance. If that isn't good enough turn off the minimap (Press "J" -> options -> minimap preset 1 -> uncheck enable minimap.) I'd only do this if absolutely necessary; the minimap is pretty useful to have. 
- Also, chrome uses a lot of memory so if you just have 8gb I'd get and use opera while playing instead of chrome. Worth doing imo as there's a good chance you'll want to pull up the wiki at some point. This doesn't really matter if you have 16gb. 
13) Add server and connect! If you want to join my quest party (i.e. share quests as a group instead of individually) ask me to invite you.
