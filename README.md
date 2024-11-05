# Nikki WA Bot Plus

This is a WhatsApp bot built for group management, including features like tagging all members, muting/unmuting, and many more. It's designed to help admins efficiently manage WhatsApp groups.


---

## 🚀 Steps to Deploy


---

### Step 1: Scan QR Code

Deploy the bot and easily connect it to your WhatsApp account by scanning the QR code. Click the button below to deploy the bot on Replit.

---

### Step 2: Deploy Now

To deploy, click the button below:

<div align="center">
  </a>
  <a href="https://replit.com/@tteokbokki1/Nikki-Bot-Plus?v=1">
    <img src="https://img.shields.io/badge/Deploy_To_Replit-Now-red" alt="Deploy on Replit"/>
  </a>
</div>


### If you are more advanced and want to edit the settings and things, clone the repl and edit it yourself in replit. To deploy elsewhere, download as a zip from Replit and do as you want.


---

---

## ⚙️ Features

- **Tag all group members** with the `.tagall` command
- **Admin restricted usage** (Only group admins can use certain commands)
- **Games** like Tic-Tac-Toe for interactive group engagement
- **Text-to-Speech** with `.tts`
- **Sticker creation** with `.sticker`
- **Anti-link detection** for group safety
- **Warn and manage group members** with admin control

---

## 📖 About

The WhatsApp Bot assists group admins by providing them with tools to efficiently manage large WhatsApp groups. The bot uses the Baileys library to interact with the WhatsApp Web API and supports multi-device features.

It is lightweight and can be easily customized to add more commands as per your requirements. The bot runs in a Node.js environment and provides QR code-based authentication to link your WhatsApp account.

---


## 📝 Commands

### General Commands:

- `.help` or `.menu`
- `.tts <text>`
- `.sticker` or `.s`
- `.owner`

### Admin Commands:

- `.ban @user`
- `.promote @user`
- `.demote @user`
- `.mute <minutes>`
- `.unmute`
- `.delete` or `.del`
- `.kick @user`
- `.warnings @user`
- `.warn @user`
- `.antilink`

### Game Commands:

- `.tictactoe @user`
- `.move <position>`

### Group Management:

- `.tagall`

### Other:

- `.topmembers`

---
