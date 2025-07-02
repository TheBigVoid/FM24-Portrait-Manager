# FM24 Portrait Manager

A simple custom tool to quickly manage and replace player portraits in Football Manager 2024 facepacks.

## Features
- One-player-at-a-time portrait replacement
- Drag-and-drop portrait import
- Live image preview
- Reset and Apply buttons with FM-style UI

## Setup & Usage Guide

📂 Facepack Setup

If you don't have a facepack, follow these steps:

Go to:

Documents > Sports Interactive > Football Manager 2024 > graphics

If the graphics folder does not exist, create it.

Inside the graphics folder, create a new folder and name it whatever you like.Example: YourFacepack

Open your new folder and download the config file from this GitHub repository.Place the config file inside your facepack folder.

🖼️ Using Portrait Manager

Open Portrait Manager.

In FacePack Path, select the folder you created (e.g. YourFacepack).

Find the Player ID:

Open Football Manager 2024.

Go to Preferences > Interface and enable Show Screen IDs in Title Bar.

In-game, navigate to the player you want to edit. The player's ID will now appear in the top bar of their profile screen.

Note: Some FM skins have an "ID" button to display it directly.

Copy the player ID and paste it into the Player ID field in Portrait Manager.

Important: If your player is a newgen (a player created by the game as it progresses), the ID will start with r-. Make sure you copy the entire ID, including the r- prefix.

Select the new portrait:

You can either click Select Portrait to browse your files, or simply drag and drop the image into the application.

Recommended: Use portraits sized 180x180 pixels. Larger sizes (like 500x500) can still work, but smaller is safer. You can use images with backgrounds, but a clean background or a transparent one is usually better. The "Remove BG (Free Preview)" option can help.

Once you’ve selected the new portrait, click Apply Change.

💡 In-Game Refresh

Go back to your save file. You can update player portraits without restarting the game.

Go to Preferences > Skin and:

Disable: Use caching to decrease page loading times.

Enable: Reload skin when confirming changes in Preferences.

Click Reload Skin at the bottom of the Preferences window.

Done! Your player should now have the updated portrait.

📢 Version Info

This is currently version 0.0.1.

Future versions will add the ability to save players and change their portraits whenever you want.


