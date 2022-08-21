# instagram-follow-bot
A simple lines of Python code that will follow people on Instagram automatically using a bot.

#### Requirements:
1. Python (+ selenium package)
2. Instagram accounts - bots that will follow a targered instagram profile.

#### Installing:
1. Install Python - https://www.python.org/
2. Install Selenium: open the console (PowerShell or CMD for windows), type: ```pip install selenium```
3. Download this repo. Click ```Code``` -> ```Download Zip```. Unpack this to any location.
4. Download the chromedriver from here - https://chromedriver.chromium.org/downloads. Choose your current chrome version. Put downloaded ```chromedriver.exe``` file to the script folder.
5. Put your bot instagram accounts to ```bots.txt```

#### Using:
1. Open ```follow.py``` using any text editor.
2. Set the ```targered profile``` in the target_profile parameter.
3. Open the console (powershell or cmd) in the folder with the ```follow.py``` file
4. Enter in the console: ```py follow.py``` and wait when all bots will follow the target.

#### Using this script you may get such message:
```[username] already follows "target"``` if this bot with ```username``` followed the ```target``` before.
```[username] successfully follow "target"``` if bot successfully followed ```target``` using this script.
```[username] didnt follow "target"``` if something went wrong. Inscrease delay time between all actions.
