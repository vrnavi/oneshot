---
title: Dishwasher Help
type: docs
---

# Dishwasher Help

Here are the accessible commands, sorted by category. **Hidden commands are not shown.**

## User Commands

These commands are accessible to all users.

### Basic Features

`help`
- Gives you a link to this page.

`ping`
- Shows the bot's latency.

`membercount`
- Shows the current member count of the server.

`journalcount`
- Shows the current member with Strange Journal count.

`hello`
- Says hello to you.

`hug`
- Gives you a hug.

`install`
- Gives you instructions on how to install a dishwasher.

`kill` [text or mention]
- Kills someone.

`dec` [number]
- Converts Base16 to Base10.

`hex` [number]
- Converts Base10 to Base16.

### Reminders

`remind` [time] [text]
- Reminds you about something in DMs.
- Use "number then unit" format, such as *5s*, which is the minimum.

`remindlist`
- Lists your reminders.

### Server Specific

`pingmod`
- Pings the mods.

`myuserlog`
- Lists actions taken on you by Staff.

## Staff Commands

These commands are used by the Staff for moderation.

### Basic

`modtoggle`
- Toggles between your Ex-Staff and Staff role.

`ban` [target] {reason}
- Bans a user and messages them with the reason.

`bandel` [target] [duration] {reason}
- Bans a user with a specified amount of days worth of messages deleted, messages them with the reason.

`silentban` [target] {reason}
- Bans a user without messaging them.

`hackban` [target] {reason}
- Bans a user with their ID without messaging them.

`massban` [targets]
- Bans several users with their IDs without messaging them.

`unban` [target] {reason}
- Unbans a user.

`kick` [target] {reason}
- Kicks a user.

<!-- `mute` [target] {reason}
- Mutes a user. Command is nonfunctional.

`unmute` [target]
- Unmutes a user. Command is nonfunctional. -->

<!-- `approve` [target] {role (journal)}
- Adds a role to a user, defaulting to Strange Journal.

`revoke` [target] {role (journal)}
- Removes a role from a user, defaulting to Strange Journal. -->

`purge` [limit] {channel (current)}
- Clears a given number of messages.

`warn` [target] {reason}
- Warns a user.

### Lockdown

`lock` {channel (current)} {soft (false)}
- Prevents people from speaking. Defaults to the current channel, and with a "hard" tone.
- Use true/false with the "soft" argument to adjust.

`unlock` {channel (current)}
- Unlocks speaking. Defaults to the current channel.

### Reactions

`clearallreacts` {channel (current)} {limit (50)}
- Clears all reactions in a channel.

`clearreactsbyuser` [user] {channel (current)} {limit (50)}
- Clears all reactions from a user.

`clearreactsinteractive`
- Clears reactions in an interactive fashion.

### Notes

`note` [target] {note}
- Adds a note to a user.

Add `id` to the end of either command to use an ID in the place of a mention.

### Watch

`watch` [target] {note}
- Puts a user under watch, with a marker in their userlog.

`unwatch` [target] {note}
- Removes a user from watch, with a marker in their userlog.

Add `id` to the end of either command to use an ID in the place of a mention.

### Timer

`deletejob` [timestamp] [jobtype] [jobname]
- Removes a timed job.
- Get *timestamp*, *type*, and *name* from `listjobs`.

`listjobs`
- List all timed jobs.

### Puppet Features

`botnickname` {nickname}
- Sets the current nickname. Send command by itself to reset.

`nickname` [target] {nickname}
- Sets a users nickname. Send command by itself to reset.

`playing` [game]
- Sets the bot's "currently playing" status. Send command by itself to reset.
- Change lasts until next playing rotation.

`reply` [channel] [message] [text]
- Replies to a message in a given channel with a given text.

`say` [text]
- Repeats some text.

`speak` [channel] [text]
- Repeats some text in a given channel.
