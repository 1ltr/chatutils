# Chatutils
Alternative embeddable front-end for your Discord server

A continuation of TN's chatutils, it is such a great project

## Setup:

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

**Discord Invite:**

14. Now go to `/public/index.html` and go to line 26 and put a permanent discord invite there

**Application ID:**

15. Save and go back to the (Discord Developer Portal)[https://discord.com/developers/applications] page and go to your bots `General Information` tab and and under the `APPLICATION ID` text it will show a series of numbers (eg. 923819283912931299)

16. Once you have located this, press the blue `Copy` button below it

17. Visit the [invite URL generator](https://pers0n-dev.github.io/Chatutils-invite-generator) for chatutils then paste from your clipboard your APPLICATION ID that you had just now copied into the input box that says `BOT client ID` then press `OK`

18. A new link should have appeared on your screen if all was done correctly, click on this link and choose a server to invite your bot to

**Deploy to heroku:**

19. Now go to https://heroku.com/deploy?template=your-github-url-here/tree/main and deploy to heroku

Congrats, you successfully setup Chatutils.

## Discord ID:

**Developer Mode:**

You need developer mode on to get the id

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


## Old Setup:


## Advanced Setup:

1. Download the (Github repo)[https://github.com/Monsters-dev/Chatutils/archive/master.zip]

2. Create a **private** github repository and manually add the files you downloaded

3. Visit the (Discord Developer Portal)[https://discord.com/developers/applications], signin, and `press New Application`

4. Set your application name to whatever you desire, this will not matter later

5. Once you are at the bot page, to the left you will see a button labelled `Bot`, click this and press `Add Bot` to the right then press `Yes, do it!` to confirm. Name it what you want your bot to be called

6. Scroll down to the area where it says `Token Click to reveal token` and press the blue `Copy` button below it

7. In your piviate github open up the config.json

8. Inside config.json, remove the text that says `token-here` and in its place, paste from your clipboard as the copy button on the earlier page should have copied your token DO NOT SHARE THIS TOKEN 

9. In the config, replace `insertContact@domain.tld` with a contact email

10. Copy the the ID of a role that can setup the bot and put it in `admin-role-id-here`

11. Now open dynamicData.json and replace `channel-id-here` with the channel id that you want to use for chatutils

12. Go to the channel your going to use and click settings

13. Go to integrations, webhooks and create 3 webhooks. Copy the webhook urls and paste them into the 3 places for webhooks

14. Now go to `/public/index.html` and go to line 26 and put a permanent discord invite there

15. Save and go back to the (Discord Developer Portal)[https://discord.com/developers/applications] page and go to your bots `General Information` tab and and under the `APPLICATION ID` text it will show a series of numbers (eg. 923819283912931299)

16. Once you have located this, press the blue `Copy` button below it

17. Visit the [invite URL generator](https://pers0n-dev.github.io/Chatutils-invite-generator) for chatutils then paste from your clipboard your APPLICATION ID that you had just now copied into the input box that says `BOT client ID` then press `OK`

18. A new link should have appeared on your screen if all was done correctly, click on this link and choose a server to invite your bot to

//19. Now open dynamicData.json and replace `channel-id-here` with the channel id that you want to use for chatutils

//20. Go to the channel your going to use and click settings

//21. Go to integrations, webhooks and create 3 webhooks. Copy the webhook urls and paste them into the 3 places for webhooks

//22. Now go to `/public/index.html` and go to line 26 and put a permanent discord invite there

23. Now go to https://heroku.com/deploy?template=your-github-url-here/tree/main and deploy to heroku

Congrats, you successfully setup Chatutils.