Project 1
Research & Documentation

Setup:
- how to get and API token
	To get API token for Discord bot, I had to go to the developer portal, create a new application, create a bot, and copy the bot's token. 
- where to put it to work with the code
	Once token was copied, you had to make a .env file in the same directory as the bot.py file. Within .env, you typed 'DISCORD_TOKEN=' and paste your token and save.
- dependencies
	You need to pip install -U discord.py and pip install -U python-dotnev
	One may have troubles about having the right version of python. Make sure you are running on python 3 and up or you may run into issues.

Usage:
- what commands you can type in your Discord server
	I set the command you can type in Discord server as 'marco'
- what response will the bot provide
i	The bot will respond in one of these four ways: 'Polo, did I win marco polo?', 'POOOOOLLLLLLLOOOOOOO', '~polo~','ahhhhhhhh, you found me'.

Research:


	I have found multiple ways to keep a bot running while host pc is off. All of them are pretty similar which is have it running on a software that can keep it on. Using a remote host that can run on a bot with specific software like heroku, virtual private server, rasberry. Or you can use a free version for simple solving which is repl.it. I think this would work either way because as long as the remote locations are on then the bot can stay on.
