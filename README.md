# Coming Soon Page with Live Countdown Timer

A modern, responsive "Coming Soon" landing page featuring a live countdown timer, glassmorphism design, and interactive elements.

## 📁 Project Structure

```
coming-soon/
│
├── index.html          # Main HTML file
├── style.css           # All CSS styles and animations
├── script.js           # JavaScript functionality
├── images/             # Optional folder for images
```

## 🚀 How to Run in VS Code

### Method 1: Using Live Server Extension (Recommended)

1. **Install Live Server Extension:**
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "Live Server" by Ritwick Dey
   - Click Install

2. **Set up the project:**
   ```bash
   # Create project folder
   mkdir coming-soon
   cd coming-soon
   
   # Open in VS Code
   code .
   ```

3. **Create the files:**
   - Create `index.html` and paste the HTML code
   - Create `style.css` and paste the CSS code
   - Create `script.js` and paste the JavaScript code

4. **Run the project:**
   - Right-click on `index.html` in VS Code
   - Select "Open with Live Server"
   - Your browser will automatically open with the page
   - Changes will auto-refresh as you edit

### Method 2: Using Browser Directly

1. **Set up files as above**
2. **Open the file:**
   - Double-click `index.html` in file explorer, or
   - Right-click `index.html` in VS Code → "Open in Default Browser"

### Method 3: Using VS Code Live Preview Extension

1. **Install Live Preview Extension:**
   - Search for "Live Preview" by Microsoft in Extensions
   - Install it

2. **Run the project:**
   - Right-click `index.html`
   - Select "Show Preview"

## ⚙️ Customization

### Change Launch Date
In `script.js`, modify the launch date:
```javascript
// Set specific date and time
const launchDate = new Date('2025-12-31T23:59:59');

// Or set days from now
const launchDate = new Date();
launchDate.setDate(launchDate.getDate() + 30); // 30 days from now
```

### Update Content
- **Brand Name:** Change "NEXUS" in `index.html`
- **Description:** Update the description text
- **Colors:** Modify the gradient colors in `style.css`
- **Social Links:** Update href attributes in `index.html`

### Add Images
1. Create an `images/` folder
2. Add your images
3. Reference them in CSS or HTML:
   ```css
   background-image: url('images/your-image.jpg');
   ```

## 🛠️ Development Tips

### VS Code Extensions for Better Development:
- **Live Server** - Auto-refresh on changes
- **Prettier** - Code formatting
- **Auto Rename Tag** - HTML tag management
- **IntelliSense for CSS** - CSS autocomplete
- **JavaScript (ES6) snippets** - JS shortcuts

### Debugging in VS Code:
1. **Console Logs:** Open browser DevTools (F12) to see console.log outputs
2. **Breakpoints:** Use VS Code debugger with Live Server
3. **Source Maps:** Browser shows original files for debugging

### Testing Responsiveness:
1. **Browser DevTools:** F12 → Toggle device toolbar
2. **VS Code:** Install "Browser Preview" extension
3. **Multiple Browsers:** Test in Chrome, Firefox, Safari, Edge

## 📱 Features Included

- ✅ Responsive design (mobile-first)
- ✅ Live countdown timer
- ✅ Animated gradient background
- ✅ Floating particles animation
- ✅ Glassmorphism design
- ✅ Email notification form
- ✅ Social media links
- ✅ Keyboard navigation
- ✅ Mouse interaction effects
- ✅ SEO-friendly HTML structure

## 🔧 Troubleshooting

### Common Issues:

1. **Page doesn't load:**
   - Check if all files are in the same folder
   - Verify file names match exactly (case-sensitive)

2. **Styles not working:**
   - Ensure `style.css` is linked correctly in `index.html`
   - Check browser console for errors

3. **JavaScript not working:**
   - Verify `script.js` is linked at bottom of `index.html`
   - Check browser console for errors

4. **Live Server not working:**
   - Restart VS Code
   - Try right-clicking on `index.html` again
   - Check if port 5500 is available

### File Encoding:
- Save all files with UTF-8 encoding
- In VS Code: Bottom right corner should show "UTF-8"

## 📊 Browser Compatibility
- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ IE11 (limited support due to modern CSS features)

## 🚀 Deployment Options
- **GitHub Pages:** Push to GitHub, enable Pages
- **Netlify:** Drag and drop folder to Netlify
- **Vercel:** Connect GitHub repo to Vercel
- **Traditional Hosting:** Upload files via FTP

Happy coding! 🎉
