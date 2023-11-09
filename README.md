# SM Community Bot 

SM Community Bot is a specialised Discord bot tailored for NFT communities. It brings together a set of interactive and administrative functions to cover underserved admin functions alongside fun community experiences. Each function is maintained as a separate script/module for improved scalability and easier maintenance.

## Features

### Admin Message Scheduling
- **Module:** `scheduling.py`
- **Functionality:** Schedule messages to be sent out by the bot at specified times. Ideal for reminders, announcements, or any recurring message needs.
This function takes a 'draft' (ie already posted in a private channel) message and re-posts it to a designated channel at a designated date and time.
- **Usage:** Commands for setting up, editing, and deleting scheduled messages can be accessed through designated admin commands.

### NFT Top Trumps
- **Module:** `nft_top_trumps.py`
- **Functionality:** Engage with your community through a fun NFT Top Trumps game. The bot reads from a provided JSON collection and turns it into an interactive game where members can "battle" with NFT attributes.
- **Usage:** Trigger a Top Trumps game with a simple command, followed by selections for the NFTs to be drawn into the battle.

### Member FAQ
- **Module:** `faq.py`
- **Functionality:** Answer frequently asked questions automatically. The bot serves an FAQ menu on-demand, viewable to only the user who initiated and reproduces answers to questions, selected via reaction.
- **Usage:** Members can ask questions in a designated channel or directly to the bot to receive instant answers.

### Quiz Game
- **Module:** `quiz.py`
- **Functionality:** A 3, 5 or 10 question quiz which can be instagated by any user and be either a solo or 1v1 event. Questions and answers are visible only to participants, with a message announcing the winner / 1p score visible to all at the end of the quiz.
- **Usage:** Anyone can start a quiz with a command, and members can join in and answer through direct messages to the bot or in a specific channel.

## Installation

## Configuration
Before you run the bot, ensure you've set up the necessary configuration. This includes setting your Discord bot token, configuring the command prefix, setting up any required permissions and adding your own FAQ and quiz content and a complete JSON of your NFT collection (for the Top Trumps game).

## Contribution
Contributions to SM Community Bot are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your proposed changes.

## License
SM Community Bot is released under the MIT License.

## Support
If you have any questions or need help with SM Community Bot, please open an issue in the GitHub repository or contact the maintainers directly.

Thank you for using SM Community Bot, and enjoy engaging your NFT community!