# DiSky
Welcome to the unofficial DiSky Documentation!

# Getting Started.
The first thing we have to do is make a new discord bot for our project.

We are going to open the [Discord Developer Portal](https://discord.com/developers)

Next we are going to create a new application

![image](https://user-images.githubusercontent.com/72381315/171682350-311863aa-65d8-4fb6-a9bc-243c6075a8a4.png)

When clicking on the new application button, You should see a menu like this popup.

![image](https://user-images.githubusercontent.com/72381315/171682595-4c20b3e8-0b35-43f6-877a-6dfef3d26c50.png)

Give it a name then click "Create"

![image](https://user-images.githubusercontent.com/72381315/171682763-9429b8da-c650-4f8d-bfa8-aae055b667f5.png)

After you should have a page like this,

![image](https://user-images.githubusercontent.com/72381315/171682962-8cd40a00-f08d-4a61-abc2-c5ceddae905f.png)

Click on the bot tab in the sidebar

![image](https://user-images.githubusercontent.com/72381315/171683053-f664a4b6-0366-4eae-af28-afe96bc08ace.png)

Then click on "Add Bot"

![image](https://user-images.githubusercontent.com/72381315/171683122-b9ab8f2e-4c9f-4937-92ba-b04da620ea6a.png)

Then click on "Yes, do it!"

![image](https://user-images.githubusercontent.com/72381315/171683275-2e5c7ef0-958b-4854-9104-3e67b214b38d.png)

Then click on "Reset Token"

![image](https://user-images.githubusercontent.com/72381315/171683407-fe480659-1de8-4acf-a0ff-113b8ecc00b3.png)

Then click on "Yes, do it!"

![image](https://user-images.githubusercontent.com/72381315/171683514-f52ff485-dfc2-42de-a4fe-9dd0e71ede56.png)

If you're a 2fa user, You might see this,

![image](https://user-images.githubusercontent.com/72381315/171683712-40b6a8d1-8e3f-4369-a631-1eb64606daf1.png)

Then click on "Copy"

![image](https://user-images.githubusercontent.com/72381315/171683844-337e03fc-d6d1-401e-a56a-f86e6f22c268.png)

**MAKE SURE TO KEEP YOUR BOT'S TOKEN PRIVATE IT IS A SECRET**, I'm only showing it to you as i will delete this application later!

Now lets link our discord bot to skript

```
define new bot named "My Cool Bot":
  token: "OTgxOTYzMjUzMzc2Nzc0MjI1.G4pS0n.XmBauXMkhnQ_2zqd9vOJiM-lyKq81QSWbk9Sv0"
  intents: default intents
  policy: all
  auto reconnect: true
  compression: none
```

Now lets reload our skript, Using the following command.

```
skript reload %your-skript-name%.sk
```

We are done, We've just made a discord bot with DiSky!

**Check out my other documentation tutorials!**
* None
