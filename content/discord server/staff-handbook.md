---
title: Staff Handbook
type: docs
---

# The OSD Staff Handbook

Welcome to Staffing on the Officially Official OneShot DiscordTM (Copyright 2016 /s). This handbook will give you everything you need to know about moderating the place and keeping it nice and clean, whether you're brand new or just checking in.

## New Staff, Start Here!

If you're brand new to the Staff team, you'll need to do this first. DM either `@renavi` or any previously active Staff member and ask for your email address to be added to the OneShot Google Drive folder. You'll need to use it in the event that coordination is needed, or just to view a previous log from basement.

Keep in mind that you'll have access to this Staff drive even if you choose to take a break with Ex-Staff. You will only lose access to this drive if you are demoted.

Once you have that done, consider making yourself a personal role (at the bottom of the role list, with the others), then continue on for the rest of this!

## Staff Guidelines

First and foremost, here are some guidelines that all Staff are expected to uphold while Staffing.
1. Be respectful to the users. You may be in a position of power, but you are still a member of the community, and should engage with the community as such.
2. Take breaks, but don't go missing. Everyone needs breaks sometimes, however things can get a bit confusing if there are one or more members of the Staff team who are part of the team, but don't show up. If you need an extended break, please use `pls modtoggle`.
3. Don't drown in your moderation responsibilities. Remember, you're a Staff member! Feel free to contribute in `#tower` for ways to improve the server, concerns about user behavior, etcetera. Users might get scared of a Staff member that only deals with moderation!
4. Work with the team, but use your judgment. There are times in which you might have to handle a situation entirely by yourself. In that case, use your best judgment when handling the situation. You can also ping `@Staff` in `#tower` as well, if you need help! And if you know of a previous example, use that! If you're working with other Staff in handling a situation, try not to dominate the conversation! Remember that you're working as a team.

## A High Level Overview

With that out of the way, how *do* you moderate? Well, take an example user who breaks the rules. Depending on severity, there are several different courses of action, each more harsh than the last.

1. Verbal warning. You can verbally tell them off, if the infraction is relatively minor. If it's light enough, you could do so in public, but if you need to take it somewhere private, you'll need to go to the next course of action.
2. Basement toss. Using `pls toss` (preferably in `#old-factory` to avoid causing the chat to ramp up in intensity, though you can do so in public if you need to set an example) will send a user to the basement. More details later, but you can use the basement to have a Staff-on-one conversation between you and the user, away from the public chats. This is very useful, do not be afraid to use it!
3. Formal warning. Given with `pls warn`, use this if an offense is severe enough to warrant it. This will log a formal warning to the user in `@Dishwasher`, and more on that is later. **Do not give out warnings for no reason!**
4. Ban. If the user isn't cooperative, or they have reached the warning limit, ban them! In most cases, they will not learn from their mistakes by this point, but you are advised to send the ban appeal their way regardless (Dishwasher will automatically forward it when using `pls ban`).

## The Tools You'll Use

Here are general overviews for the moderation bots that you'll need to know about.

### Shokki Araiki / Dishwasher

Dishwasher is the OneShot Discord's main moderation bot, coded by `@renavi`. You'll be using it to warn, toss, kick, ban, manage ban logs, archive basement sessions, and more. You are advised (and expected) to get familiar with it! This handbook covers the commands you'll need to do your part for the Staff team, but more commands are available on its [documentation](https://kitchen.0ccu.lt).

As `@renavi` is the one managing this bot, please ping her should you encounter a bug with it.

### Robohex

Robohex is our ModMail bot. Youll see the tickets come up in `📫 Console Input` when someone opens a ModMail. More information on this later.

### Watcher

Watcher handles the slowmode for the public chats. All you'll need to know with Watcher is that you can use `/settings` to view a channel's sensitivity settings, and `/set sensitivity` to set the sensitivity.

## How To:

Here are detailed explanations for how each component of Staffing works. You'll quickly get accustomed to it.

### Toss

When tossing a user (or, users), it is heavily advised to do so away from the public chats, to prevent any boiling over. Think of the "ooh, someone's in trouble!" thing, that's rather hard to quell. It's recommended to perform tosses in `#old-factory`.

To perform a toss, you'll need to either mention a user, or use their IDs. IDs are much preferred, and you'll need Developer Mode enabled for them. `Settings > Advanced > Developer Mode`. You can also use usernames, if that is easier for you.

Once you have their name, mention, or ID, simply use `pls toss USER`. If you are tossing multiple users, separate them with spaces, such as `pls toss USER1 USER2`.

When tossing a user, `@Dishwasher` will create a new "session" for you, in `🚷 Lower Tower`, with a max of four sessions open at a time. The tossed user (or users) will be pinged, and given a timer to respond. When they do, or when the timer expires, you will be pinged.

Depending on the user, you'll take your next courses of action in the session channel. If they are uncooperative, they likely aren't a good fit for the server. Use your best judgement here.

If you need to add more users to the session, simply use `pls toss` again within the session channel, and they will be added.

When you're done (and you haven't kicked or banned them), you can use `pls untoss USER` to untoss the user and return them to the public chats. If you run `pls untoss` by itself, it will untoss every user.

Once you've done that, you'll need to close the channel. To do this, simply run `pls close`, and the channel will be closed and deleted for you.

In the event that the bot complains about nobody being in the toss cache, run `pls archive USER`, and delete the channel manually.

### Warn, Note, and Log

You'll want to keep tabs on users, but you can't know everything. That's why `@Dishwasher` has a simple log system.

To warn a user, run `pls warn USER Your Reason Here`. Preferably do this with the user, during a basement session, so they are aware of why they are being warned.

To view a user's logs, run `pls logs USER`. This will tell you each occasion in which they have been tossed, warned, kicked, and banned, as well as any notes that they may have.

To view a user's notes, run `pls notes USER`. To add a note to a user (you do not have to do this in front of them), run `pls note USER`.

You are advised to check the [warning system](https://discord.com/channels/256926147827335170/1155312248282153081/1155318807217328139) in the server rules, such that you may know when it is necessary to ban a user.

### Ban

Dishwasher has many different commands to ban a user. Here's a quick rundown of them:
- `pls ban` will ban a user, DMing them that they are banned, a reason for their ban if provided, and a link to the appeal form. For example, `pls ban kitchensink Terrible bot.`.
- `pls unban` will unban a user.
- `pls sban` will ban a user without DMing them anything.
- `pls massban` will ban a list of users, **separated by spaces**. The bot will not convert newlines.

### Raids

In the event of a raid, __do not panic!__ Ping `@Staff` in `#tower` to notify everyone, and use `pls raidmode on` to enable `@Dishwasher`'s raid mode, posting every new user to `#tower`.

Once done, do your best alongside the other Staff members to ban every user involved in the raid as immediately as you can. Do not worry about proper procedure when handling raids, focus on stemming the tide as soon as you can! Take advantage of other Dishwasher commands, such as `pls lock` in the event that they are spamming public chats, and `pls massban` to ban many at the same time.

Be careful not to confuse regular users with raiders! During a raid, many users will pop into the chat wondering what's going on. Use `pls lock` to your advantage here. You may also have to remind users to not pop in and ask what's going on during a raid, as that will lead to more confusion.

Do your best in this scenario!

### ModMail

To handle modmails, you'll need to be familar with `@Robohex`'s commands.

When a user uses ModMail, they are DMing the bot, which in turn posts their messages into the channel the bot makes. Channels have unique names as to not identify any users by API leaks.

Here's a brief overview of Robohex commands that you can use in a thread.

- `>r` will reply, sending a message back to the user.
- `>ar` will do as the above, but anonymously.
- `>close` will close the thread. Adding `-s` will do so silently, without notifying the user. Adding a time (such as 30m, 30s, 30h, etc.) will delay a close to a specified delay.
- `>alert` will alert you to the next post from the user.
- `>edit` with the number of the message provided by `@Robohex` will allow you to edit a message.
- `>delete` with the number of the message provided by `@Robohex` will allow you to delete a message.
- `>logs` with an ID will show you previous modmail logs with the user.
- `>block` with an ID will block a user from using the bot. Adding a time (as in close) will prevent them from using the bot for a specified time.
- `>unblock` reverses the above.
- `>is_blocked` with an ID will check if a user is blocked.
- `>newthread` with an ID will start a new thread with a user.

People may use modmail to apply for various channels. When they do so, you can use specific commands to send boilerplate messages to them. For example:
- `>>cafe` will send a boilerplate message for `#cafe`.
- `>>bar` will send a boilerplate message for `#bar`.
- `>>both` will send a boilerplate message for `#cafe` and `#bar`.
- `>>dev` will send a boilerplate message for the Mod Developer role, which enables posting in `#terminal-data`.
- `>>raid` will send a boilerplate response for a user reporting a raid.

For the mails requesing entry into a channel, make sure they confirm that they have read the rules, and then ping `@Staff` with a yes or no reaction vote. When the majority of Staff have voted (visible with `pls staff`), respond with the outcome.

### Appeals

When a user appeals a ban, it'll be sent to the `#banana-peals` channel. If `@Dishwasher` is working correctly, a poll and thread will be made for you. Simply vote on each poll, and offer your opinions on each user in their threads.

If an appeal goes through, unban the user with `pls unban`, and notify them, whether through Discord or Email. The Staff Email is available in `#tower` pins.

### Ban Log

When a user gets banned, unbanned, or kicked, a new case will be made in `#safety-violations`. If you are the one to ban, you are expected to provide a reason for your ban if you haven't already, for public logs. You can add a reason by using `pls reason CASEID Reason Here`.

In some scenarios, you might have to reason multiple cases, in the event of multiple bans. In that case, you can use the two case IDs, separated by either `-` or `..`. For example, `pls reason 5000..5010 Trolls.`. If you are reasoning for more than 20 users, Dishwasher will warn you that you are doing so. Be careful!

In the event someone has a racist username or display name, or something else wildly offensive that we shouldn't show in the public ban logs, use `pls censor` with their case ID. Dishwasher will redact the username by replacing it with a blank space.

If you need to dump user IDs for whatever reason (such as getting a list of raiders), use `pls dump caseid..caseid`. Any user is allowed to use this command.

### Clean Up

You'll probably need to clean up a few messes in the public chats sometimes. `@Dishwasher` has you covered in that regard, and here are a few commands and their uses in order to handle situations.

- `>pls lock` will lock a chat, preventing users from speaking.
- `>pls unlock` will unlock a chat, enabling speaking once more.
- `>pls purge` will purge the chat. You'll need to add some modifiers to it, detailed below.
- `>pls slowmode` with a number will set the slowmode. Do not do this in chats managed by Watcher, as it will be overriden.

#### Purging

`pls purge` has numerous modifiers. When using a purge command, you can always apply the following at the end:
- The number of messages you'd like purged.
- The channel you'd like to purge messages in.

For example, `pls purge 50 #barrens` will purge 50 messages from `#barrens`.

You may also make `purge` more specific, by adding a modifier between the number of messages, and the command itself. Here are some modifiers:
- `bots` - This will only purge bots.
- `from` - This will purge messages from a certain user. You'll have to specify the user afterwards. For example, `pls purge from @renavi 10 #old-factory`.
- `with` - This will purge messages with a certain string. If you are using spaces, you must enclose the string in quotes. For example, `pls purge with "this is a test" 20 #old-factory`.
- `emotes` - This will purge messages with emotes.
- `embeds` - This will purge messages with embeds, including stickers.
- `reacts` - This will clear reactions from messages, **but will not delete the messages**. Good for reaction spam.
