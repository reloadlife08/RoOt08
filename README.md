 # [RoOt08](https://telegram.me/root08)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/reloadlife08/RoOt08.git
cd RoOt08
chmod +x RoOt08.sh
./RoOt08.sh install
./RoO08.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/reloadlife08/RoOt08.git && cd RoOt08 && chmod +x RoOt08.sh && ./RoOt08.sh install && ./RoOt08.sh
```

* * *

### Sudo And Bot
After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    324656723,
    0,
    YourID
  }
```
add your bot ID at line 4 and add your ID at line 87 in bot.lua
add your ID at line 2 in Tools.lua
Then restart the bot.

# [RoOt08](https://telegram.me/root08)
