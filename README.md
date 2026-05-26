# steam-stvn-oled-ui
Ready to install on Steam Millennium: Dark OLED optimized theme: modern and minimalist.

## 📸 Preview

![Preview placeholder - Add theme screenshots here]

---

## ⚙️ Requirements

Before installing this theme, make sure you have:

- **Steam** — Latest version installed on your system
- **Steam Millennium** — [Download here](https://github.com/SteamClientHomebrew/Millennium)
- **Supported Platforms:**
  - Windows (10, 11, or newer)
  - Linux
  - macOS (experimental)

---

## 📥 Installation

### Quick Start (Easiest Method)

1. **Download the theme**
   - Click the green `<> Code` button → `Download ZIP`
   - Extract the folder

2. **Locate your Steam themes folder**
   - **Windows:** `C:\Program Files (x86)\Steam\steamui\skins`
   - **Linux:** `~/.steam/steam/steamui/skins`
   - **macOS:** `~/Library/Application Support/Steam/steamui/skins`

3. **Copy the theme folder**
   - Copy the extracted `steam-stvn-oled-ui` folder into your `skins` directory

4. **Activate in Steam**
   - Open Steam
   - Go to **Settings** → **Interface** → **Theme**
   - Select `steam-stvn-oled-ui` from the dropdown
   - Restart Steam

✅ **Done!** Your theme is now active.

---

## 🎨 Customization

### Changing Accent Colors

The theme uses **CSS variables** to allow easy color customization without modifying the CSS files.

**Primary Color (Blue - Buttons & Highlights)**
- Edit `skin.json`
- Find: `"primaryColor": "#0066FF"`
- Change to your preferred hex color

**Secondary Color (Red - Warnings & Alt States)**
- Edit `skin.json`
- Find: `"secondaryColor": "#FF3333"`
- Change to your preferred hex color

**Example:**
```json
{
  "primaryColor": "#1E90FF",
  "secondaryColor": "#FF6B6B"
}
```

Restart Steam to see the changes.

---

## 📝 Credits

**Author:** Rafael Stevanato  
**Theme:** steam-stvn-oled-ui  
**Version:** 1.0.0  
**Based on:** [Steam Millennium](https://github.com/SteamClientHomebrew/Millennium)

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use the theme personally
- ✅ Modify it for your own use
- ✅ Share and distribute
- ✅ Use it commercially

Just keep the license and attribution intact.

---

## 🔗 Resources

- **Millennium Documentation:** https://docs.steambrew.app/
- **Millennium Repository:** https://github.com/SteamClientHomebrew/Millennium
- **Theme Template:** https://github.com/SteamClientHomebrew/ThemeTemplate
- **Keep a Changelog Official Template:** https://keepachangelog.com/en/1.1.0/

---

## 💬 Support & Contributions

Found a bug? Have suggestions?

- **Report issues** on the [Issues](../../issues) tab
- **Fork and contribute** — Pull requests are welcome!

---

**Last Updated:** May 2026  
**Status:** Active Development