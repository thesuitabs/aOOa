# 🚀 Quick Update Guide for aOOa Website

*For non-technical users who just want to make simple changes*

## 📝 Changing Text Content

**What you need**: Any text editor (Notepad, TextEdit, etc.)

1. **Open the file called `content.json`**
2. **Find the text you want to change** (it's between quotes like "this")
3. **Change the text** (keep the quotes!)
4. **Save the file**
5. **Upload to GitHub** (drag and drop to replace the old file)

### Common Changes:

**Change the main tagline:**
Look for: `"tagline": "Life is absurd. Money is absurd..."`
Change to: `"tagline": "Your new tagline here"`

**Update Twitter/X link:**
Look for: `"url": "https://x.com/ancientorderO"`
Change to: `"url": "https://x.com/yournewhandle"`

**Update Telegram link:**
Look for: `"url": "https://t.me/ancientabsurdity"`
Change to: `"url": "https://t.me/yournewgroup"`

## 🖼️ Changing Images

**What you need**: Your new image file (PNG or JPG)

1. **Rename your image** to match what you're replacing:
   - Logo: `aOOaLogo.png`
   - Mascot: `aOOaMastcot.png`
   - Characters: `character-01.png`, `character-02.png`, etc.

2. **Upload to the `images` folder** on GitHub
3. **Replace the old file** when prompted

## 🎯 Quick Fixes

### ✅ Launch Status (Pre-launch → Live)
In `content.json`, find:
```
"launch_status": "pre-launch"
```
Change to:
```
"launch_status": "live"
```

### ✅ Add New Ticker Message
In `content.json`, find the `ticker_phrases` section and add:
```
"Your new message here • Another message"
```

### ✅ Update Meme of the Month
1. Upload your meme image to `images` folder
2. In `content.json`, find `meme_showcase` and change:
   ```
   "current_image": "your-meme-name.jpg"
   ```

## ⚠️ Important Rules

1. **Always keep the quotes** around text
2. **Don't delete commas** at the end of lines
3. **Test your JSON** at jsonlint.com before uploading
4. **Make a backup** before making changes
5. **One change at a time** until you're comfortable

## 🆘 If Something Breaks

1. **Don't panic** - you can always revert to the previous version
2. **Check for missing quotes** or commas
3. **Use jsonlint.com** to check your content.json file
4. **Ask for help** in the Telegram group

## 📱 Testing Your Changes

After uploading:
1. **Wait 2-3 minutes** for changes to appear
2. **Refresh your browser** (Ctrl+F5 or Cmd+Shift+R)
3. **Check on mobile** too
4. **Test all links** to make sure they work

---

**Remember**: Small changes, test often, and keep it absurd! 🎭

*The Order believes in you. You've got this.*

