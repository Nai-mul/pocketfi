# PocketFiBot
🖱️ clicker for [https://t.me/pocketfi_bot](https://t.me/pocketfi_bot/Mining?startapp=558455838)

## Recommendation before use
# 🔥🔥 Use PYTHON 3.10 🔥🔥

## Functionality
| Functional                                                     | Supported |
|----------------------------------------------------------------|:---------:|
| Multithreading                                                 |     ✅     |
| Binding a proxy to a session                                   |     ✅     |
| Auto-purchase of items if you have coins (tap, energy, charge) |     ✅     |
| Random sleep time between clicks                               |     ✅     |
| Random number of clicks per request                            |     ✅     |
| Support tdata / pyrogram .session / telethon .session          |     ✅     |

## [Settings](https://github.com/sizifart/PocketFiBot/blob/main/.env-example)
| Настройка               | Описание                                                                   |
|-------------------------|----------------------------------------------------------------------------|
| **API_ID / API_HASH**   | Platform data from which to launch a Telegram session (stock - Android)    |
| **CLAIM_RETRY**         | Number of tryings if **Claim** is unsuccessful _(eg 3)_                    |
| **SLEEP_BETWEEN_CLAIM** | Delay between **Claim** in minutes _(eg 180)_                              |
| **USE_PROXY_FROM_FILE** | Whether to use proxy from the `bot/config/proxies.txt` file (True / False) |

## 📕 Profiles
Possible to create a profile with unique data for each session:
```json
{
  "session1": {
    "proxy": "socks5://yGow3a:uBro3wL@58.195.21.83:9715",
    "headers": {"...": "..."},
    "fingerprint": {"...": "..."}
  },
  "session2": {
    "proxy": "socks5://yGow3a:uBro3wL@58.195.21.83:9715",
    "headers": {"...": "..."},
    "fingerprint": {"...": "..."}
  },
  "...": {}
}
```
> ❕ **Note**:  `session1` и `session2` - are examples of session names.


## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.10**
- Telegram API_ID and API_HASH (you can get them [here](https://my.telegram.org/auth))

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Auto Install/Run
- Click on RUN.bat to automatically install the required dependencies and run the project

## Menual Install/Run
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Please edit the name file .env-example to .env and add your API_ID and API_HASH:
   
## Usage
1. Run the bot:
   ```bash
   python main.py
   ```

## Install/Run into Phone
# Termux Setup 

[Link about python and pip on Termux](https://wiki.termux.com/wiki/Python) that comes with the pkg python

```bash
git clone https://github.com/sizifart/PocketFiBot.git
cd PocketFiBot
pip3 install -r requirements.txt
chmod +x main.py
```
 
# Telegram Channel

✅ Channel for information and training on Telegram airdrop bots 🔷 Follow us on Telegram : [SIZIFAIRDROP](https://t.me/sizifairdrop)
   
# Discussion

If you have an question or something you can ask in here : [F.Davoodi](https://t.me/sizifart)
