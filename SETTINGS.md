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

!![Welcomemessage](http://i.imgur.com/o7bR4u1.png)
r
### Welcome channel

You can set a specific channel for the welcome announcement or you set it as private message.
If it's private, the bot sends the new member a private message with the welcome text.

Use `!welcomechannel #channel` to set it to a channel, or only `!welcomechannel` without any arguments to set it as private message

![Welcomechannel](http://i.imgur.com/sRNrjI0.png)


### Welcome message content

You can set your own welcome text for the message! But note: Emojis won't work!

Use `!welcomecontent` **without** any arguments to show the current welcome text.

To set it, just type `!welcomecontent Your welcome text here`

![Welcomecontent](http://i.imgur.com/sl2dQHt.png)


## Level and XP system

Improve you community spirit with the Level and XP system. For every message members earn xp and increase their level.

To enable this use `!xp on` or `!xp off` to disable it.

You can show your current rank with `!rank` or the top ranking of the server with `!ranking`

![XP](http://i.imgur.com/ohI1Gis.png)


## User role self management

This system gives members the possibility to add certain roles on their own.

The Moderators set up a list of roles which the members can add.
Some examples:
  * different game roles
  * Music genre
  * Teams
  
The Moderators use `!addrole @role` or `!deleterole @role` to add or delete roles from the list. (`!deleterole` without any argument will delete all roles from the list)  

With `!sub` everyone can show the current list of available roles.
Use `!sub @role` to add the certain role.

![Sub](http://i.imgur.com/SbExwwI.png)

## Swearword block

This feature blocks the most bad words. It's not perfect but it keeps the chat clean from too swearing

Enable it with `!wordblock on` or disable it with `!wordblock off`

