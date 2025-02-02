# [OFFICIAL SHOWCASE](github.com/juywvm/batus-valorant-instalocker)

# FAQ - BATUS VALORANT INSTALOCKER
## Language
This instalocker was made with python 3.12 idk if its works with older or new versions of python lol.



## How to use/run it?

* First of all, you need python installed.
* open the `install all modules on time.bat` file just once
* START AND ENTER THE LOBBY BEFORE RUNNING INSTALOCKER
* After that, just run instalocker.py everything should be fine. (when you in lobby)



## How to use it / I dont understand anything?

* When you start instalocker, it will ask you for REGION.
You need to enter CORRECT REGION or it will crash/not work.

If you don't know what region is, its means which server do you play on like na,eu,br etc.
Like if you play on Istanbul server, you need to type eu (WITHOUT CAPSLOCK)

If you dont know where the f*ck do you live, visit: https://support-valorant.riotgames.com/hc/en-us/articles/360055678634-Server-Select

* After entering region, it will ask you to confirm it. You can type no to change it.

* After region screen, it will show you current supported agents and ask you to type an agent name you see on the terminal.

* After typing an agent name, it will ask you for loop or not.

What is loop?

Its automaticly detects whenever you join a new match, and auto-instalock agent that you typed in everytime. So you dont need to run it every match, it will just run on background and you will be fine.

What if i set loop to NO?

It will instalock only one time, after instalocking agent it return you to Agent Names Screen again after 10 seconds

* After setting loop to true or false, start queue and have fun with instalocking!



## How backend works?
* Well, its using `valclient` python library to instalock. So you will safely use it without entering passwords,usernames,emails etc.
* Everytime u start instalocker.py , its sends request to `https://valorant-api.com/v1/agents/` so if riot adds an new agent, it will be automaticly updated and ready to go. Also new agent name will pop up on terminal too! If valorant api changes that agent api, we are f*cked up lol. So if valorant does not changes their agent api, you will be always using UPDATED and WORKING instalocker.
* After sending request to valorant api, its getting agent uuid's and overwrites to `baturwashere.json` . Then instalocker getting uuid from json file. not directly from api. thats means you are safe.



## Why its obfuscated?
* Uh, im actually so sorry about that. Because i spent over hours to make this project, and i dont want people to skid that nasty code.
* But, you can absolutely control anything with wireshark like if its rat, if its sending diffrent requests to diffrent sites or not. You can believe me its safe!
* And actually, if you know how to reverse engineering, you can deobfuscate it and inspect the source code. But please dont share with anyone, just be sure if you are safe or not. Thanks
* And! i can share source code with you! For educational purposes only, like if you are new at python, valorant api, trying to learn something new, etc. contact me at discord and i will give you full source. No problem! :) batus always with you!
