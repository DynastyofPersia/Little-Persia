Installation
The following procedure documents how to set up the TLOPO Discord Bot.

Open a new instance of Terminal (UNIX/Mac) or Command Prompt (Windows).
Change your current working directory to the TLOPO Discord Bot source code.
Run the following command to install the dependencies that the bot needs to run: python3 -m pip install -r requirements.txt
Once that has completed, you're ready to start the bot. Use the following command to start: python3 -m bot.core.BotStart
You'll be prompted to configure the bot.
Make sure to edit settings.json and include the secret key for the App Bot User provided by Discord on the Discord Developers page. Other settings relating to the bot's operation can also be configured here.
