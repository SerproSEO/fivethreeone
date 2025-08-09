# Restaurant Picker Game - Setup Instructions

## Getting Started

### 1. Get a Google Maps API Key

1. Go to the [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select an existing one
3. Enable the following APIs:
   - Maps JavaScript API
   - Places API
4. Go to "Credentials" and create an API key
5. (Optional but recommended) Restrict your API key to your domain

### 2. Add Your API Key

Open `restaurant-picker-game.html` and find this line at the bottom:
```html
src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places&callback=initMap">
```

Replace `YOUR_API_KEY` with your actual Google Maps API key.

### 3. Open the Game

Simply open `restaurant-picker-game.html` in your web browser!

## How to Play

### The 5-2-1 Method

1. **Step 1 - Pick 5**: Player 1 searches and selects 5 restaurants
2. **Step 2 - Remove 2**: Player 2 eliminates 2 restaurants they don't want
3. **Step 3 - Final Choice**: Player 3 (or Player 1 if no third player) picks the final restaurant

### Features

- **Search Mode**: Use Google's autocomplete to search for specific restaurants
- **Nearby Mode**: Find restaurants near your current location
- **Quick Picks**: Select from popular cuisine types (Pizza, Burger, Sushi, etc.)
- **Random Selection**: Let the app randomly select restaurants for you
- **Player Names**: Customize player names for a personal experience
- **History**: Save your restaurant choices for future reference
- **Get Directions**: Click to open the winning restaurant in Google Maps

### Tips

- The game works best with location services enabled
- You can use Player 3 as a tie-breaker or let Player 1 make the final choice
- Use the random selection features for a fun surprise
- Your history is saved locally and shows your last 10 picks

## Improvements Made

Beyond the basic 5-2-1 game flow, I've added:

1. **Player Customization**: Name all players for a personalized experience
2. **Search Flexibility**: Both search and nearby modes
3. **Quick Categories**: Fast selection by cuisine type
4. **Random Options**: Random selection at each step for spontaneity
5. **Visual Feedback**: Clear step indicators and selection counters
6. **Restaurant Details**: Shows ratings, reviews, and addresses
7. **Game History**: Track where you've eaten before
8. **Direct Navigation**: Get directions to the chosen restaurant
9. **Responsive Design**: Works on desktop and mobile devices
10. **Beautiful UI**: Clean, modern design inspired by your reference

Enjoy picking your next meal!