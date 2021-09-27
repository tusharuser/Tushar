[![Deploy to Heroku]](https://github.com/Hertzian1/Hertzian")


# Hertzian
> A proactive judgement system for group chats.

## A Telethon UserBot to make gbanning easy 
> (asyncio)

## Config
Here stuff you need to put in config.py or Environment variables:
- ` API_ID_KEY`
- ` API_HASH_KEY`
You can get both of these from my.telegram.org
- `STRING_SESSION`:  You can get this by doing `python3 generatestringsession.py` on Linux and Mac, If on windows just python will work
- ` SIBYL `: Users who approve gbans, manage blacklist etc.
- ` ENFORCERS `: Users who send gban request
- ` Sibyl_logs `: In this group all scan request come
- ` Sibyl_approved_logs `: When approved it sends a message there
- ` GBAN_MSG_LOGS `:Where to gban user, Set to None and it will send /gban in Sibyl_logs
------------

## Purpose and schematics

Based on the popular anime series "Psycho Pass", Sibyl is designed to work in a judgement and scan system where groups can request Cymatic scans for spammers, this then connects to the Sibyl network and sends the data to Sibyl for judgement, upon the approval of which the user is judged by the dominator. [Base idea of Sibyl](https://psychopass.fandom.com/wiki/Sibyl_System "Base idea of Sibyl")

> To create and manage all Dominators and scanner systems in-country and to monitor the behavior of MWPSB personnel

------------


------------

### Commands list
Users can access the following commands, usage is limited based on enforcer privileges.

    *scan *- Reply to a message with reason to send a request for gbans
    *approve* - Approve a scan request
    *proof* - Get message from proof id which is at the end of gban msg

------------
---

# *Credit - DragSama*
