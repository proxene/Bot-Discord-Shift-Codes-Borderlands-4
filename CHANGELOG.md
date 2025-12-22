## [2.0.2] – 2025-12-22

- ⚠️ Fixed a critical issue where SHiFT codes were not being persisted correctly, causing repeated notifications.
- Added better error handling and logging for data persistence failures.
- Improved overall stability of the SHiFT code checking loop.

<br>

## [2.0.1] - 2025-10-06

- Improved SHiFT code detection and reliability.
- Enhanced date formatting for better clarity and consistency.
- General stability and performance improvements.

<br>

## [2.0.0] - 2025-10-03

- Updated Python and discord.py versions.  
- Updated expiration check logic for `/codes` and `/checkcode` commands.
- Fixed compatibility with Python 3.12/3.13.  
- Fixed compatibility with discord.py 2.4.0/2.6.3.
- Added the **Vault Hunt** event.  
- Added `/vault` and `/vaultopt` commands.  
- Added autocompletion for commands.
- Improved interaction interfaces with the bot.  
- Removed support for commands in DMs.
- Users no longer see admin commands when typing slash commands.  
- Buttons in interactive interfaces are now disabled if the view times out.  
- General stability improvements.  
- General translation improvements.  

<br>

## [1.0.4] - 2025-09-28

- Fixed an issue where the `/codes` command displayed expired codes.  
- Improved formatting: rewards are now shown on a single line and codes are visually separated for easier reading.  
- Removed unnecessary long text blocks — only the essential information is shown. 

<br>

## [1.0.3] - 2025-09-25

- Global improvements.
- The bot is now faster at posting codes as soon as they are discovered.
- Added a friendly **Gortys-style welcome message** when the bot joins a new server.
- Removed the /support and /donate commands. These have been replaced with buttons.

⚠️ Important : If no channel is configured with /setchannel, **no SHiFT codes will be posted**.  

<br>

## [1.0.2] - 2025-09-23

  - Fixed commands failing in DMs.
  
  - Added clear user feedback when a command is used outside of a server:<br>
  "❌ This command can only be used in a server."

<br>

## [1.0.1] - 2025-09-21

- Fixed issue where the last four codes might have been sent twice.
- Added new command to list all active codes.

<br>

## [1.0.0] - 2025-09-19
- First release of the bot.
