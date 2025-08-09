# Restaurant Picker Game

A modern, beautifully designed 5-2-1 decision-making game to solve the eternal "Where should we eat?" dilemma!

## 🎯 How It Works

The **5-2-1 Method**:
1. **Player 1** picks 5 restaurants they'd like
2. **Player 2** eliminates 2 restaurants they don't want  
3. **Player 3** (or Player 1) makes the final choice!

## ✨ Features

- **Local Play**: Pass the device between players
- **Online Play**: Play remotely using session codes
- **Map Integration**: Find restaurants using OpenStreetMap
- **Quick Categories**: Pizza, Burger, Sushi, Mexican, and more
- **Random Selection**: Let fate decide!
- **No API Key Required**: Works out of the box

## 🚀 Quick Start

### Option 1: GitHub Pages Hosting

1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from branch" → main → root
4. Your game will be live at `https://yourusername.github.io/fivethreeone/`

### Option 2: Run Locally
```bash
# Clone the repo
git clone https://github.com/yourusername/fivethreeone.git

# Open in browser
open index.html
```

## 🎲 Game Modes

### Local Mode
- Perfect for groups dining together
- Pass the device between players
- No internet required for basic functionality

### Online Mode (Beta)
- Create a session and share the 6-digit code
- Each player uses their own device
- Real-time synchronization
- Currently uses localStorage (Firebase integration coming soon)

## 🗺️ Restaurant Finding Options

1. **Map Search**: Search for restaurants on an interactive map
2. **Nearby**: Find restaurants near your location
3. **Categories**: Quick picks like Pizza, Sushi, Mexican
4. **Manual Entry**: Type in restaurant names directly

## 🛠️ Technology Stack

- **Frontend**: Pure HTML, CSS, JavaScript
- **Maps**: OpenStreetMap with Leaflet.js
- **Hosting**: GitHub Pages (free!)
- **Session Storage**: localStorage (upgrading to Firebase)

## 📱 Mobile Friendly

The game is fully responsive and works great on:
- Desktop computers
- Tablets
- Smartphones

## 🔧 Customization

Want to customize the game? Edit the main file:

- `index.html` - Main game file with embedded styles
- `Logo.png` - Replace with your own logo
- Modern orange color scheme throughout

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 📄 License

MIT License - feel free to use this for your own projects!

## 🙏 Credits

Created with AI assistance to demonstrate the possibilities of modern web development.

---

**Note**: This version uses OpenStreetMap with Leaflet.js which is completely free and doesn't require any API keys!