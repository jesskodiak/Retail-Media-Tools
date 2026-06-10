# Retail Media Tools

A modern, elegant platform for managing and organizing Retail Media apps and skills. Built by [@jesskodiak](https://github.com/jesskodiak).

🔗 **Live Site:** https://jesskodiak.github.io/Retail-Media-Tools/

## Features

✨ **What You Can Do:**
- 📱 **Create Apps** - Add external applications with URLs
- 🔧 **Build Skills** - Create custom skills with detailed instructions
- 🔍 **Search & Filter** - Quickly find tools by name
- 💾 **Auto-Save** - All tools persist in browser storage
- 🎨 **Modern UI** - Clean, dark-themed interface with green accent
- 👤 **Full Ownership** - You manage everything

## Quick Start

1. **Visit the site:** https://jesskodiak.github.io/Retail-Media-Tools/
2. **Click "Manage Page"** in the top right
3. **Add an App or Skill:**
   - Switch to **Apps** tab → Fill in name, description, URL → Click "Add App"
   - Switch to **Skills** tab → Fill in name, description, instructions → Click "Add Skill"
4. **View your tools** on the main grid
5. **Search** using the search box to filter tools

## Managing Tools

### Apps
External applications and platforms. Each app needs:
- **Name** - What is it called?
- **Description** - What does it do?
- **URL** - Where do users access it?

### Skills
Custom capabilities and utilities. Each skill needs:
- **Name** - What is it called?
- **Description** - What does it do?
- **Instructions** - How do users leverage it?

### Viewing All Tools
Click "All Tools" tab in the manager to see a list of everything you've created, with delete options.

## How It Works

- **Local Storage:** All tools are saved to your browser's local storage
- **No Backend:** Everything runs client-side - no server needed
- **GitHub Pages:** Hosted automatically via GitHub Pages
- **Fully Customizable:** Edit the HTML to change colors, fonts, or layout

## Customization

Edit `index.html` to customize:

```css
:root {
  --primary: #10b981;        /* Main accent color (green) */
  --black: #080808;           /* Background */
  --text: rgba(255,255,255,0.90);  /* Text color */
  /* ... more variables ... */
}
