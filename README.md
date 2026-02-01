# AppzLab - Local HTML App Hosting

Welcome to AppzLab! This repository provides a simple way to host and access HTML applications locally on your computer without needing a web server.

## 🚀 Quick Start

### Option 1: Direct File Access
1. **Download or clone this repository** to your computer
2. **Open `index.html`** in your web browser (just double-click it)
3. You'll see a launcher page with all available apps
4. Click on any app to open it

### Option 2: Add to Home Screen (Mobile/Desktop)
1. Open `index.html` in your browser
2. **On Mobile:** Tap the share button and select "Add to Home Screen"
3. **On Desktop (Chrome/Edge):** Click the install icon in the address bar, or go to Menu → Install AppzLab
4. The app will now be accessible from your home screen/desktop like a native app!

## 📁 Folder Structure

```
AppzLab/
├── index.html          # Main launcher page (open this file)
├── apps/               # Place your HTML files here
│   ├── example-app.html    # Example app template
│   └── [your-app.html]     # Your custom HTML files
├── FDNY-EMS-Staffing/  # FDNY EMS Staffing System
└── README.md           # This file
```

## ➕ Adding Your Own Apps

### Method 1: Simple Copy & Paste
1. Copy your HTML file into the `apps/` folder
2. Refresh the `index.html` page in your browser
3. Your app should appear in the list automatically!

### Method 2: Manual Registration (for better control)
If you want custom names or icons:
1. Place your HTML file in the `apps/` folder
2. The launcher will automatically detect and display it

## 🎨 Features

- **No Server Required:** All apps run directly from your file system
- **Offline Ready:** Works without internet (except for apps that need external resources)
- **Mobile Friendly:** Installable as a PWA on mobile devices
- **Easy Organization:** Simple folder structure for managing multiple apps
- **Automatic Discovery:** New apps are automatically detected

## 📱 Installing as a Progressive Web App (PWA)

The launcher page can be installed as a Progressive Web App:

1. Open `index.html` in Chrome, Edge, or Safari
2. Look for the install prompt or:
   - **Desktop:** Click the ⊕ icon in the address bar
   - **Mobile:** Tap Share → Add to Home Screen
3. Once installed, you can access all your apps from your home screen/desktop

## 🔧 Technical Details

- All apps are self-contained HTML files
- No build process required
- Works on any operating system with a web browser
- Compatible with modern browsers (Chrome, Firefox, Safari, Edge)

## 📝 Examples Included

- **FDNY EMS Staffing System:** Full-featured staffing management system
- **Example App:** Template for creating your own apps

## 🆘 Troubleshooting

**Q: My app doesn't appear in the launcher**
- Make sure your HTML file is in the `apps/` folder
- Refresh the browser page
- Check that the file has a `.html` extension

**Q: Can I organize apps into subfolders?**
- Yes! The launcher will scan subfolders too

**Q: Do my apps need internet?**
- Only if they use external resources (APIs, CDNs, etc.)
- Apps using only local resources work 100% offline

**Q: Can I customize the launcher page?**
- Yes! Edit `index.html` to customize colors, layout, etc.

## 📄 License

Free to use for personal and commercial projects.

## 🤝 Contributing

Feel free to add your own apps or improve the launcher page!

---

**For the Bravest. By the Bravest. 🚨**
