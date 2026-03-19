# LCE Server + Java Crossplay Support

This seems like the best way to do it that ive seen, and it should work in general for joining servers, if it doesnt? Whoops! This allows Java support but it should also work for just LCE servers, but who am I to know!

https://github.com/DeveloperExotic/LegacyCrossPlay Download the Client AND the Source Code. You need both, .zip for windows, .tar.gz for linux. 

The repo above gives you an instructions for what to do to get yourself set up, DO THOSE FIRST. 

<img width="1250" height="590" alt="image" src="https://github.com/user-attachments/assets/16b27a63-e2bf-46f3-9419-f663efdcba4a" />

You should already have the LegacyCrossPlay folder extracted, if you dont, go back to the repo and follow its instructions. Then, go into the "constants.js" file in the folder and edit one of the IP's in the const SERVERS = {} area (it should look like the image below) to your custom IP. And you can also set your username above to whatever you feel like in the custom_username area. <img width="577" height="244" alt="image" src="https://github.com/user-attachments/assets/e82d5445-89a6-42c2-8aa9-20a722afa301" />

# FOR HOSTERS ONLY (FOLLOW THIS SECTION IF YOU WANT A SERVER BASED ON 1.8)
Then on a server host of your choice, be it Aternos, your own hardware or a server hosting service like Apex or Shockbyte, set the server version to release 1.8. Also make sure your server is set to offline authentication mode in the server properties file or else it will throw an error.

# 1.8-1.21.11+ Setup
I recommend changing the server to Paper, Fabric is untested by me but Paper works.

You need ViaVersion, ViaBackwards, and ViaRewind to set this up. 
https://viaversion.com/

Put those in your piugins folder, then restart the server.
