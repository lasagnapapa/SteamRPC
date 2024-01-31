## SteamRPC - A universal Discord rich presence for all Steam games

This software uses data from your Steam profile to generate your game title and status, this can be useful as many games on Steam provide a detailed status of the game and it's current activities. The goal of this project is to create a universal RPC that will display on your Discord profile as "Playing **Steam Game**", followed by "Game Title", "Current Activity", as well as displaying the cover art for the game you're currently playing (Similar to how the Nintendo Switch RPC works). I feel this is a good way to display the game you're currently playing, and what you're doing (proven conversation starter).

## Notice: As of now this application is not working
- I am actively working on the code for this app, so please stay tuned

### Getting Started (When the project is fully functional)

To get started you're going to need the following information before running the setup (setup.exe/setup.py)
- Your own Steam API key from: https://steamcommunity.com/dev/apikey
- Your Steam ID (not your display name)
- Your Discord Application Client ID (see below)
 
### Discord Application

To make your Discord Application, follow these steps:
- Go to https://discord.com/developers/
- Click on "New Application"
- Name your new application "Steam Game", "Steam Software", or simply "Steam"
- After making your new application navigate to "General Information"
- Copy the "Application ID" (client ID) for future reference
- Add "steam_large.png" and "steam_small.png" to your assets underneath the "Rich Presence" tab
- You can find the ones I recommend here: https://github.com/lasagnapapa/SteamRPC/tree/main/Title%20Assets/Steam%20(Default)
- It should look like this:

![image](https://github.com/lasagnapapa/SteamRPC/assets/68775205/2096040e-ecbe-4be3-87bc-8875ca91c8fb)


### Customization

To add more cover images, and small images for the games you provide, you will need to upload them to the assets portion of your steam applet.
- Navigate to your Discord Application in https://discord.com/developers/applications/
- Click on the "Rich Presence" tab
- Upload your cover image with the title of the game, followed by "_large"
- It should look as follows:

![image](https://github.com/lasagnapapa/SteamRPC/assets/68775205/e72c130d-6335-4be9-af57-a1149958cf0e)

- Finally, add your game title in "SteamRPC" along with the corresponding asset name

### Please let me know if you have any issues, suggestions, or if you would like to contribute in to improving the software.
