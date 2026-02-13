# 💕 Valentine's Pixelated Cat Mini Games 💕

A charming, interactive Valentine's Day mini-game website featuring pixelated cats and romantic games. This is a **pure HTML, CSS, and JavaScript** project with no dependencies required.

## 🎮 Features

### Games Included

1. **Guessing Couple Year Game** - Test your memory by guessing what year you started dating
2. **Guessing First Day Game** - Guess your first day together (format: MM/DD/YYYY)
3. **Heart Crane Game** - Interactive crane game where you catch 5 hearts to win
4. **Love Letter** - A beautiful typed love letter with a sweet message

### Gift Boxes (After Completing Games)

Three interactive gift boxes held by adorable pixelated cats:

- **🧡 Lalay (Orange Cat)** - 10 pictures gallery with descriptions of your favorite moments
- **🩶 Chitchay (Grey Cat)** - Favorite music playlist with song titles and artists
- **🧡🤎 Kikay (Calico Cat)** - Heartfelt compliments and reasons why you love her

## 📋 How to Use

### Quick Start

1. Extract the zip file
2. Open `index.html` in any modern web browser
3. Click "START GAME" and enjoy!

### Customization

Edit the `index.html` file to personalize the games:

```javascript
// Line ~510 - Update these values:
const COUPLE_YEAR = 2020;           // Your actual year
const FIRST_DAY = "02/14/2020";     // Your actual first day (MM/DD/YYYY)

const LOVE_LETTER = `
    Your custom love letter here...
`;
```

### Customize Gift Content

**For Lalay's Pictures (Line ~650):**
- Replace the emoji placeholders with actual image URLs
- Update descriptions for each picture

**For Chitchay's Music (Line ~680):**
- Add your favorite songs with titles and artists
- Customize the music list

**For Kikay's Compliments (Line ~710):**
- Edit the compliment messages
- Add more compliments as needed

## 🎨 Design Features

- **Retro Arcade Aesthetic** - 8-bit/16-bit pixel art style with smooth animations
- **Romantic Color Palette** - Warm coral, soft pink, and gold accents
- **Smooth Animations** - Bouncy interactions, floating particles, and typewriter effects
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Particle Effects** - Floating hearts and sparkles on interactions

## 🎯 Game Instructions

### Guessing Couple Year
- Enter the year you started dating
- The game gives hints if you're wrong (earlier or later)
- Submit the correct year to proceed

### Guessing First Day
- Enter your first day together in MM/DD/YYYY format
- Example: 02/14/2020
- Get it right to move to the next game

### Heart Crane Game
- Click and drag the golden crane hook left and right
- Position it over the hearts to catch them
- Catch 5 hearts to win and unlock the love letter

### Love Letter
- Read the beautiful typed message
- Click "Open Your Gifts" to proceed to the gift boxes

### Gift Boxes
- Click on each cat to see their gift
- Lalay: Browse through 10 special pictures
- Chitchay: Listen to your favorite songs
- Kikay: Read heartfelt compliments

## 💻 Technical Details

- **No Dependencies** - Pure HTML, CSS, and JavaScript
- **No Server Required** - Works completely offline
- **Modern Browser Support** - Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- **File Size** - Lightweight (~40KB)
- **Performance** - Optimized for smooth animations and interactions

## 🎵 Fonts Used

- **Press Start 2P** - Retro pixel font for titles (from Google Fonts)
- **Nunito** - Friendly, readable font for body text (from Google Fonts)
- **Caveat** - Handwritten style font for special text (from Google Fonts)

## 📱 Browser Compatibility

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎁 Tips for Best Experience

1. **Full Screen** - For the best experience, open in full screen
2. **Sound** - Consider adding background music while playing
3. **Sharing** - You can share the HTML file with your loved one
4. **Customization** - Personalize all the content to make it special
5. **Mobile** - Works great on mobile devices for on-the-go fun

## 🔧 Customization Guide

### Change Background Color
Find the `body` CSS rule and modify the gradient:
```css
background: linear-gradient(135deg, #FFF8F0 0%, #FFE8F0 50%, #FFD9E8 100%);
```

### Change Font Sizes
Adjust the `.title` class for different heading sizes:
```css
.title {
    font-size: 2.5rem; /* Change this value */
}
```

### Add More Pictures
In the Lalay gift section, duplicate a gallery-item div and update the emoji and description.

### Change Color Scheme
Search for color codes like `#FF6B9D` (pink) and `#FFB6D9` (light pink) and replace with your preferred colors.

## 📝 File Structure

```
valentine_cat_games_standalone/
├── index.html          # Complete game code (HTML + CSS + JavaScript)
├── README.md           # This file
└── ideas.md            # Design philosophy and brainstorm
```

## 🎉 Enjoy!

This Valentine's mini-game website is designed to bring joy and celebrate your love. Customize it, share it, and have fun! 💕

---

**Created with ❤️ for your special someone**

For questions or customization help, refer to the inline comments in the HTML file.
