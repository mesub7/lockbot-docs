---
description: >-
  This page will be periodically updated with details from the update log
  channel in the discord server. If you want the changelog as soon as it is
  released, join the discord server.
---

# Change Log

## LockBot v3.3.1

* When a channel has been created/deleted this will now be logged in the Logging System \(if enabled\).
* If Kick/Ban Lock has been enabled/disabled, this will be logged within the Logging System.
* Maintenance Mode will now log when it has been enabled \(only will work if you have the logging system enabled\) 
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
* Panel command 

## LockBot v3.2.7

* Custom Prefixes that have been set will work after the bot has been restarted.

## LockBot v3.2.6

* K-Lock \(Kick Lock\) & B-Lock \(Ban Lock\) is now finally up and running.

## LockBot v3.2.5

* Maintenance Mode now has a max of 60 channels instead of 30.
* If a server has more than 60 channels, it will say how many channels needs removing before using Maintenance Mode.
* Fixed ping on info command.

## LockBot v3.2.4

* Mute command now fixed \[Uses role "Muted" to mute members\].

**Note**: When the bot restarts at 00:00 GMT you will have to remove the role manually.

## LockBot v3.1.4

* Fixed Channel Lock from locking random channels.

