# 🚀 How to Deploy Your Restaurant Picker Game for FREE

## Quick Deploy to GitHub Pages (Recommended)

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create a free account

### Step 2: Create Your Repository
1. Click the "+" icon in the top right → "New repository"
2. Name it `restaurant-picker`
3. Make it Public
4. Don't initialize with README (we already have files)
5. Click "Create repository"

### Step 3: Upload Your Files
1. On the repository page, click "uploading an existing file"
2. Drag and drop these files:
   - `restaurant-game.html` (rename to `index.html` before uploading)
   - `README.md`
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to Settings (in your repository)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click Save

### Step 5: Access Your Game!
- Your game will be live at: `https://[your-username].github.io/restaurant-picker/`
- It takes 2-5 minutes to go live
- Share this link with anyone!

## Alternative Free Hosting Options

### Option A: Netlify (Instant Deploy)
1. Go to [netlify.com](https://netlify.com)
2. Sign up for free
3. Drag your project folder to the Netlify dashboard
4. Done! You get a link like `amazing-einstein-123abc.netlify.app`

### Option B: Vercel
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import your GitHub repository
4. Auto-deploys when you update!

### Option C: Surge.sh (Command Line)
```bash
npm install -g surge
cd your-project-folder
surge
# Choose a domain like: restaurant-picker.surge.sh
```

## Making It Work Better

### For Online Multiplayer (Free Firebase Setup)

1. **Create Firebase Project**:
   - Go to [console.firebase.google.com](https://console.firebase.google.com)
   - Click "Create Project"
   - Name it "restaurant-picker"
   - Disable Google Analytics (not needed)

2. **Enable Realtime Database**:
   - Click "Realtime Database" in left menu
   - Click "Create Database"
   - Choose "Start in test mode"
   - Select your region

3. **Get Your Config**:
   - Click the gear icon → Project Settings
   - Scroll down and click "Add app" → Web
   - Copy the config code
   - Replace the Firebase config in `index.html`

4. **Update Security Rules** (for production):
   ```json
   {
     "rules": {
       "sessions": {
         "$sessionId": {
           ".read": true,
           ".write": true,
           ".validate": "newData.hasChildren(['host', 'players', 'status'])"
         }
       }
     }
   }
   ```

## Share Your Game!

Once deployed, you can:
- Share the link on social media
- Add it to your portfolio
- Show it to potential employers
- Let friends use it for their dinner decisions!

## Customization Ideas

Want to make it unique? Try:
- Change colors in the CSS
- Add more food categories
- Include dietary restrictions
- Add voting features
- Include price range filters

## Troubleshooting

**Game not showing up?**
- Wait 5-10 minutes after enabling GitHub Pages
- Check if index.html is in the root folder
- Make sure repository is public

**Maps not working?**
- The free version uses OpenStreetMap (no API needed)
- For Google Maps, you'll need an API key

**Online mode not syncing?**
- Make sure Firebase is configured
- Check browser console for errors
- Ensure all players use the same session code

## Cost: $0.00

Everything mentioned here is **completely free**:
- GitHub Pages hosting
- Firebase (free tier)
- OpenStreetMap
- Netlify/Vercel (free tiers)

## Need Help?

- Check the browser console (F12) for errors
- Make sure you're using a modern browser
- Try the local version first
- Create an issue on GitHub

---

**Pro Tip**: Once it's live, you can access it from any device - phone, tablet, computer - anywhere in the world! Perfect for deciding where to eat with friends, even when you're apart.