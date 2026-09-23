# Telegram GPT Chat Bot 🧠

Bot Telegram në Python që i përgjigjet **çdo mesazhi** me inteligjencë artificiale (GPT).

## Si funksionon
Çdo tekst që i dërgon botit dërgohet te një GPT API dhe përgjigja kthehet në chat. Në versionin origjinal përdoret një endpoint i jashtëm GPT.

## Si ekzekutohet versioni real
1. Instalo libraritë: `pip install pyTelegramBotAPI requests`
2. Krijo një bot me [@BotFather](https://t.me/BotFather) në Telegram dhe merr **token-in**
3. Vendose token-in në `original/bot.py`
4. Konfiguro URL-në e GPT API-së sipas ofruesit që përdor
5. Ekzekuto: `python original/bot.py`

> ⚠️ Mos e ndaj token-in e botit me askënd. Përdorimi i API-ve GPT mund të ketë kosto — kontrollo kuotën tënde.

## Demo në browser
Dosja `demo/` përmban një **simulim edukativ**: boti përgjigjet me rregulla keyword të gatshme në shqip/anglisht (përshëndetje, orë, mot, barcaleta etj.), jo me GPT të vërtetë.

---
Krijuar nga **Erion Nezha** — © 2026 Të gjitha të drejtat e rezervuara
