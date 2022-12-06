# <p align="center">![pybcgh](https://user-images.githubusercontent.com/95466780/204153308-668e4bc7-6b95-450d-85fd-1fc860191589.png)CAR: IRC Python bot — wrapped up as an executable</p>
# <p align="center">— Cycle And Renew —</p>

<p align="left">◼️◼️◼️◼️</p><p align="center">◼️◼️◼️◼️</p> <p align="right">◼️◼️◼️◼️</p><p align="center"><img width="512" height="512" src="https://user-images.githubusercontent.com/95466780/204159427-8987297a-4389-406b-98d7-c78013f4ff3c.png"></p><p align="left">◼️◼️◼️◼️</p><p align="center">◼️◼️◼️◼️</p> <p align="right">◼️◼️◼️◼️</p>

PyBot Desc: IRC Python bot converted to .exe for use with Windows Task Scheduler -- to cycle and renew your nick and nicks in your nick group to prevent expiration / dropping.  

(gg if you use a BNC/ZNC, but they don't last forever though and have to be maintained just like a nick, many have to be logged into often to avoid them expiring as well - so unless you host your own, there's risk involved with that too.  Grats if you have noexpire set on your nick and group, lol-- I'm jealous ~ hook me up?) 

The bot is composed or comprised?... of three parts: 1) a [console] window version, which is for manual checking / cycle/renew use, 2) a [headless ¦ in-background] version for use with WTS and won't pop-up any cmd console window and can be run silently in the background w/o any user interaction, and finally 3) a ConfigParser configuration .py file.  

The bot works on multiple networks; just not at once from a single instance - so, just change the user settings in the CAR.py configuration file to the single server you want to use; you can also add aditional servers you want to connect on that aren't listed too; baring in mind you follow the same syntax already outlined for the current servers listed within - the servers listed are for networks I personally ran CAR on to check for compatibility - if you want multiple servers to cycle and renew your nicks on, then you can just duplicate the executables and CAR.py file, then edit the server and nick data in each CAR.py instance, and then if you like, put those constituent parts in individual folders and name those said folders whichever server name coresponds to 'em - duplicate those 3 as much as you like and have folders with the bot parts in each of 'em, rename the folders to each individual network you want to cycle and renew your nicks on- that's what I recommend and do myself as seen just below:  

![ss (2022-11-27 at 08 06 06)](https://user-images.githubusercontent.com/95466780/204157956-6a7fb18a-1902-455e-a867-ba0882122db1.png)
![aaaaass (2022-11-27 at 08 07 45)](https://user-images.githubusercontent.com/95466780/204158403-181d875f-67e2-4f65-aa77-fd535ec4f283.png)

In WTS, I recommed running [headless] .exe perpetually / indefinitely every X hours.

You can cycle and renew up to 5 nicks on a network from one instance of those 3 files, but you can get more by duplicating and running the clone on the same network with your extra nicks.  Duplicate for different scenarios like having different passwords etc...

You don't have to use all the nick slots either; you can leave what you're not using blank "" - but I recommend just using the same nick in the unused fields as the bot can't switch to a nick it's already using ;)

#### WTS
- * ##### Have the following files in the same directory/folder/path of your choosing: CAR.py & Cycle And Renew (CAR) [headless ¦ in-background].exe & Cycle And Renew (CAR) [console].exe | NOTE: You can rename the executable files to whatever you like.exe; example: Rizon [console].exe, Freenode [headless].exe, but CAR.py must retain the same name or things will break.
* WTS: Actions, **<ins>Edit Action</ins>**, Action: Start a program ˇ
* WTS: Program/script ~path e.g.~: "C:\Users\YOU\Desktop\Cycle And Renew\Cycle And Renew (CAR) [headless ¦ in-background].exe"
* WTS: Add arguments (NOT optional): CAR.py
* WTS: Start in (NOT optional): C:\Users\YOU\Desktop\Cycle And Renew\
* - ##### General example: 

![WTS e.g.](https://user-images.githubusercontent.com/95466780/204062655-ad2b3123-bf5c-4ee1-820e-778a6b5ca4ef.png)


- * ### Script '.exe' [console] application in use: <video src="https://user-images.githubusercontent.com/95466780/201495586-c3272787-c481-4ee2-9f0f-eaa098b82696.mp4" controls="controls" style="max-width: 700px;">
</video> 


### <p align="right">Note: [headless] does the same thing but w/o a viewable window for scheduled background use w/ WTS.</p>


- * ### Script IRC output: <video src="https://user-images.githubusercontent.com/95466780/201495986-8d456f85-b1e0-4907-8a2b-130ca7d5daa7.mp4" controls="controls" style="max-width: 700px;">
</video>
