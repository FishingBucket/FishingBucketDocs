# Getting started with Fishing Bucket!  

> [!NOTE]
> This was made as of October 17, 2026. (This will be updated as this guide gets updated.)

This guide was made because I was having issues with getting the bot setup and understanding things, So I hope this helps.

## Table of Contents

1. Importing from Fishing Bucket, Pluralkit, Tupperbox, Utter.
2. How to use autoproxy?
3. Command list

## Importing from Fishing Bucket, Pluralkit, Tupperbox, Utter.
**Fishing bucket**


**Pluralkit**


**Tupperbox**


**Utter**


## How to use autoproxy?


## Command list

> [!NOTE]
> There is more than just the prefix in the commands below. I tend to personally use `fb!` but `fish!` is the main one listed in the documentation. (You can also ping the bot and run commands. Ex: `@FishingBucket help`)

**Commands for the bot itself**

`fish!ping` - Gets the bot's latency.

`fish!invite` - Invite me to your community!

`fish!explain` - What do I do?

`fish!stats [stat: stat]` - Get global statistics about the bot.

`fish!dashboard` - Opens the link to the online dashboard.

`fish!website` - Opens the link to the online website homepage.

`fish!legal` - Links to the legal pages on the website.

`fish!contact` - Opens the link to the Contact Us page on the website.

`fish!help [topic: string]` - Provides information about this bot or about a command.

**Proxy Commands**

`fish!register <name: string> <trigger: template>` - Registers a proxy to be used.

`fish!list [page: page] [detailed: boolean]` - Lists your registered proxies.

`fish!find <name: string>` - Finds all of your proxies that matches a certain name.

`fish!info <proxy: proxy>` [detailed: boolean] - Shows you information about a proxy.

`fish!reproxy <new: proxy>` - Changes the proxy of your last message in this channel.

`fish!autoproxy <setting: 'latch' OR 'spotlight' OR boolean OR proxy> [mode: 'global' OR 'community'] [expiration: duration OR 'never']` - Automatically proxies your messages.

`fish!who` - Shows you information about a proxied message.

`fish!delete [bypass: boolean]` - Deletes a proxied message.

`fish!edit <message: string>` - Edits a proxied message.
**Proxy Edit Commands**

`fish!set avatar <proxy: proxy> [url: url]` - Updates a proxy's avatar.

`fish!set triggers <proxy: proxy> <mode: 'set' OR 'add' OR 'remove'> [trigger: template]` - Updates a proxy's triggers.

`fish!set name <proxy: proxy> <new name: string>` - Updates a proxy's name.

`fish!set nickname <proxy: proxy> [new nickname: string]` - Updates a proxy's nickname.

`fish!set pronouns <proxy: proxy> [new pronoun: string]` - Updates a proxy's pronouns.

`fish!set description <proxy: proxy> [new description: string]` - Updates a proxy's description.

`fish!set tags <proxy: proxy> <mode: 'add' OR 'remove'> <tags: proxy tag(s)>` - Updates a proxy's tags.

`fish!set forms <proxy: proxy> <mode: 'set' OR 'add' OR 'remove'> [form: ( <name: string> [avatar: url] )]` - Updates a proxy's different forms.

`fish!set current form <proxy: proxy> [form: string]` - Sets the current form of the proxy.

`fish!remove <proxy: proxy>` - Removes a proxy that you own.

`fish!nuke` - Deletes every proxy associated with your account.

**Tag Commands**

`fish!tag register <name: string> [description: string]` - Creates a new tag.

`fish!tag list [page: page] [detailed: boolean]` - Lists your tags.

`fish!tag info <tag: proxy tag> [detailed: boolean]` - Shows you information about a tag.

`fish!tag members <tag: proxy tag> [page: page] [detailed: boolean]` - Shows you the proxies with a specific tag.

`fish!tag set name <tag: proxy tag> <name: string>` - Updates a tag's name.

`fish!tag set description <tag: proxy tag> [description: string]` - Updates a tag's description.

`fish!tag set marker <tag: proxy tag> [marker: template]` - Updates a tag's marker.

`fish!tag delete <tag: proxy tag>` - Deletes a tag.

**Import / Export Commands**

`fish!import [file: url] [origin: origin]` - Imports proxy data from a file.

`fish!export` - Generates an export of your data.

**Community Staff Commands**

`fish!permissions set <targets: #channel OR @role OR @users OR 'community'> <allow: boolean OR 'default'>` - Changes which members can proxy within the community.

`fish!permissions reset` - Reset all proxying settings in this community.

`fish!permissions list` - See a list of places where proxying is allowed or disallowed.

`fish!log set [channel: #channel]` - Sets the channel to log to on each proxy message.

`fish!log view` - Views the channel that was set as the logging channel in this community.

**User Commands**

`fish!privacy list` - Lists your privacy settings.

`fish!privacy set <status: 'public' OR 'private'> <options: 'all' OR setting(s)>` - Sets your privacy settings.

`fish!link initiate` - Initiates account linking procedure.

`fish!link code <code: string>` - Finishes the account linking procedure.

`fish!link list` - Lists all of your linked accounts.

`fish!unlink` - Unlinks your account.

`fish!account delete` - Deletes every information related to your account.

**Dice Commands**

`fish!dice <expression: string>` - Roll dice or perform arithmetics.

`fish!environment list [target: 'user' OR 'community' OR 'global' OR 'all'] [object: 'variables' OR 'functions' OR 'all']` - Gets all dice environment variables or functions.

`fish!environment set <target: 'user' OR 'community'> <name: word> <value: string>` - Sets a variable or function to be used in dice expressions.

`fish!environment remove <target: 'user' OR 'community'> <name: word>` - Removes a dice variable or function.

**Spotlight Commands**

`fish!spotlight list` - Shows your current spotlight.

`fish!spotlight set [proxies: proxy(s)]` - Sets your current spotlight.

`fish!spotlight add <proxy: proxy>` - Adds a proxy to your current spotlight.

`fish!spotlight clear` - Clears your current spotlight list.

`fish!spotlight pop` - Removes the last entered spotlight proxy.

`fish!spotlight insert <proxy: proxy> [index: integer]` - Inserts a proxy into the current spotlight.