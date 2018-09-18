# FutureBot
FutureBot is a Discord bot build with discord.py imported into Julia to aid with roommate-related tasks.

## About FutureBot
### Why is it called FutureBot?
There was a running joke when my roommates and I were looking at places in Philadelphia to rent that we needed a nickname system to differentiate places rather than using the addresses (it became quite tedious to keep track of all those addresses). As a result we used nicknames to name all the places that we were interested in renting. We eventually ended up signing a lease to the place we dubbed "Futureeeee" because of how modern and affordable the house was. Thus, "FutureBot" aims to aid all of our roommate interactions here at "Futureeeee".

### Why code this bot in Julia?
I've been wanting to learn the language for a while now just for fun and personal use, and I thought that this project would be a great way to get some exposure to the language through experimental learning.

### What is the goal of this project?
The goal of the project is to utilize Julia's PyCall library to import discord.py and use it in the Julia language. The ultimate goal is to obviously create some neat and nifty features for the bot to make our lives as roommates easier. Though we may end up not actually using the bot, perhaps it may be of use to someone else out there on the Internet looking for solutions to roommate-related tasks.

### Will this bot be public?
I will not be making this bot public as I do not want to bear the responsibility of hosting this bot for others to use. However, you're more than welcome to register your own bot at [Discord's Developer Portal](https://discordapp.com/developers) and host it yourself. If you do decide to use this bot, I'd love to see some screenshots of someone else putting my work to good use! :)

## Notes
* Currently the Makefile assumes that the user is running Julia v1.0.app (MacOS). If you're not running v1.0 and MacOS then either directly run "bot.jl" or modify the Makefile to fit your needs.
