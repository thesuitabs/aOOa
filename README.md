# Ancient Order of Absurdity (aOOa) Website

Welcome to the official website repository for the Ancient Order of Absurdity meme token project.

## 🎭 About This Website

This is a fully responsive, accessible, and dynamic website built for the aOOa community. It features:

- **Responsive Design**: Works perfectly on mobile, tablet, and desktop
- **Interactive Elements**: Flippable character cards, smooth animations, and engaging user interactions
- **Accessibility**: Built with screen readers and keyboard navigation in mind
- **Easy Updates**: Designed for non-technical users to make changes via GitHub

## 📁 File Structure

```
aOOa-website/
├── index.html          # Main website file
├── content.json        # All text content (EDIT THIS TO UPDATE TEXT)
├── css/
│   └── styles.css      # All styling (advanced users only)
├── js/
│   └── scripts.js      # Interactive features (advanced users only)
├── images/
│   ├── aOOaLogo.png           # Main logo
│   ├── aOOaMastcot.png        # Mascot image
│   ├── sui-logo.png           # SUI blockchain logo
│   ├── character-01.png       # Character images
│   ├── character-02.png       # (character-01 through character-14)
│   └── ...
└── README.md           # This file
```

## ✏️ How to Update Content (Non-Technical Users)

### Method 1: Update Text Content

1. **Open `content.json`** in any text editor
2. **Find the section you want to change** (e.g., "mission_statement", "tokenomics_section")
3. **Edit the text between the quotes**
4. **Save the file**
5. **Upload to GitHub** (replace the old file)

**Example**: To change the main tagline:
```json
"hero_section": {
    "tagline": "Your new tagline goes here"
}
```

### Method 2: Update Images

1. **Prepare your new image** (PNG or JPG format recommended)
2. **Name it appropriately** (e.g., `new-character.png`)
3. **Upload to the `images/` folder** on GitHub
4. **Update the HTML file** to reference the new image name

### Method 3: Add New Character

1. **Add your character image** to the `images/` folder (name it `character-15.png`, etc.)
2. **Update `content.json`** in the "characters_section" to add the new character info
3. **Update `index.html`** to add the new character card (copy an existing one and modify)

## 🔧 Quick Updates Guide

### Change Links
Edit the `links_section` in `content.json`:
```json
"links": [
    {
        "name": "Twitter/X",
        "url": "https://your-new-twitter-url",
        "description": "Your description"
    }
]
```

### Update Launch Status
In `content.json`, find `how_to_buy` section:
```json
"launch_status": "live",  // Change from "pre-launch" to "live"
"pre_launch_message": "We're now live!"
```

### Add New Ticker Phrases
In `content.json`, add to the `ticker_phrases` array:
```json
"ticker_phrases": [
    "Your new phrase here",
    "Another absurd statement"
]
```

### Update Meme of the Month
1. **Upload your meme image** to the `images/` folder
2. **Update `content.json`**:
```json
"meme_showcase": {
    "current_image": "your-meme-filename.jpg",
    "placeholder_text": "Winner: [Creator Name] - [Meme Title]"
}
```

## 🚀 Deployment Instructions

### Option 1: GitHub + Netlify (Recommended)
1. **Upload all files** to your GitHub repository
2. **Connect Netlify** to your GitHub repo
3. **Deploy automatically** - Netlify will build and host your site
4. **Get your live URL** (e.g., `yoursite.netlify.app`)

### Option 2: GitHub + Vercel
1. **Upload all files** to your GitHub repository
2. **Connect Vercel** to your GitHub repo
3. **Deploy automatically** - Vercel will build and host your site
4. **Get your live URL** and IPFS CID

### Option 3: Direct Upload to IPFS
1. **Zip all website files** (except README.md)
2. **Upload to Pinata** or another IPFS service
3. **Get the CID** for your SUI domain

## 🎨 Customization Tips

### Colors
The website uses CSS custom properties (variables) for easy color changes. Edit `css/styles.css`:
```css
:root {
    --primary-color: #6366f1;    /* Main brand color */
    --secondary-color: #ec4899;  /* Accent color */
    /* Change these to match your brand */
}
```

### Fonts
To change fonts, update the Google Fonts link in `index.html` and the CSS variable:
```css
--font-family: 'Your-New-Font', sans-serif;
```

## 📱 Mobile Responsiveness

The website is fully responsive and includes:
- **Mobile-first design**
- **Touch-friendly interactions**
- **Optimized images**
- **Fast loading times**

## ♿ Accessibility Features

- **Screen reader compatible**
- **Keyboard navigation support**
- **High contrast mode support**
- **Reduced motion support**
- **Semantic HTML structure**

## 🐛 Troubleshooting

### Images Not Loading
- Check file names match exactly (case-sensitive)
- Ensure images are in the `images/` folder
- Use PNG or JPG formats

### Text Not Updating
- Check JSON syntax in `content.json` (use a JSON validator)
- Ensure quotes are properly closed
- Clear browser cache

### Mobile Menu Not Working
- Check that `scripts.js` is loading properly
- Ensure JavaScript is enabled in browser

## 🎭 Easter Eggs

The website includes several fun easter eggs:
- **Konami Code**: Try the classic cheat code sequence
- **Mascot Interactions**: Click on mascot images
- **Console Messages**: Check the browser developer console

## 📞 Support

If you need help with updates:
1. **Check this README** first
2. **Validate your JSON** at jsonlint.com
3. **Test locally** before uploading
4. **Ask the community** in Telegram

## 🔄 Version History

- **v1.0**: Initial website launch
- **v1.1**: Added character interactions
- **v1.2**: Enhanced mobile experience

---

**Remember**: This website represents the Ancient Order of Absurdity. Keep it absurd, keep it fun, but keep it professional. The Order approves of controlled chaos.

*Life is absurd. Websites are absurd. This README is absurd. But it works.*

