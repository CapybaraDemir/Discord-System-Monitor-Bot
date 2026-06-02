# Discord System Monitor Bot

A Discord bot developed with Python, discord.py, and psutil to monitor and report real-time system information.

## Features

- CPU monitoring
- RAM usage information
- Disk usage statistics
- Network activity tracking
- System uptime monitoring
- RAM warning notifications
- Separate Discord commands for each system parameter

## Commands

| Command | Description |
|----------|-------------|
| !cpu | Shows CPU information |
| !ram | Shows RAM usage |
| !disk | Shows disk statistics |
| !ag | Shows network information |
| !uptime | Shows system runtime |
| !uyari | Displays RAM warning status |
| !yardim | Lists available commands |

## Technologies Used

- Python
- discord.py
- psutil

## Installation

Install required libraries:

```bash
pip install discord.py psutil
```

Run the bot:

```bash
python bot.py
```

## Note

Replace the bot token inside `bot.py` with your own Discord Bot Token before running the project.
