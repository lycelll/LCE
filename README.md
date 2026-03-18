# LCE Server + Java Crossplay Support

This seems like the best way to do it that ive seen.

https://github.com/DeveloperExotic/LegacyCrossPlay 

The repo above gives you an instructions for what to do to get yourself set up, DO THOSE FIRST. Then on a server host of your choice, be it Aternos, your own hardware or a server hosting service like Apex or Shockbyte, set the server version to release 1.8. Also make sure your server is set to offline authentication mode in the server properties file or else it will throw an error.

You should already have the LegacyCrossPlay folder extracted, if you dont, go back to the repo and follow its instructions. Then, go into the "constants.js" file in the folder and edit one of the IP's in the const SERVERS = {} area (it should look like the image below) to your custom IP. <img width="577" height="244" alt="image" src="https://github.com/user-attachments/assets/e82d5445-89a6-42c2-8aa9-20a722afa301" />

And you can also set your username above to whatever you feel like in the custom_username area.
