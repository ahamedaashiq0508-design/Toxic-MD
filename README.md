<div align="center">

# Toxic MD — WhatsApp Bot

![Node.js](https://img.shields.io/badge/Node.js-20+-brightgreen?style=flat-square&logo=node.js)
![Platform](https://img.shields.io/badge/Platform-WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![Multi-Device](https://img.shields.io/badge/Multi--Device-Supported-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![Version](https://img.shields.io/badge/Version-1.2.0-blue?style=flat-square)

**A powerful, lightning-fast WhatsApp Multi-Device bot built for group control, automation, AI chat, media editing, and fun commands^^**

<img src="https://raw.githubusercontent.com/xhclintohn/Music-Clips-Collection/main/images/toxicx.png" width="100%" />

</div>

---

## 🌍 Read This README In Your Language

This README is in English by default. Full translations live in the [`Langs/`](Langs) folder:

| Language | Link |
|---|---|
| Swahili | [Read the Swahili (Kiswahili) README](Langs/sw.md) |
| Spanish | [Read the Spanish (Español) README](Langs/es.md) |
| French | [Read the French (Français) README](Langs/fr.md) |
| German | [Read the German (Deutsch) README](Langs/de.md) |
| Portuguese | [Read the Portuguese (Português) README](Langs/pt.md) |
| Arabic | [Read the Arabic (العربية) README](Langs/ar.md) |
| Hindi | [Read the Hindi (हिन्दी) README](Langs/hi.md) |
| Chinese | [Read the Chinese (中文) README](Langs/zh.md) |
| Japanese | [Read the Japanese (日本語) README](Langs/ja.md) |
| Korean | [Read the Korean (한국어) README](Langs/ko.md) |
| Russian | [Read the Russian (Русский) README](Langs/ru.md) |
| Turkish | [Read the Turkish (Türkçe) README](Langs/tr.md) |
| Indonesian | [Read the Indonesian (Bahasa Indonesia) README](Langs/id.md) |
| Hausa | [Read the Hausa README](Langs/ha.md) |
| Yoruba | [Read the Yoruba (Yorùbá) README](Langs/yo.md) |
| Amharic | [Read the Amharic (አማርኛ) README](Langs/am.md) |

Change the bot's reply language anytime with: `.language <code>` (Owner only)

---

## 📖 About

**Toxic-MD** is a modern WhatsApp bot built on the **Baileys Multi-Device** library. It helps you manage groups, automate repetitive tasks, protect your chats, and enjoy a wide range of fun and utility commands — all in a single, easy-to-deploy package.

### Why Toxic-MD?

| Feature | Details |
|---|---|
| ✅ Multi-Device Support | No constant QR scanning required |
| ⚡ Fast & Stable | Optimized for continuous uptime |
| 🚀 Easy Deployment | Works on any hosting platform |
| 🧑‍💻 Beginner Friendly | Simple setup, clear documentation |
| 🔧 Highly Customizable | Flexible prefix, modes, settings, and languages |
| 🤖 AI-Powered | Auto AI chat with Groq/Llama |
| 🛡️ Group Protection | Anti-link, anti-badword, anti-group-status, anti-delete, view-once recovery, and more |
| 🌐 Multi-Language | 17 languages supported |
| 📊 Auto Reports | Daily group stats posted to group status |

## Deploy the Bot

#### Step 1 — Fork the Repository

[![Fork Repo](https://img.shields.io/badge/FORK%20REPOSITORY-brightgreen?style=for-the-badge&logo=github)](https://github.com/xhclintohn/Toxic-MD/fork)

#### Step 2 — Pair Your WhatsApp

[![Pair WhatsApp](https://img.shields.io/badge/PAIR%20WHATSAPP-blue?style=for-the-badge&logo=whatsapp&logoColor=white)](https://fork.toxicx.tech)

#### Step 3 — Deploy the Bot

[![Deploy Bot](https://img.shields.io/badge/DEPLOY%20BOT-orange?style=for-the-badge&logo=rocket)](https://fork.toxicx.tech)

### Quick Start

1. Visit: **https://toxicx.tech/pairing**
2. Open WhatsApp on your phone
3. Go to **Settings → Linked Devices**
4. Tap **Pair Device** and scan or enter the pairing code

```env
SESSION=eyJub2lzZUtleSI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiSUcyNEhWeEVuL1ErMzBOUHZLMUE5K1NvTHFxS0RGaGhtbWVlU3ZiWVNuST0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiS0lIczBtdG55V0pWanJnWk51Ti9oRjMvc3cxVm5zZW9mbUdmaDA0cXR6UT0ifX0sInBhaXJpbmdFcGhlbWVyYWxLZXlQYWlyIjp7InByaXZhdGUiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJFRldHSDFMWktENmtRenlra3NvYktwcE9lVVZoNXcwd2RZNWJhbkdFQzBZPSJ9LCJwdWJsaWMiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiI3ck9vb203Uk40UDNpazl4SGFjWWVMSTFzK1VNQWM3NURLQ09ISnQ0UFhNPSJ9fSwic2lnbmVkSWRlbnRpdHlLZXkiOnsicHJpdmF0ZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IitJUE1aSHgwYXdIRVZURjdkMWY5MyttR0lMbTQzUGxnVVNxMkZ6Y1pZWGs9In0sInB1YmxpYyI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IlVZczhxQmo3YkdQVW8velRWTzZSdkFJeVJ0YWJJaUx2T2d6V0llQnlLWDA9In19LCJzaWduZWRQcmVLZXkiOnsia2V5UGFpciI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiU0Y4Znp6OTRUZThDNUVDSlFBRUQ3VXZnV1pBZWpBOXNqZ2VrNVFiMnlIRT0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiNmJFYlNOK1VXTDZZUFJlcFh5L2hxVUNKNFJBazAydlp6SmxqUFR6ZkwxUT0ifX0sInNpZ25hdHVyZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6Im5oTWdvQ0VyT0RxVkZieW96bmdOV1VOMHlZL1hEOUxiYnR4M0hrMW5PcVhId1loQ254c0V3S2VIZ0tuVW5DeTNHQjllTTNrZTRSVnl2S3JUZXd4Z2pnPT0ifSwia2V5SWQiOjF9LCJyZWdpc3RyYXRpb25JZCI6MTA2LCJhZHZTZWNyZXRLZXkiOiJuVmZOWk1HZE55N25rRHhkSmtyMi9pUVhoZGMzajZVTnZ3aThDbmlhOGR3PSIsInByb2Nlc3NlZEhpc3RvcnlNZXNzYWdlcyI6W3sia2V5Ijp7InJlbW90ZUppZCI6Ijk0Nzc4NDk5MzE1QHMud2hhdHNhcHAubmV0IiwiZnJvbU1lIjp0cnVlLCJpZCI6IjNBQTcwMEI4RTExRDNDRTVDQ0MzIiwicGFydGljaXBhbnQiOiIiLCJhZGRyZXNzaW5nTW9kZSI6InBuIn0sIm1lc3NhZ2VUaW1lc3RhbXAiOjE3ODg1Mjk3Mjh9LHsia2V5Ijp7InJlbW90ZUppZCI6Ijk0Nzc4NDk5MzE1QHMud2hhdHNhcHAubmV0IiwiZnJvbU1lIjp0cnVlLCJpZCI6IjNBRDREM0I2QzQ1MzgxMThBNEREIiwicGFydGljaXBhbnQiOiIiLCJhZGRyZXNzaW5nTW9kZSI6InBuIn0sIm1lc3NhZ2VUaW1lc3RhbXAiOjE3ODg1Mjk3MzF9LHsia2V5Ijp7InJlbW90ZUppZCI6Ijk0Nzc4NDk5MzE1QHMud2hhdHNhcHAubmV0IiwiZnJvbU1lIjp0cnVlLCJpZCI6IjNBNUM2Q0M5OTBFNzJFNzE0REU5IiwicGFydGljaXBhbnQiOiIiLCJhZGRyZXNzaW5nTW9kZSI6InBuIn0sIm1lc3NhZ2VUaW1lc3RhbXAiOjE3ODg1Mjk3MzN9LHsia2V5Ijp7InJlbW90ZUppZCI6Ijk0Nzc4NDk5MzE1QHMud2hhdHNhcHAubmV0IiwiZnJvbU1lIjp0cnVlLCJpZCI6IjNBMzZDNENBQUU4NEJGNDc5QTk3IiwicGFydGljaXBhbnQiOiIiLCJhZGRyZXNzaW5nTW9kZSI6InBuIn0sIm1lc3NhZ2VUaW1lc3RhbXAiOjE3ODg1Mjk3MzR9XSwibmV4dFByZUtleUlkIjo4MTMsImZpcnN0VW51cGxvYWRlZFByZUtleUlkIjo4MTMsImFjY291bnRTeW5jQ291bnRlciI6MSwiYWNjb3VudFNldHRpbmdzIjp7InVuYXJjaGl2ZUNoYXRzIjpmYWxzZX0sInJlZ2lzdGVyZWQiOnRydWUsInBhaXJpbmdDb2RlIjoiTktGOUNMVkgiLCJtZSI6eyJpZCI6Ijk0Nzc4NDk5MzE1OjQxQHMud2hhdHNhcHAubmV0IiwibGlkIjoiMjQ2Njg2MTc3ODI1MDA5OjQxQGxpZCIsIm5hbWUiOiJ+IH7wn5Cd8J+QmSAg77y64pOP4oKs4pOUz4zik6bvvLfhl68g8J+qvSDwn4y34pyM8J+Viu+4jyJ9LCJhY2NvdW50Ijp7ImRldGFpbHMiOiJDTEhScXRFUEVMU1k2OVFHR0FFZ0FDZ0EiLCJhY2NvdW50U2lnbmF0dXJlS2V5IjoiRlUzN3dkRXMzeXVMT3hYaHErMktqS01YSFRod2NDZnc1NUtzOXFNbGhBbz0iLCJhY2NvdW50U2lnbmF0dXJlIjoidVJtZ3k3cjlDVy9YUlI2bVkvQ2J4SEpQS0YrRU9xbVNnSVZyWURRV1RwWkZVUFlRQkpwdXZ4a3g5cDljWFhoeGp3SGxQOFVNWHNRY1ZBUUgvSlZ0REE9PSIsImRldmljZVNpZ25hdHVyZSI6Ink5OWluV2VpYzRHUHdwRW9Rc1RINlJPT0VOUHN4QUNML2U2KzFtUWREUXZOZnlzRGtuUmhWRll3aFhRbWlBL0FLd3J4MWtoeHg5YTFFUzY0eHFXV2dRPT0ifSwic2lnbmFsSWRlbnRpdGllcyI6W3siaWRlbnRpZmllciI6eyJuYW1lIjoiMjQ2Njg2MTc3ODI1MDA5OjQxQGxpZCIsImRldmljZUlkIjowfSwiaWRlbnRpZmllcktleSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IkJSVk4rOEhSTE44cml6c1Y0YXZ0aW95akZ4MDRjSEFuOE9lU3JQYWpKWVFLIn19XSwicGxhdGZvcm0iOiJpcGhvbmUiLCJyb3V0aW5nSW5mbyI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IkNBMElCUWdTIn0sImxhc3RBY2NvdW50U3luY1RpbWVzdGFtcCI6MTc4ODUyOTcyNSwibGFzdFByb3BIYXNoIjoiMWtSZ0tNIiwibXlBcHBTdGF0ZUtleUlkIjoiQUFBQUFJUlMifQ==
```

---

## Features

#### 🤖 Automation

- Auto Read Messages, Auto View Status, Auto Like Status
- Custom Auto Replies, Auto AI Chat (Groq/Llama), Auto Bio
- Auto Report (Daily group stats)

#### 🛡️ Group Protection & Moderation

- Anti-Link — blocks WhatsApp and external links
- Anti-Bad Word — deletes/warns/kicks for a bad-word list, extensible per group
- Anti-Group Status — deletes/warns/kicks non-admins who post a group status
- Anti-Bot — detects and removes known bot accounts
- Anti-Delete — retrieves deleted messages
- View-Once Media Recovery
- Anti-Status Mention, Anti-Foreign, Anti-Demote & Anti-Promote
- Welcome & Goodbye Messages (customizable images/text)
- Auto Warn & Auto Kick System

#### ⚙️ Useful Tools

- Sticker Maker (Image / Video / GIF), QR Code Generator
- Media Downloader (YouTube, TikTok, IG, FB, etc.)
- Profile & Group Info Commands, CDN Upload
- Language Switcher (17 languages)

#### 🎮 Fun Commands

- Random Memes, Quotes & Facts, Mini Games
- AI-Style Chat Commands, Media Editing (brat, trigger, wanted, wasted, etc.)

#### 🔧 System Controls

- Public / Private Mode Toggle, Bot Ping & Status Check
- Restart Bot Command, Menu & Help Commands
- Time-Based Greetings, Multi-Platform Update Support

---

## 🛡️ Safety Notice

> ⚠️ Using unofficial WhatsApp APIs may violate WhatsApp's Terms of Service. Toxic-MD is a self-hosted project. Use it responsibly.

**Best Practices:**

- Use a secondary WhatsApp number, not your primary one
- Enable Two-Step Verification on your account
- Avoid spamming commands or over-automating activity
- Use Private Mode to reduce visibility and risk

---

## 🔧 Troubleshooting

| Problem | Solution |
|---|---|
| Session expired | Re-pair your WhatsApp via the pairing link |
| Bot not responding | Check your server/hosting logs for errors |
| Ban warning received | Reduce automation frequency and switch to Private Mode |

---

## 📚 Disclaimer

> ⚠️ All features provided by Toxic-MD are strictly for **educational purposes only**.
> The developer is not responsible for any misuse, account bans, or violations of WhatsApp's policies that may result from using this bot.

---

<div align="center">

**Toxic-MD**

Simple • Powerful • Multi-Device WhatsApp Bot

*Built with ❤️ by xh_clinton*

</div>
