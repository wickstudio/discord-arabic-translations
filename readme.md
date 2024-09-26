# Arabic Plugin for Discord - BetterDiscord

![Arabic Plugin](https://img.shields.io/github/v/release/wickstudio/discord-arabic-translations?style=flat-square)
![Stars](https://img.shields.io/github/stars/wickstudio/discord-arabic-translations?style=flat-square)
![License](https://img.shields.io/github/license/wickstudio/discord-arabic-translations?style=flat-square)

### 🌟 Fully Arabic Translations for Discord UI
This **BetterDiscord plugin** dynamically fetches Arabic translations for the entire Discord interface, making it more accessible for Arabic speakers. All translations are hosted in easily manageable JSON files on this repository, allowing for rapid updates without modifying the core plugin.

---

## 🚀 Features

- **Full Arabic Translation:** All core Discord elements translated to Arabic including navigation, settings, messages, and more.
- **Dynamic Fetching:** Translations are dynamically fetched from the GitHub repository, ensuring the latest updates are always applied.
- **Modular Structure:** Translations are organized into 61 JSON files, categorized by Discord UI sections for easy maintenance and updates.
- **Efficient DOM Translation:** The plugin efficiently translates text, placeholders, and other attributes in real-time, adapting to dynamic changes in Discord's interface.

---

## 📂 JSON Structure

All translations are split into **61 JSON files** corresponding to different sections of Discord, making it easy to manage and update.

Here are the categories of JSON files:

```plaintext
- general_navigation.json
- user_settings.json
- server_settings.json
- server_management.json
- channels.json
- messages.json
- reactions.json
- direct_messages.json
- friends_list.json
- notifications.json
- voice_and_video.json
- user_profile.json
- presence_and_status.json
- audit_logs.json
- roles_and_permissions.json
- integrations.json
- server_boost.json
- member_list.json
- moderation.json
- invites.json
- pinned_messages.json
- search.json
- mentions.json
- typing_indicators.json
- modals.json
- popups_and_tooltips.json
- loading_and_error_messages.json
- settings_modals.json
- friend_requests.json
- guild_discovery.json
- invite_splash_pages.json
- file_sharing.json
- embeds.json
- markdown_and_formatting.json
- threads.json
- emojis_and_stickers.json
- custom_emojis.json
- voice_channels.json
- video_calls.json
- server_widgets.json
- server_moderation.json
- threads_and_forums.json
- stage_channels.json
- message_settings.json
- mention_settings.json
- pinned_message_settings.json
- reaction_management.json
- invites_and_permissions.json
- advanced_settings.json
- themes_and_customization.json
- keyboard_shortcuts.json
- help_and_support.json
- privacy_and_security.json
- connections.json
- billing.json
- reports.json
- boost_settings.json
- developer_portal.json
- game_activity.json
- status_notifications.json
- system_notifications.json
```

Each of these JSON files contains key-value pairs representing English terms and their Arabic translations, making it easy to update specific sections without affecting others.

---

## 🛠️ Installation Instructions

### Prerequisites
- **BetterDiscord** must be installed. You can download it from [BetterDiscord's Official Website](https://betterdiscord.app).

### Step-by-Step Installation:
1. **Download the Plugin:**
   - Download the `ArabicPlugin.plugin.js` from this repository: [Download Plugin](https://github.com/wickstudio/discord-arabic-translations/raw/main/ArabicPlugin.plugin.js).
   
2. **Move the Plugin to BetterDiscord's Plugins Folder:**
   - Copy the downloaded `ArabicPlugin.plugin.js` file and paste it into the following directory:
     - **Windows:** `%AppData%\BetterDiscord\plugins`
     - **macOS/Linux:** `~/Library/Application Support/BetterDiscord/plugins`

3. **Enable the Plugin in Discord:**
   - Open Discord and go to **User Settings > Plugins**.
   - Enable the **Arabic Plugin**.

4. **Enjoy a Fully Arabic Discord UI!**

---

## 🔄 Updating Translations

Since the plugin fetches translations dynamically from this repository, there’s no need to manually update the plugin. Simply update the respective JSON file in this repo, and Discord will automatically apply the new translations when the plugin is running.

To update translations:
1. Navigate to the corresponding JSON file (e.g., `general_navigation.json`).
2. Update the translations directly or submit a **Pull Request** to contribute improvements.
3. The plugin will automatically fetch the new translations.

---

## 📜 Contributing

We welcome contributions to improve or add new translations to this project! Here's how you can contribute:

1. Fork this repository.
2. Create a new branch for your feature/translation (`git checkout -b feature/new-translation`).
3. Make your translation changes in the respective JSON files.
4. Push your changes to your branch (`git push origin feature/new-translation`).
5. Open a Pull Request, and we’ll review and merge your contributions.

Feel free to submit issues or suggestions for features or improvements.

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 💬 Support

If you encounter any issues, or need help setting up the plugin, feel free to join our **Discord Support Server**: [Wick Studio Discord](https://discord.gg/wicks).

---

## 📊 Metrics

![GitHub Repo Stars](https://img.shields.io/github/stars/wickstudio/discord-arabic-translations?style=flat-square)
![GitHub Forks](https://img.shields.io/github/forks/wickstudio/discord-arabic-translations?style=flat-square)
![GitHub Issues](https://img.shields.io/github/issues/wickstudio/discord-arabic-translations?style=flat-square)
![Contributors](https://img.shields.io/github/contributors/wickstudio/discord-arabic-translations?style=flat-square)
![GitHub Last Commit](https://img.shields.io/github/last-commit/wickstudio/discord-arabic-translations?style=flat-square)

---

## 💡 Future Enhancements

- **Additional Language Support:** While this plugin currently focuses on Arabic, we plan to extend support to other languages.
- **Translation Accuracy Improvements:** Community contributions will ensure more accurate translations as Discord evolves.
- **Customization Options:** Users will be able to enable or disable specific sections for translation.

---

## 🙌 Acknowledgements

Special thanks to the **BetterDiscord** team for their incredible work on enhancing Discord, and to all contributors who help improve this plugin over time.

---

Made with ❤️ by **[Wick](https://github.com/wickstudio)**