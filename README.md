# [Miss Rose Bot](https://t.me/MissRose_bot)

### Deploy on Heroku

Press the below button to Fast deploy on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Doctorstra/Miss-india)

## Credits 
* [![Doctorstra-Devs](https://img.shields.io/static/v1?label=Doctorstra&message=devs&color=critical)](https://telegram.dog/DoctorstraDevs)


## Profile

![Rose Profile](https://telegra.ph/file/718d48493d1fb11197d8b.jpg)


{
  "name": "Miss Rose",
  "logo": "https://telegra.ph/file/48522f7be29b993a19e60.jpg",
  "description": "Telegram's sassiest group manager. Modular Telegram group management bot!",
  "keywords": [
    "telegram",
    "best",
    "group",
    "manager",
    "3"
  ],
  "repository": "hhttps://github.com/FayasKKD/Miss-Rose-Bot",
  "env": {
    "ENV": {
      "description": "Setting this to ANYTHING will enable env variables",
      "value": "ANYTHING"
    },
    "TOKEN": {
      "description": "Your bot token, as a string.",
      "value": ""
    },
    "OWNER_ID": {
      "description": "An integer of consisting of your owner ID",
      "value": ""
    },
    "OWNER_USERNAME": {
      "description": "Your username",
      "value": ""
    },
    "WEBHOOK": {
      "description": "Setting this to ANYTHING will enable webhooks when in env mode messages",
      "value": "ANYTHING"
    },
    "URL": {
      "description": "The Heroku App URL similar to https://<appname>.herokuapp.com/",
      "value": ""
    },
    "MESSAGE_DUMP": {
      "description": "optional: a chat where your replied saved messages are stored, to stop people deleting their old",
      "value": "-1007777777777"
    },
    "SUDO_USERS": {
      "description": "A space separated list of user_ids which should be considered sudo users",
      "value": ""
    },
    "SUPPORT_USERS": {
      "description": "A space separated list of user_ids which should be considered support users (can gban/ungban, nothing else)",
      "value": ""
    },
    "WHITELIST_USERS": {
      "description": "A space separated list of user_ids which should be considered whitelisted - they can't be banned.",
      "value": ""
    },
    "DONATION_LINK": {
      "description": "Optional: link where you would like to receive donations.",
      "value": ""
    },
    "PORT": {
      "description": "Port to use for your webhooks",
      "value": "8443"
    },
    "DEL_CMDS": {
      "description": "Whether to delete commands from users which don't have rights to use that command",
      "value": "True"
    },
    "STRICT_GBAN": {
      "description": "Enforce gbans across new groups as well as old groups. When a gbanned user talks, he will be banned.",
      "value": "True"
    },
    "ALLOW_EXCL": {
      "description": "Whether to allow using exclamation marks ! for commands as well as /.",
      "value": "True"
    },
    "BAN_STICKER": {
      "description": "Which sticker to use when banning people. Use https://telegram.dog/ShowJsonBot to get the file_id",
      "value": "CAACAgQAAxkBAAEHAedfwdK1GHtSZe1Q0F0q6vWRsxL91gAC-QgAAoThEVJCGmPkkeA1_R4E"
    }
  },
  "addons": [
    {
      "plan": "heroku-postgresql",
      "options": {
        "version": "10"
      }
    }
  ]
}
