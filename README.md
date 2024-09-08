# TapSwapBot
🖱️ clicker for [https://t.me/tapswap_bot](https://t.me/tapswap_mirror_bot?start=r_558455838)

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

## [Settings](https://github.com/sizifart/TapSwapBot/blob/main/.env-example)
| Настройка                | Описание                                                                                 |
|--------------------------|------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**    | Platform data from which to launch a Telegram session _(stock - Android)_                |
| **MIN_AVAILABLE_ENERGY** | Minimum amount of available energy, upon reaching which there will be a delay _(eg 100)_ |
| **SLEEP_BY_MIN_ENERGY**  | Delay when reaching minimum energy in seconds _(eg [1800,2400])_                         |
| **ADD_TAPS_ON_TURBO**    | How many taps will be added when turbo is activated _(eg 2500)_                          |
| **AUTO_UPGRADE_TAP**     | Should I improve the tap _(True / False)_                                                |
| **MAX_TAP_LEVEL**        | Maximum level of tap pumping _(up to 20)_                                                |
| **AUTO_UPGRADE_ENERGY**  | Should I improve the energy _(True / False)_                                             |
| **MAX_ENERGY_LEVEL**     | Maximum level of energy pumping _(up to 20)_                                             |
| **AUTO_UPGRADE_CHARGE**  | Should I improve the charge _(True / False)_                                             |
| **MAX_CHARGE_LEVEL**     | Maximum level of charge pumping _(up to 5)_                                              |
| **APPLY_DAILY_ENERGY**   | Whether to use the daily free energy boost _(True / False)_                              |
| **APPLY_DAILY_TURBO**    | Whether to use the daily free turbo boost (_True / False)_                               |
| **RANDOM_CLICKS_COUNT**  | Random number of taps _(eg [50,200])_                                                    |
| **SLEEP_BETWEEN_TAP**    | Random delay between taps in seconds _(eg [10,25])_                                      |
| **USE_PROXY_FROM_FILE**  | Whether to use proxy from the `bot/config/proxies.txt` file _(True / False)_             |


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
git clone https://github.com/sizifart/TapSwapBot.git
cd TapSwapBot
pip3 install -r requirements.txt
chmod +x main.py
```
 
# Telegram Channel

✅ Channel for information and training on Telegram airdrop bots 🔷 Follow us on Telegram : [SIZIFAIRDROP](https://t.me/sizifairdrop)
   
# Discussion

If you have an question or something you can ask in here : [F.Davoodi](https://t.me/sizifart)
