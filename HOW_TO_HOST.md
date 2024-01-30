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
3. Press Open Folder and locate the folder you downloaded.
4. Double click the folder, and double click the folder inside that folder as well and then press 'Select folder'.
You might this warning:
![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/40caee06-8348-47f4-8485-e2b9e6bffd0c)
Just press Yes, I trust the authors
5. Right click this panel on the top left and click 'New file'
![image](https://github.com/GroenKonijn/jumperbot/assets/94995135/15596f4f-e71f-4fde-a113-d0dc1c8d946e)
6. Give it the name 'params.json' without the quotation marks.
{
    "token" : "",
    "prefix" : ";",
    "is_dev" : [424616077805223956, 298835729901944834],
    "admins" : [424616077805223956, 298835729901944834],
    "banned" : [],
    "trusted" : [],
    "sim_timeout" : 100
}

   
