---
description: >-
  This page will be periodically updated with details from the update log
  channel in the discord server. If you want the changelog as soon as it is
  released, join the discord server.
---

# 🔄 Change Log

## LockBot v3.4.0a

**Added**

* &#x20;`antiscam` has been added to make setting up easier - Documentation for `Anti Scam`: [https://docs.lockbot.dev/bot-info-commands/anti-scam](https://docs.lockbot.dev/bot-info-commands/anti-scam)

**Changes**

* Changed `antiscam` setup on the `setup` command, you will be prompted to use the new command - Slight grammar improvements

**Fixed**

* Fixed quite a huge memory leak and CPU overclocking constantly

## LockBot v3.4.0

**Added**

* &#x20;`Unknown Command` has been re-added and optimised. Shows your suggestions if you spelt a command wrong.&#x20;
* `Anti Scam` has been added, once enabled, it'll filter scam links (e.g steam/nitro). **\[BETA]** Please create a ticket or dm me if you are having any issues.
* You can choose which punishment to give to users if they send a scam link (kick/ban/none), all links detected will be deleted automatically.
* Ban & Kick Lock Reason is now on the `panel` command.
* Anti Scam & the punishment is on the `panel` command.

**Changes**

* Fixed internal errors spamming console
* Fixed a few bugs erroring out and crashing the server's shard
* You will now need the 'Manage Messages' permission in order to view `panel`

**Fixed**

* \[Hopefully] Fixed slow response times when you run a command

## LockBot v3.3.9

**Added**

* `invites` command `setup` command
* Server stats on web api
* You can set a reason why kick/ban lock is enabled for it to DM users when they join. Information what the `Kick & Ban Lock Reason` module does on our docs: [https://docs.lockbot.dev/bot-info-commands/kick-and-ban-lock-reason](https://docs.lockbot.dev/bot-info-commands/kick-and-ban-lock-reason)
* A quick but helpful troubleshooting guide on our docs: [https://docs.lockbot.dev/troubleshooting](https://docs.lockbot.dev/troubleshooting)

**Changes**

* You will now have to set up the Logging System in order to use Kick & Ban Lock You will now only be able to enable either Kick Lock or Ban Lock not both

**Fixes**

* Fixed ban lock dmming users but not banning the user Fixed an issue with the `prefix` command crashing the server shard

## LockBot v3.3.8

**Patches**

* Fixes on `suggest` command

**Changes**

* The Kick/Ban Lock alert embeds are even more detailed than ever with avatar hyperlinks, bot checker, flags (badges) and if they're a possible threat to your server

## LockBot v3.3.7

**Added**

* You will now be alerted after someone has been kicked/banned within your server when kick/ban lock is enabled, **if** the Logging System is setup. This will show you their tag aswell as their ID, their account age, and whether they have been notified within DMs.

## LockBot v3.3.6



**Patches**

* Fixed `permissions` command

**Added**

* New `suggest` command

## LockBot v3.3.5

* Fixed `s-unlock`'s embed of "Unlocking Server" but not doing anything.
* Fixed `maintenance-mode`'s prompt being replaced by another embed.
* Fixed a couple of bugs within `maintenance-mode`.

## LockBot v3.3.4

* Maintenance Mode will now ask you whether you would like the `maintenance-mode` channel able to send messages or not
* Slight adjustments on Maintenance Mode
* Bug fixes
* Updated command descriptions
* Changes to Server Unlock > Maintenance Mode

## LockBot v3.3.3

* Fixed Console spamming when people create and delete channels without a log channel set
* Fixed purge messages not showing the actual messages deleted in the logs
* Added checking to see if the Klock, Block and Mmode modules are enabled if so it would prompt you to disable the module

## LockBot v3.3.2

* Fixed some internal errors
* You must now agree to our Terms and Conditions when inviting Lock Bot to your server. \[Screenshot below]
* Grammar changes
* Shards has been decreased to 19
* K/B-Lock DM Messages are now in embeds

![](https://media.discordapp.net/attachments/807571569106878475/846279447942004757/Screenshot\_20210524\_074803.jpg?width=500\&height=116)

## LockBot v3.3.1

* When a channel has been created/deleted this will now be logged in the Logging System (if enabled).
* If Kick/Ban Lock has been enabled/disabled, this will be logged within the Logging System.
* Maintenance Mode will now log when it has been enabled (only will work if you have the logging system enabled)&#x20;
* Server Unlock will also be logged when Maintenance Mode has been disabled.
* Fixed `RangeError [BITFIELD_INVALID]: Invalid bitfield flag or number.`

## LockBot v3.3.0

* Updated the format of Kick Lock and Ban Lock.
* Added `.config` as an alias to the panel command.

## LockBot v3.2.9

* Updated Panel command
* Logging System for Moderation commands
* Customisable Logging Channel
* Updated slowmode messages to embeds
* S-Unlock has been re-designed for all 3 locking commands.

## LockBot v3.2.8

* Bug Fixes
* Panel command\


## LockBot v3.2.7

* Custom Prefixes that have been set will work after the bot has been restarted.

## LockBot v3.2.6

* K-Lock (Kick Lock) & B-Lock (Ban Lock) is now finally up and running.

## LockBot v3.2.5

* Maintenance Mode now has a max of 60 channels instead of 30.
* If a server has more than 60 channels, it will say how many channels needs removing before using Maintenance Mode.
* Fixed ping on info command.

## LockBot v3.2.4

* Mute command now fixed \[Uses role "Muted" to mute members].

**Note**: When the bot restarts at 00:00 GMT you will have to remove the role manually.

## LockBot v3.1.4

* Fixed Channel Lock from locking random channels.
