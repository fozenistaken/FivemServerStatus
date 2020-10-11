# FiveM Server Status
FiveM Server Status Discord Bot

FiveM sunucuları ve bir discord topluluğu ile etkileşim için işlevsellik sağlayan özel bir discord botu

## Tavsiye

- Eğer bilgin yoksa hiç girişme

## Gereksinimler:

- fivemqueue bulunmalı

## Kurulum

1. fivemqueue dosyasını paketinizi ekleyin
2. server.cfg den startını verin
3. Aşağıdaki değişkenleri kendinize göre ayarlayın

```
URL_SERVER - server urlniz örn. http://127.0.0.1:3501 (sonuna `/` koymayın)
LOG_LEVEL - 0-4 arasında bişey yazın (size kalmış)
BOT_TOKEN - Discord bot tokeniniz
CHANNEL_ID - serveriniin loglarının atılacağı kanal idsi
MESSAGE_ID - editlenecek mesaj idsi (gerekli değil)
SUGGESTION_CHANNEL - öneri kanalı idsi
BUG_CHANNEL - bugların raporlanacağı kanalın idsi
BUG_LOG_CHANNEL - raporlanan bugların atılacağı kanal idsi
LOG_CHANNEL - log kanalı
```
## Çalıştırma
1. `npm i`
2. `npm start` or `node ./index.js`


## Komutlar
1. +status <Message> status komutuna eklenecek mesaj.
2. +status status komutuna eklenen mesajı sıfırlama.
  
![Screenshot](https://media.discordapp.net/attachments/424886239410388992/625739298846801936/unknown.png)

## Credits
- Roque https://github.com/RoqueDEV
- Douile https://github.com/Douile
- drazero https://github.com/draZer0
- Queue script: https://github.com/anderscripts/FiveM_Queue
