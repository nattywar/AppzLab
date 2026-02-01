# Apps Folder

Welcome! This is where you place your HTML files to make them accessible through AppzLab.

## 🎯 Quick Start

1. **Copy** any HTML file into this folder
2. **Refresh** the main `index.html` page
3. **Your app appears** in the launcher!

## 📝 Example Apps Included

- **example-app.html** - A template showing how to create your own apps

## 🔧 Tips for Creating Apps

### Self-Contained HTML Files Work Best
The ideal app for AppzLab is a single HTML file that includes all its CSS and JavaScript. For example:

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        /* Your CSS here */
    </style>
</head>
<body>
    <h1>My App</h1>
    <script>
        // Your JavaScript here
    </script>
</body>
</html>
```

### Using External Resources
You can still use external resources (CDNs, APIs, etc.), but remember:
- They require an internet connection
- The app won't be fully offline-capable

### Organizing Multiple Files
If your app needs multiple files:
1. Create a subfolder (e.g., `apps/my-project/`)
2. Place all files there
3. The main HTML file will be detected

## 🎨 Customization Ideas

Here are some ideas for apps you could create:

- **Personal Dashboard** - Links, notes, to-do lists
- **Calculators** - Custom calculators for specific needs
- **Forms** - Data entry forms (data saved to localStorage)
- **Games** - Simple browser games
- **Tools** - Text processors, converters, generators
- **Dashboards** - Data visualization tools

## 💡 Advanced Tips

### Save Data Locally
Use `localStorage` to save data:
```javascript
// Save
localStorage.setItem('myData', 'value');

// Load
const data = localStorage.getItem('myData');
```

### Make it Installable
Add these meta tags to your app:
```html
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
```

### Link Back to Launcher
Add a back button to your app:
```html
<a href="../index.html">← Back to AppzLab</a>
```

## 🆘 Need Help?

- Check out `example-app.html` for a working template
- Read the main `README.md` for more documentation
- Look at the existing FDNY apps for complex examples

---

Happy coding! 🚀
