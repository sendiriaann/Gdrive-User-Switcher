# Gdrive-User-Switcher
User switcher for Google Drive, because Google won't

---

You opened a folder someone shared with you, yet you access it through the wrong account<br/>
switching through the usual account dropdown will log you out of the folder and back to home instead<br/>
this sucks, and it seems nobody else care much about this so I (ask chatGPT to) make this lil script

the script just fetch current gdrive link you're in:<br/>
https://drive.google.com/drive/home

then adds "/u/(number)/" into it:<br/>
https://drive.google.com/drive/u/0/home

the number correspond to your google account list, which is based on whichever account logged in first<br/>
0 for default account, 1 for 2nd account, 2 for 3rd, so on<br/>
![1](https://media.discordapp.net/attachments/899871890783498300/1434019428491858053/image.png?ex=6906ce2a&is=69057caa&hm=6ad55d365533b63444f9bbe1dc0e13bdaf579c56b71fb23cd9a026e079c1b874&=&format=webp&quality=lossless&width=347&height=518)

with this script, you dont need to edit the link manually anymore<br/>
just add however many accounts you have, and you're set<br>
![2](https://media.discordapp.net/attachments/899871890783498300/1434019741919608853/image.png?ex=6906ce75&is=69057cf5&hm=e8b24c39d009c77027f0f03f4fbb8dda8e14a83dacc6be37bc9d8596012aea0f&=&format=webp&quality=lossless&width=221&height=350)

---

current feature:
- Quick user combobox selection
- Add, Edit, Remove user from list (does not actually logout your account, just from the quick selection)
![3](https://media.discordapp.net/attachments/899871890783498300/1434019923591561278/image.png?ex=6906cea0&is=69057d20&hm=b9ea1d9c58fedf82a797ab5a5f0f498a895c927f5cdd1995f790ba94239bd2b9&=&format=webp&quality=lossless)

⚠ Refresh page after activating script<br/>
⚠ This script cannot see your logged in accounts, so you must add, rename, remove accordingly to every change (its easy dw)
