## Introduction
Vii Room is a replacement server for Wii Room, otherwise known as: Wiiの間.

Please note that this tool is still in development and will only work on
Japan only consoles.

## Important Info
To use this tool, you'll need node.js and OpenSSL installed on your computer.

## Setup Process
Open command prompt and type `npm install` to install all the required packages. Then, type `node first.js` and enter your IP address. This will create new files and folders inside the directory for the server to work. 

Once you've done that, go to the patcher folder and put in an official WAD of Wii Room, then type `node AutoPatcher.js` and choose the best settings. When the patcher is finished patching, you can close out of command prompt.

## Images and Videos
Go into the assets folder, and put in some images that you like, make sure its resolution is the same as the template ones.

Videos are different and can be a bit complex. You'll need to download Mobiclip Conversion Tool from RiiConnect24's github page, get a Mobiclip license for the program to work correctly, download the actual Mobiclip tools, and get a license for it.

When installing the actual Mobiclip tools, you'll get a message saying that the program was blocked by an admin. This is fixable, open command prompt again but as an admin, and paste in the programs path. It should open.

Once you've done that, open up the Mobiclip Conversion Tool and insert a video. But before you start the conversion, install the license first. There should what date and time to add on the license's name.

Once you've done everything correctly, it should open VirtualDub and convert the video to a .mo video format, this file name was used for the Nintendo Wii for videos.

## Adding Videos
To add a video, go into the assets folder, and then movies. Add the video file and make sure it matches the images file name.

## Testing
To test the server, go into the back folder, open command prompt and type `node server.js` This should run the server without any problems. You will also need Dolphin Emulator with Japan selected as the region. Unless if you have a Japan only Wii.

## Errors and Issues
If you experience any errors, or if I forgot something please let me know!
