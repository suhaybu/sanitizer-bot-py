> [!IMPORTANT]
> This project has been archived in favor for the Rust rewrite which can be found here: [/sanitizer-bot](https://github.com/suhaybu/sanitizer-bot)
> 
> This repo is be no longer maintained or updated.

# Sanitizer Bot (Python)

[![](https://img.shields.io/pypi/v/discord-py-interactions.svg?label=Interactions.py&logo=pypi)](https://github.com/interactions-py/interactions.py)
![](https://img.shields.io/badge/Python-3.12+-1081c1?logo=python)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![License](https://img.shields.io/badge/license-CC0_1.0-v1)](https://github.com/Suhaybu/Sanitizer-bot/blob/main/LICENSE)


## Introduction

Sanitizer is a simple bot that uses regex to identify links for social platforms and replaces them with discord embed friendly links that allows you to view the content of the link without ever having to leave the discord app. You might think this is a bot for lazy people, but I assure you, if you give it a try, you'll never want to go back.

The bot is developed in Python using the `interactions.py` library. Click [here](https://github.com/interactions-py/interactions.py) for their GitHub repo. This GitHub repo is utilized for version control and the assistance of GitHub Copilot has been used for creating examples of implementation from documentations.


## Features

-   **User Privacy first:** No logs are made on any messages users send.
-   **Supports Multiple platforms:** Works with Twitter, TikTok, Instagram.
-   **Automatic conversion:** Automatically fixes any supported links posted.
-   **User Installable App:** The `/sanitize` app command can be used in any context.
-   **Handles Direct Messages:** Will attempt to fix links sent in private.
-   **Implemented QuickVids API:** Implemented QuickVids API to convert TikTok links into embeddable content in discord.

## Getting Started

If you wish to host your own instance of the Sanitizer bot, follow along.

### Prerequisites

-   Python 3.12
-   A Discord account and token

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/suhaybu/sanitizer-bot.git
    ```
2. **Setup virtual Python environment:**
    ```bash
    python3 -m venv .venv
    ```
3. Activate virtual Python environment:
   on Linux or MacOS
    ```bash
    source .venv/bin/activate
    ```
    on Windows
    ```bash
    .venv\Scripts\activate
    ```
3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```
4. **Set up your Bot Token:**
   Add your Discord bot token as `BOT_TOKEN` variable. You may add this to the `.env` file present in the root directory.

5. **Set up your QuickVids Token (for TikTok):**
	Get your QuickVids api token from [here](https://quickvids.win/dashboard/me) and add it to the `QUICKVIDS_TOKEN` variable.

### Running the Bot

Use the following command:

```bash
python3 main.py
```

## Usage

Once the bot is running, you can use the following commands:

-   `/credits`: To roll the credits
-   `/sanitize`: To fix the embed of your link

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Suhayb - [@suhayb_u](https://twitter.com/suhayb_u)


## Acknowledgments
-   [interactions.py](https://github.com/interactions-py/interactions.py)
-   **Twitter:** Thanks to FixTweet's awesome [FxTwitter](https://github.com/FixTweet/FxTwitter) project
-   **TikTok:** Thanks to [QuickVids](https://quickvids.app/) super fast API
-   **Instagram:** Thanks to [InstaFix](https://github.com/Wikidepia/InstaFix)'s reliable service
