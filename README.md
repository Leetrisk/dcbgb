# dcbgb

this is **c#** btw and not **c++**

![alt text](https://github.com/Leetrisk/dcbgb/blob/main/dcbgb.png?raw=true)

dcbgb or 'discord background bot' lets you run .bat in system tray 

(orginally intended for running discord bot's 'start.bat' in background if you cant afford / get a VPS to host on)

i have put the source there, it is the file named dcbgb_src.rar

**LATEST RELEASE**
https://github.com/Leetrisk/dcbgb/releases/download/1.0/dcbgb.1.0.rar

**HOW TO USE**
1. put the .exe and the .txt file inside your bots base folder (works only for discord.js/node.js)
2. press **select** and use choose your start.bat, whichever one launches your bot.js file
3. press **start** and it will go to system tray 

**KNOWN ISSUES**
1. if you run it, then re-open from system tray it will add another dcbgb.exe in task manager/background, this will also be added to the check which shows number of node/dcbgb processes that are running (closing the program from the x/close button should usually fix this)
2. may read more than 1 process on start for each thing, as it grabs all current node/dcbgb processes
3. for the above reason, this program may conflict with other node processes on your computer, such as closing dcbgb closes other node procceses, please be aware of that

