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
0 for default account, 1 for 2nd account, 2 for 3rd, so on

with this script, you dont need to edit the link manually anymore<br/>
just add however many accounts you have, and you're set<br>

---

current feature:
- Quick user combobox list
- Add, Edit, Remove user from list (does not actually logout your account, just from the quick selection)

⚠ Refresh page after activating script<br/>
⚠ This script cannot see your logged in accounts, so you must add, rename, remove accordingly to every change (its easy dw)
