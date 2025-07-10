<p align="center">
  <img src="https://envs.sh/232.jpg" alt="RMC-POST-SEARCH-BOT Logo" width="280"/>
</p>

<h1 align="center">RMC POST SEARCH BOT</h1>

<p align="center">
🔍 A blazing-fast Telegram bot to search posts from connected channels & groups — without any login or session risk!  
</p>

---

## ✨ Features

- 🔎 **Superfast Message Search** from connected channels  
- 🤖 **No Login or Session Required** (safe to deploy)
- 🧩 **Inline Mode**, Pagination, Retry System  
- 🔐 **Force-Subscribe + Resume Search**  
- 👤 **Admin Commands**: /userc, /groupc, /broadcast  
- 💬 **Search Works in Groups & PM Both**

---

## 🚀 Getting Started

### 🛠️ Deploy via Render

1. Click this button to deploy:

   [![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com)

2. Add the following **environment variables** in Render dashboard:

| Key             | Description                            |
|------------------|----------------------------------------|
| `API_ID`         | Your Telegram API ID                   |
| `API_HASH`       | Your Telegram API HASH                 |
| `BOT_TOKEN`      | Token from [@BotFather](https://t.me/BotFather)  
| `LOG_CHANNEL`    | Channel ID where bot logs actions      |
| `DATABASE_URI`   | MongoDB Atlas URI                      |
| `ADMIN`          | Your Telegram User ID                  |

---

## 📁 Project Structure


---

## 🤖 Bot Commands

| Command        | Description                       |
|----------------|-----------------------------------|
| `/start`       | Start bot in PM                   |
| `/verify`      | Verify group (admin only)         |
| `/connect`     | Connect channel to group          |
| `/fsub`        | Enable force-subscription         |
| `/userc`       | Count users                       |
| `/groupc`      | Count groups                      |
| `/broadcast`   | Send message to all users         |
| `/mode`        | Switch between inline/text mode   |

---

## 💎 Credits

- Developed with ❤️ by [RMCBACKUP](https://t.me/RMCBACKUP)  
- Powered by [Pyrogram](https://docs.pyrogram.org), [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

---

## 🔗 Support

Need help? Join [@RMCBACKUP](https://t.me/RMCBACKUP)
