# pwnagotchi_plugins
Pwnagotchi plugins
This is a bit modified better_quickdic plugin.
To use it you neet to copy it to custom plugin folder and install
```
sudo apt install python3-python-telegram-bot python3-qrcode
```
and add to you config.toml
```
main.plugins.quickdic.enabled = true
main.plugins.quickdic.face = "(   ^i  )"
main.plugins.quickdic.wordlist_folder = "/home/pi/wordlists/"
main.plugins.quickdic.api = "tokentelegram"
main.plugins.quickdic.id = "chatid"
```
