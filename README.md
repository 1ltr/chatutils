# Chatutils
Alternative embeddable front-end for your Discord server

This is a continuation of TN's chatutils, because it was such a great project

It was made private so I made this, a continuation that other people can use and contribute too!

![screenshot](https://github.com/Monstars-dev/Chatutils/blob/main/chatutilsscreenshot.png?raw=true)

## To Do:

**ENV:**
Use env in deploy for putting in values insted of making new gitub
Env format https://github.com/Pers0n-dev/Basic-Auth/blob/main/app.json

**Multiple Channels**

**UI:**
channel name, user ID

**Invite generator**

### Setup:

**Make private github:**

1. Download the (Github repo)[https://github.com/Monsters-dev/Chatutils/archive/master.zip]

2. Create a **private** github repository and manually add the files you downloaded

**Token:**

3. Visit the (Discord Developer Portal)[https://discord.com/developers/applications], signin, and `press New Application`

4. Set your application name to whatever you desire, this will not matter later

5. Once you are at the bot page, to the left you will see a button labelled `Bot`, click this and press `Add Bot` to the right then press `Yes, do it!` to confirm. Name it what you want your bot to be called

6. Scroll down to the area where it says `Token Click to reveal token` and press the blue `Copy` button below it

7. In your piviate github open up the config.json

8. Inside config.json, remove the text that says `token-here` and in its place, paste from your clipboard as the copy button on the earlier page should have copied your token DO NOT SHARE THIS TOKEN 

**Email:**

9. In the config, replace `insertContact@domain.tld` with a contact email

**Role ID:**

10. Copy the the ID of a role that can setup the bot and put it in `admin-role-id-here`

**Channel ID:**

11. Now open dynamicData.json and replace `channel-id-here` with the channel id that you want to use for chatutils

**Webhooks:**

12. Go to the channel your going to use and click settings

13. Go to integrations, webhooks and create 3 webhooks. Copy the webhook urls and paste them into the 3 places for webhooks

**Discord:**

14. Now go to `/public/index.html` and go to line 26 and put a permanent discord invite there

15. Now delete `/public/assets/logo.png` and upload your serer's logo

**Application ID:**

16. Save and go back to the (Discord Developer Portal)[https://discord.com/developers/applications] page and go to your bots `General Information` tab and and under the `APPLICATION ID` text it will show a series of numbers (eg. 923819283912931299)

17. Once you have located this, press the blue `Copy` button below it

18. Visit the [invite URL generator](https://pers0n-dev.github.io/Chatutils-invite-generator) for chatutils then paste from your clipboard your APPLICATION ID that you had just now copied into the input box that says `Application ID` then press `OK`

19. A new link should have appeared on your screen if all was done correctly, click on this link and choose a server to invite your bot to

**Deploy to heroku:**

20. Now go to https://heroku.com/deploy?template=your-github-url-here/tree/main

21. It will ask to connect to your github, follow the steps

22. Now deploy

Congrats, you successfully setup Chatutils!

**If it is not working try:**

1. In the chatutils channel say `_setchannel`

2. In the chatutils channel say `_setlogging`

3. Just wait a bit

## Discord ID:

**Developer Mode:**

You need developer mode on to get any id

1. User Settings

2. Advanced

3. Toggle developer mode on

**Channel ID:**

1. Right click on channel 

2. Press copy ID

**Role ID:**

1. Server Settings

2. Roles

3. Right click on role

4. Press Copy ID

### Commands:

_say message (ex: _say hello world!)

### Configuration:

**Bot Info:**

Name and picture:

1. Visit the (Discord Developer Portal)[https://discord.com/developers/applications]

2. Click the button labelled `Bot`

3. Change the bot name and picture to whatever you like

Playing Message:

1. Go to `server.js`

2. Click edit and go to line 432

3. Edit  name:'Alternative embeddable front-end...'} to something whatever you want, ex: name:'Chatutils!'}

**Custom Emojis:**

1. Go to `/public/assets/emojis.js` 

2. In the place you want your emoji put `['emoji_name','💻'],`

3. The bottom emoji does not have a `,`

### Credits:

**TN:** 

Everyone there

**Divide**

**Pers0n-dev**

**EnderKingJ**

**MegaPixel**
