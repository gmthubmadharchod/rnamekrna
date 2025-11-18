# Auto Rename Bot ✨

<p align="center">
  <img src="https://i.imgur.com/8V1T91D.jpg" alt="Bot Channels" width="700"/>
</p>

A powerful and dynamic Telegram bot designed to automatically rename files, with a fully interactive, button-based UI that can be configured dynamically by the owner.

---

## 🚀 Features

-   **✍️ Auto Rename:** Automatically rename files based on a user-defined format.
-   **🖼️ Custom Thumbnail & Caption:** Set your own custom thumbnails and captions for renamed files.
-   **🎞️ Metadata Support:** View and manage metadata for your files.
-   **SEQUENCE MODE:** Send multiple files and have them renamed and sent back in a perfect sequence.
-   **FORCE SUBSCRIBE:** Ensure users join designated channels before they can use the bot.
-   **⚙️ In-Bot Configuration:** The bot owner can manage all important settings directly from the bot's UI.
-   **🔐 Secure:** No hardcoded credentials. All sensitive information is loaded from environment variables.
-   **🏆 Leaderboard:** Track user activity and see who has renamed the most files.

---

## 🤖 Bot Commands

The bot is primarily controlled through a user-friendly button interface. Here are the initial commands to get started:

### User Commands
-   `/start` - sᴛᴀʀᴛ ᴛʜᴇ ʙᴏᴛ
-   `/autorename` - ᴛᴏ sᴇᴛ ᴀ ᴀᴜᴛᴏ ʀᴇɴᴀᴍᴇ ғᴏʀᴍᴀᴛ
-   `/showformat` - Tᴏ sᴇᴇ ʏᴏᴜʀ ғᴏʀᴍᴀᴛ
-   `/tutorial` - sᴇᴇ ᴜsᴀɢᴇ ɢᴜɪᴅᴇ
-   `/leaderboard` - Tᴏ ᴠɪᴇᴡ ʟᴇᴀᴅᴇʀʙᴏᴀʀᴅ
-   `/viewthumb` - ᴠɪᴇᴡ ᴛʜᴜᴍʙɴᴀɪʟ
-   `/delthumb` - ᴅᴇʟᴇᴛᴇ ᴛʜᴜᴍʙɴᴀɪʟ
-   `/set_caption` - sᴇᴛ ʏᴏᴜʀ ᴏᴡɴ ᴄᴀᴘᴛɪᴏɴ
-   `/see_caption` - ᴠɪᴇᴡ ʏᴏᴜʀ ᴄᴀᴘᴛɪᴏɴ
-   `/del_caption` - ᴅᴇʟᴇᴛᴇ ʏᴏᴜʀ ᴄᴀᴘᴛɪᴏɴ
-   `/setmedia` - sᴇᴛ ᴏᴜᴛᴘᴜᴛ ғɪʟᴇ ᴛʏᴘᴇ
-   `/start_sequence` - sᴛᴀʀᴛ ғɪʟᴇ sᴇǫᴜᴇɴᴄɪɴɢ
-   `/end_sequence` - ᴇɴᴅ ғɪʟᴇ sᴇǫᴜᴇɴᴄɪɴɢ
-   `/metadata` - ᴠɪᴇᴡ ʏᴏᴜʀ ᴍᴇᴛᴀᴅᴀᴛᴀ
-   `/verify` - Tᴏ ᴠᴇʀɪғʏ

### Admin Commands
-   `/add_premium` - Tᴏ ᴀᴅᴅ ᴘʀᴇᴍɪᴜᴍ ᴜsᴇʀs
-   `/remove_premium` - Tᴏ Rᴇᴍᴏᴠᴇ ᴘʀᴇᴍɪᴜᴍ ᴜsᴇʀs
-   `/premium_users` - Tᴏ ᴠɪᴇᴡ ᴀʟʟ ᴘʀᴇᴍɪᴜᴍ ᴜsᴇʀs
-   `/premium_info` - Tᴏ ᴠɪᴇᴡ ᴘᴇʀsᴏɴᴀʟʟʏ ᴏɴᴇ ᴘʀᴇᴍɪᴜᴍ ᴜsᴇʀ
-   `/verify_settings` - Tᴏ ᴄʜᴀɴɢᴇ ᴠᴇʀɪғʏ sᴇᴛᴛɪɴɢs
-   `/fsub_mode` - Tᴏ sᴇᴇ ᴛʜᴇ ғᴏʀᴄᴇ sᴜʙ ᴍᴏᴅᴇ
-   `/addchnl` - ᴀᴅᴅ ᴀ ᴄʜᴀɴɴᴇʟ ғᴏʀ ғᴏʀᴄᴇ sᴜʙsᴄʀɪᴘᴛɪᴏɴ
-   `/delchnl` - ʀᴇᴍᴏᴠᴇ ᴀ ғᴏʀᴄᴇ sᴜʙsᴄʀɪʙᴇ ᴄʜᴀɴɴᴇʟ
-   `/listchnl` - ᴠɪᴇᴡ ᴀʟʟ ᴀᴅᴅᴇᴅ ғᴏʀᴄᴇ sᴜʙsᴄʀɪʙᴇ ᴄʜᴀɴɴᴇʟs
-   `/add_admin` - ᴀᴅᴅ ᴀ ɴᴇᴡ ᴀᴅᴍɪɴ
-   `/deladmin` - ʀᴇᴍᴏᴠᴇ ᴀɴ ᴀᴅᴍɪɴ
-   `/admins` - ʟɪsᴛ ᴀʟʟ ᴄᴜʀʀᴇɴᴛ ᴀᴅᴍɪɴs
-   `/restart` - ʀᴇsᴛᴀʀᴛ ᴛʜᴇ ʙᴏᴛ
-   `/broadcast` - ʙʀᴏᴀᴅᴄᴀsᴛ ᴀ ᴍᴇssᴀɢᴇ
-   `/status` - Tᴏ ᴄʜᴇᴄ𝑘 ʙᴏᴛ sᴛᴀᴛᴜs
-   `/ban` - ʙᴀɴ ᴀ ᴜsᴇʀ
-   `/unban` - ᴜɴʙᴀɴ ᴀ ᴜsᴇʀ
-   `/banned` - sʜᴏᴡ ʙᴀɴɴᴇᴅ ᴜsᴇʀs

---

## 🛠️ How to Deploy

You can easily deploy this bot yourself. Follow the steps below.

### **Prerequisites**

-   A Telegram Bot Token. Get one from [@BotFather](https://t.me/BotFather).
-   Your Telegram API ID and API Hash. Get them from [my.telegram.org](https://my.telegram.org).
-   A MongoDB database URL. Get one for free from [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

### **Deployment Steps**

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Set up Environment Variables:**
    Create a `.env` file in the root directory or set the following environment variables in your deployment environment:

    | Variable      | Description                                |
    |---------------|--------------------------------------------|
    | `API_ID`      | Your Telegram App ID.                      |
    | `API_HASH`    | Your Telegram App Hash.                    |
    | `BOT_TOKEN`   | Your Telegram bot token from @BotFather.   |
    | `DB_URL`      | Your MongoDB connection URL.               |
    | `OWNER_ID`    | Your numerical Telegram User ID.           |
    | `LOG_CHANNEL` | The ID of the channel where the bot will send logs/notifications. |

4.  **Run the bot:**
    ```bash
    python3 bot.py
    ```

---

## 🙏 Credits & Acknowledgements

This bot was made possible with the help and support of the following individuals and projects:

-   **Base Repository:** A special thanks to **[Jishu Developer](https://github.com/JishuDeveloper)** for their foundational work.
-   **[ABHINAI](https://t.me/about_zani)**
-   **[ABHINAV](https://t.me/adityaabhinav)**
-   **[MASTER](https://t.me/V_Sbotmaker)**

A special thanks to the **[REx BOTs](https://t.me/RexBots_Official)** channel for their inspiration and support!
