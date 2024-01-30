# How to host Mothball yourself

## Step 01:
### Create a new discord bot.
1. Go to https://discord.com/developers/docs/intro and click on 'applications' on the top left.
2. On the top right, click 'New Application'.
3. On the left panel, click on the OAuth2 dropdown menu and go to URL Generator.
4. Under scopes, check the box next to 'bot', scroll down a bit and check the box next to 'Administrator'.
5. Scroll down and copy paste the link. You can use this link to invite the bot to your Discord server.
6. In the developer portal, in the menu on the left, click 'Bot'. Turn on these 3 settings and save changes:

![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/96bc29be-5b2d-4318-af30-7ef4a192f0f2)

## Step 02:
### Install an IDE.
#### You can use any IDE but for this guide I will use VSC because that's what I'm using.
Install Visual Studio Code https://code.visualstudio.com/download1

## Step 03:
### Install Python.
Install the most recent stable version here: https://www.python.org/downloads/

## Step 04:
### Putting the code into VSC.
1. Go to bot's github page: https://github.com/GroenKonijn/jumperbot
2. Press the 'Code' button, then press download zip.

![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/471d2188-f585-458b-9ad4-f3b4865c8b55)

4. Press Open Folder and locate the folder you downloaded.
5. Double click the folder, and double click the folder inside that folder as well and then press 'Select folder'.
You might get this warning:

![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/40caee06-8348-47f4-8485-e2b9e6bffd0c)

   Just press Yes, I trust the authors

6. Right click this panel on the top left and click 'New file'

![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/15596f4f-e71f-4fde-a113-d0dc1c8d946e)

7. Give it the name 'params.json' without the quotation marks.
8. In the params.json file, write the following:

![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/ffa3a417-6f6b-4088-b5cd-9b649a159423)

   You can leave the is_dev and admins keys empty or replace them with your Discord ID.

### Getting your bot token for the json file.
1. Go back to the developer portal https://discord.com/developers/docs/intro
2. Press Applications, click on your bot, then click Bot on the left panel.
3. Click Get Token or Reset Token if you need to reset it.

![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/be27910e-39aa-425f-9c0d-5156290df74a)

4. Copy paste it into the params.json file between the quotation marks.

## Step 05.
### Running the bot.
1. Double click bot.py on the left panel.
2. Press F5 to run the code, you should see something like this pop up:

![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/8add04d4-227e-4035-82bc-9f675c9888d1)

   Press 'Python File' and you should be good to go!


### If you have any questions feel free to msg me on Discord or something: 1414_
   
