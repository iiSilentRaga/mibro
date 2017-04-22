# Settings
In the following is explained how you customzie the Bot for your server

Use `!settings` to show your current settings. At the same time, this shows the commands to change those settings.

![Settings](http://i.imgur.com/8iRxOd7.png)


## Set up Modrole / Channel
Use `!modrole @role` and `!modchannel #channel` to set your role and channel.
a
![Modrole](http://i.imgur.com/SMv4tU8.png) ![Modchannel](http://i.imgur.com/Uv0jHyI.png)



## Welcome message

First you have to enable the Welcome message 

![Welcomemessage](http://i.imgur.com/o7bR4u1.png)

#### Welcome channel

You can set a specific channel for the welcome announcement or you set it as private message.
If it's private, the bot sends the new member a private message with the welcome text.

Use `!welcomechannel #channel` to set it to a channel, or only `!welcomechannel` without any arguments to set it as private message

![Welcomechannel](http://i.imgur.com/sRNrjI0.png)


#### Welcome message content

You can set your own welcome text for the message! But note: Emojis won't work!

Use `!welcomecontent` **without** any arguments to show the current welcome text.

To set it, just type `!welcomecontent Your welcome text here`

![Welcomecontent](http://i.imgur.com/CfQRW6U.png)


## Auto role assignment

If you set this role (`!autorole @role`), new members will get this role automatically in the moment they join your server.

**Please Note:** Right now you can only set one autorole


## Level and XP system

Improve you community spirit with the Level and XP system. For every message members earn xp and increase their level.

To enable this use `!xp on` or `!xp off` to disable it.

You can show your current rank with `!rank` or the top ranking of the server with `!ranking`

![XP](http://i.imgur.com/ohI1Gis.png)


## User role self management

This system gives members the possibility to add certain roles on their own. No permission or admin needed!

The Moderators set up a list of roles which the members can add.
Some examples:
  * different game roles
  * Music genre
  * Teams
  
The Moderators use `!addrole` or `!deleterole` to add or delete roles from the list.

With `!sub` everyone can subscribe the roles from the above list.
Use `!unsub` to unsubscribe.

These two commands show the list of available roles, and you just have to type in the number. (Picutes following!)

**Please note:** MiBro needs a role with permission to assign roles. And this roles has to be higher than the roles you want to add. (Look at you Discord Serversettings)

## Swearword block

This feature blocks the most bad words. It's not perfect but it keeps the chat clean from too swearing

Enable it with `!wordblock on` or disable it with `!wordblock off`


## Global Prikbord

To connect to the gloabl prikbord: `!prikbord #channel`
To disconnect: `!prikbord` (without arguments)
