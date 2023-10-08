
[❗・Important](#important)<br>
[👑・Features](#features)<br>
[⚙・Config.json example](#configjson-example)<br>
[💎・Get Token](#get-token)<br>
[📍・OwO DM channel id](#owo-dm-channel-id)<br>
[⚠️・Captcha Alert](#captcha-alert)<br>
[📡・Socket Client](#socket-client)<br>
[🎈・Usage](#usage)<br>

## ❗・Important

-   It can detect virus due to captcha(ban) bypasser please turn off your antivirus.

## 👑・Features

-   Auto Hunt
-   Auto Battle
-   Inventory Check
    -   Auto Gem Use (beta)
    -   Auto Lootbox Use
    -   Auto Fabled Lootbox Use
    -   Auto Crate Use
    -   Auto Eventbox Use (like anniversary present or valentine's day)
-   Auto Gamble
    -   Auto Coinflip
    -   Auto Slots
-   Auto Animals Sell OR Sacrifice,
-   Auto Upgrade Autohunt
-   Auto Pray
-   Auto CheckList (beta)
    -   Auto Quest
    -   Auto Daily
    -   Auto Cookie
-   Captcha(Ban) Protection v0.1.8 (beta)
-   Discord-RPC
-   **Extra Token**
    -   All Main Token Features
    -   Auto Pray for Main Token

## ⚙・config.json example

```
{
    "settings": {
        "huntandbattle": "", true or false
        "banbypass": "", true or false
        "discordrpc": "", true or false
        "pray": "", true or false
        "extratoken": "", true or false
        "autoquest": "", true or false
        "inventory": {
            "inventorycheck": "", true or false
            "gemcheck": "", true or false
            "lootboxcheck": "", true or false
            "fabledlootboxcheck": "", true or false
            "cratecheck": "", true or false
            "eventcheck": "" true or false
        },
        "animals": {
            "enable": "", true or false
            "type": "" sell or sacrifice
            "ifsacrifice": {
                "common": "", true or false
                "uncommon": "", true or false
                "rare": "", true or false
                "epic": "", true or false
                "mythical": "", true or false
                "patreon": "", true or false
                "cpatreon": "", true or false
                "legendary": "", true or false
                "gem": "", true or false
                "bot": "", true or false
                "distorted": "", true or false
                "fabled": "", true or false
                "special": "", true or false
                "hidden": "" true or false
            }
        },
        "upgradeautohunt": {
            "enable": "", true or false
            "type": "" efficiency, duration, cost, gain, exp or radar
        },
        "gamble": {
            "coinflip": {
                "enable": "", true or false
                "amount": "1"
            },
            "slots": {
                "enable": "", true or false
                "amount": "1"
            }
        }
    },
    "main":{
        "token":"", main token
        "userid":"", token user id
        "channelid":"", channel id for main token
        "owodmchannelid":"" owo bot dm channel id
        "autoquestchannelid":"" auto quest channel id
    },
    "extra":{
        "token":"", extra token
        "userid":"", extra token user id
        "channelid":"", channel id for extra token
        "owodmchannelid":"" extra token owo bot dm channel id
    }
}


```

## 💎・Get Token

```js
(webpackChunkdiscord_app.push([
    [""],
    {},
    (e) => {
        m = [];
        for (let c in e.c) m.push(e.c[c]);
    },
]),
m)
    .find((m) => m?.exports?.default?.getToken !== void 0)
    .exports.default.getToken();
```

## 📍・OwO DM channel id

![](https://raw.githubusercontent.com/Mid0aria/owofarmbot/main/images/owochannelid.jpg)

## ⚠️・Captcha Alert
!!! If you want the captcha alert to work properly, turn off do not disturb

![](https://raw.githubusercontent.com/Mid0aria/owofarmbot/main/images/captchaalert.png)



## 📡・Socket Client

![](https://raw.githubusercontent.com/Mid0aria/owofarmbot/main/images/socketclient.png)

## 🎈・Usage
```
> edit config.json
```

```bash
> type npm install
```

```bash
> type node bot.js
``
