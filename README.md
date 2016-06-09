# CPTSBOT

# الاوامر

 **تحويل ملصق الى*

`لتحويل الملصق الى صورة فقط ارسل الملصق`

 **صورة الى ملصق**

`لتحويل الصورة الى ملصق فقط ارسل الصورة`

  **خط عريض**

`/bold الكلمة`

 **خط مائل**

`/italic الكلمة`

 **لستة روابط**

`/link url الكلمة`

**خط ازرق**

`/code الكلمة`

# القنوات

 **ارسال كلمات بخط عريض للقناة**

`/boldch @cptsch الكلام`

 **ارسال كلام بخط مائل للقناة**

`/italicch @cptsch الكلام`

 **ارسال لستة روابط للقناة**

`/linkch @cptsch url الكلام`

**ارسال خط ازرق للقناة**

`/codech @cptsch الكلام`

# التنصيب

هذه الاكواد مبرمجة بواسطة [lua](http://www.lua.org/) للتنصيب
ادخل هذا الكود واضغط انتر

```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
بعدها هذن الكودين واضغط انتر
```
`sudo apt-get install lua-socket` & `sudo apt-get install lua-sec`

بعدها انسخ هذن والصقهن

```
git clone https://github.com/ahmeedsalam/CPTSBOT.git
cd CPTSBOT

```

بعد التنصيب استعمل هذا الملف⬇️ فقط

`lua bot.lua`
بعدها اذهب الى فاذر بوت
@botfahter
اعطيه
/newbot
وبعدين
newbottest
بعدين
معرف للبوت
مثلا
CPTSBOT
بعدين انسخ التوكن
بعدين lua bot.lua (config part)

```lua

local bot_api_key = "اضع هنا التوكن" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
local BASE_FOLDER = "" -- لاحاجة لهذا اتركه فارغا
```

بعدها اضع هنا ايدي حسابك وايدي حسابك صديقك حتى تصبحون ادمنية مثل هذا الشيء [bot.lua](https://github.com/Imandaneshi/file-manager-bot/blob/master/bot.lua#L19)
كما في النقش
```lua
local var = false
  local admins = {140629197,987654321}-- اضع ايديك هنا
  for k,v in pairs(admins) do

```
بعدها
احفظ التعديلات bot.lua

ابدا عمل البوت

`lua bot.lua`


# lua-api-bot

A simple telegram-bot wtitten in LUA based on [file manager bot](https://github.com/Imandaneshi/file-manager-bot)

# commands

 **sticker to photo**

`just send a sticker`

 **photo to sticker**

`just send a photo`

  **bold text**

`/bold text`

 **italic text**

`/italic text`

 **markdown link**

`/link url text`

**code text**

`/code text`

# channel

 **send bold text to a channel**

`/boldch @channelusername text`

 **send italic text to a channel**

`/italicch @channelusername text`

 **send markdown link to a channel**

`/linkch @channelusername url text`

**send code text to a channel**

`/codech @channelusername text`

# Installation

You should have [lua](http://www.lua.org/) installed

```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev

```
`sudo apt-get install lua-socket` & `sudo apt-get install lua-sec`

Clone the bot

```
git clone https://github.com/pAyDaAr/lua-api-bot.git
cd lua-api-bot

```

Then install bot using

`lua bot.lua`

bot token in bot.lua (config part)

```lua

local bot_api_key = "" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
local BASE_FOLDER = "" -- do not set this
```

And enter your telegram-id in admins table in [bot.lua](https://github.com/Imandaneshi/file-manager-bot/blob/master/bot.lua#L19)
```lua
local var = false
  local admins = {123456789,987654321}-- put your id here
  for k,v in pairs(admins) do

```

Save bot.lua

Start the bot

`lua bot.lua`
