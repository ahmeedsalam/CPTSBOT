# CPTSBOT

Telegram :- 
[Developem] (https://telegram.me/amody6)

Github | ahmeedsalam 👮
# 🔸commands🔹

 **sticker🏰 to photo🌄**

`just send a sticker`

 **photo🌄 to sticker🏰**

`just send a photo`

  **bold text** ✅

`/bold text`

 **italic text** ✅

`/italic text`

 **markdown link** ✅

`/link url text`

**code text** ✅

`/code text`

# channel📣

 **send bold text to a channel**

`/boldch @channelusername text`

 **send italic text to a channel**

`/italicch @channelusername text`

 **send markdown link to a channel**

`/linkch @channelusername url text`

**send code text to a channel**

`/codech @channelusername text`

# Installation 🔌

1⃣-- Write>>

sudo apt-get update

2⃣-- Write>>

```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```
3⃣-- Write>>
`sudo apt-get install lua-socket` 
4⃣-- Write>>
`sudo apt-get install lua-sec`

5⃣-- Write>> Clone the bot Write ⏬
```
git clone https://github.com/ahmeedsalam/CPTSBOT.git
cd CPTSBOT

```

🚸Then install bot using✅
`lua bot.lua`
👮bot token in bot.lua (config part)✔️

```lua

local bot_api_key = "" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
local BASE_FOLDER = "" -- do not set this
```
🔰And enter your telegram-id in admins table in [bot.lua](https://github.com/Imandaneshi/file-manager-bot/blob/master/bot.lua#L19) 💠

```lua
local var = false
  local admins = {140629197,987654321}-- اضع ايديك هنا
  for k,v in pairs(admins) do

```
Save bot.lua Ⓜ️

Start the bot 👁

`lua bot.lua`

