# Add a section on setting Dashboard_v1.0.html as the homepage in Edge and Chrome.
updated_readme = """# Dashboard_v1.0  
**Created by:** BLK3L53Y  
**Created on:** 2025-08-02  

---

## Overview

**Dashboard_v1.0** is a standalone HTML homepage for Windows users that lets you organize, customize, and launch your favorite links with ease.  
Works best in Microsoft Edge or Google Chrome.

- Drag-and-drop button and category ordering
- Categorized, color-coded buttons
- Built-in notes, usernames, and passwords for each link (stored locally)
- Customizable themes, title, and full backup/restore options
- All data saved in your browser—no cloud or external storage

---

## Updates

- MAIN: [https://github.com/BLK3L53Y/Dashboard_v1.0](https://github.com/BLK3L53Y/Dashboard_v1.0)

---

## Features

- ✅ Multiple link categories (collapsible sections)
- ✅ Drag-and-drop reordering (buttons & categories)
- ✅ Quick-access link buttons (open in new tab)
- ✅ Popup notes & local credentials for every button
- ✅ Dark/Light mode toggle + multiple color themes
- ✅ Custom site title (editable)
- ✅ Export/import all links, notes, and settings (JSON)
- ✅ Reset to factory defaults anytime
- ✅ Fast, portable, and works offline

---

## Controls

| Button/Control   | Description |
|:-----------------|:------------|
| **Home**         | View all your link categories and buttons |
| **Settings**     | Access all site options and customization |
| **Open File**    | Opens a file selection dialog (for future features/import) |
| **Open Directory** | Opens your main Windows directory (`C:\\`) in a new browser tab |
| **Theme Toggle** | Switch between dark and light mode |
| **Color Swatch** | Change accent color theme |
| **Update Site Name** | Set custom dashboard title |
| **Export Buttons** | Download a backup of all data (JSON) |
| **Import Buttons** | Restore dashboard from backup (JSON) |
| **Reset Dashboard** | Return to default categories/buttons |
| **Add Button**   | Add a new button to any category |
| **Edit Content** | Edit/delete all categories and buttons in a popup |

---

## Button Actions

| Home Page Button         | Function |
|:------------------------|:---------|
| **Main Button**         | Opens the assigned link in a new tab |
| **Plus (+) Button**     | Opens popup for notes, username, password for this button |
| **Drag-and-drop**       | Rearrange buttons within a category |
| **Category Header Drag**| Move categories up/down |

---

## Popup (Notes & Credentials)

- Each button's `+` opens a popup
    - **Notes**: Free text field for reminders or context
    - **Username/Password**: For local use (not encrypted)
    - **Copy Buttons**: Copy username or password to clipboard
- All popup data is saved to your browser's local storage (see Privacy)

---

## How To Use

1. **Download** and open `Dashboard_v1.0.html` in Edge or Chrome.
2. **Add buttons** in Settings:  
    - Enter button name, URL, assign or create a category, click **Add Button**.
3. **Rearrange** by dragging buttons or categories.
4. **Customize theme** and site title in Settings.
5. **Use notes popups** (`+` button) for storing extra info per button.
6. **Export** your setup to back up or move to another device/browser.
7. **Import** to restore a backup.
8. **Reset** if you want to start over from defaults.

---

## Setting Dashboard_v1.0 as Your Home Page

You can set `Dashboard_v1.0.html` as the homepage or startup page in your browser for instant access every time you open Edge or Chrome.

### Microsoft Edge

1. Open Edge.
2. Go to `Settings` > `Start, home, and new tabs`.
3. Under "When Edge starts," select **Open these pages**.
4. Click **Add a new page**.
5. Click **Browse** and select your `Dashboard_v1.0.html` file from your PC, or enter the full file path (e.g., `file:///C:/Users/YourName/Desktop/Dashboard_v1.0.html`).
6. (Optional) Also set as **Home button**:  
   - Go to `Appearance` > turn on **Show home button on the toolbar** > **Enter URL** > paste the file path above.

### Google Chrome

1. Open Chrome.
2. Go to `Settings` > `On startup`.
3. Select **Open a specific page or set of pages**.
4. Click **Add a new page**.
5. Enter the full file path to `Dashboard_v1.0.html` (e.g., `file:///C:/Users/YourName/Desktop/Dashboard_v1.0.html`).
6. (Optional) Set as **Home button**:  
   - Go to `Appearance` > turn on **Show Home button** > **Enter custom web address** > paste your file path.

**Tip:**  
- Always use three forward slashes for the file path: `file:///C:/...`
- If you move the HTML file, update the path in browser settings.

---

## File/Folder Features

| Control         | Description |
|:---------------|:------------|
| **Open File**  | Opens a file picker (used for import; does not alter site by itself) |
| **Open Directory** | Opens `C:\\` in a new browser tab (works on Windows/Edge/Chrome only) |

---

## Data & Storage

| Data Type     | Where Stored         | Encrypted? |
|:--------------|:---------------------|:-----------|
| Buttons, Categories, Theme, Title | Browser Local Storage | ❌ No |
| Notes, Username, Password (per button) | Browser Local Storage | ❌ No |

- **Export/Import** uses JSON files (portable, but not secure—protect your backup files!)

---

## Privacy & Disclaimer

- All data remains local to your browser and PC
- Passwords and notes are **not encrypted**
- Do not store critical or sensitive credentials
- Resetting, clearing browser data, or switching browsers/profiles will erase your setup unless exported

> **DISCLAIMER:** This dashboard is provided as-is for personal productivity. No warranty or guarantee of security or data recovery. Use at your own risk.

---

## Requirements

- Windows 10 or 11
- Microsoft Edge or Google Chrome (latest version recommended)
- No installation needed

---

## Troubleshooting

| Issue                             | Solution |
|:-----------------------------------|:---------|
| **Open Directory does nothing**    | Try Edge or Chrome; some browsers block `file:///` links |
| **Lost data after reset/clear**    | Restore from export, or set up again |
| **Cannot see buttons/categories**  | Make sure JavaScript is enabled |
| **"Open File" doesn't import**     | Use the "Import Buttons" button in Settings instead |

---

## License

Open-source for personal use.  
Free to modify, remix, or share—credit to [BLK3L53Y](https://github.com/BLK3L53Y).

---

# 🚀 Enjoy using Dashboard_v1.0!
"""

with open("/mnt/data/Dashboard_v1.0_README.md", "w", encoding="utf-8") as f:
    f.write(updated_readme)
