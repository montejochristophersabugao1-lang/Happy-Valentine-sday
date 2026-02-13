# 🎨 Complete Customization Guide

This guide will help you personalize every aspect of your Valentine's mini-games!

## 📝 Basic Customization (Easy)

### 1. Change the Couple Year
**File**: `index_mobile.html` or `index.html`
**Line**: ~510

Find this line:
```javascript
const COUPLE_YEAR = 2020;
```

Change `2020` to your actual year:
```javascript
const COUPLE_YEAR = 2023;  // Your year here
```

### 2. Change the First Day
**File**: `index_mobile.html` or `index.html`
**Line**: ~511

Find this line:
```javascript
const FIRST_DAY = "02/14/2020";
```

Change to your actual date in MM/DD/YYYY format:
```javascript
const FIRST_DAY = "05/15/2022";  // Your date here
```

### 3. Change the Love Letter
**File**: `index_mobile.html` or `index.html`
**Line**: ~513-521

Find this section:
```javascript
const LOVE_LETTER = `
    Every moment with you feels like a beautiful dream I never want to wake up from.
    Your smile brightens my darkest days, and your laughter is the sweetest music to my ears.
    I fall in love with you more and more each day, in the smallest moments and the biggest adventures.
    Thank you for being my best friend, my partner, and my greatest love.
    Forever yours, with all my heart. 💕
`;
```

Replace with your own message:
```javascript
const LOVE_LETTER = `
    Your custom message here...
    You can write multiple lines...
    Add as much as you want! 💕
`;
```

## 🎁 Customize Gift Content

### Lalay's Pictures (10 Pictures Gallery)

**File**: `index_mobile.html` or `index.html`
**Line**: ~650-700 (search for "LALAY'S GIFT")

Each picture item looks like this:
```html
<div class="gallery-item">
    <div style="background: linear-gradient(135deg, #FF6B9D, #FFB6D9); width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; font-size: 3rem;">📸</div>
    <div class="gallery-description">Our first date</div>
</div>
```

**To customize:**
1. Change the emoji (e.g., `📸` → `🌹`)
2. Change the description (e.g., `Our first date` → `Our first kiss`)
3. To add real images, replace the div with:
```html
<div class="gallery-item">
    <img src="path/to/your/image.jpg" alt="Description">
    <div class="gallery-description">Your description here</div>
</div>
```

### Chitchay's Music (Favorite Songs)

**File**: `index_mobile.html` or `index.html`
**Line**: ~680-710 (search for "CHITCHAY'S GIFT")

Each music item looks like this:
```html
<div class="music-item">
    <div class="music-icon">🎵</div>
    <div class="music-info">
        <div class="music-title">Our Song</div>
        <div class="music-artist">The Perfect Love Song</div>
    </div>
</div>
```

**To customize:**
1. Change the music icon emoji
2. Change the song title
3. Change the artist name
4. Add or remove music items as needed

### Kikay's Compliments

**File**: `index_mobile.html` or `index.html`
**Line**: ~710-750 (search for "KIKAY'S GIFT")

Each compliment looks like this:
```html
<div class="compliment-text">
    💕 You are the most beautiful person I know, inside and out. Your kindness radiates from your smile and touches everyone around you.
</div>
```

**To customize:**
1. Change the emoji at the start
2. Write your own compliment
3. Add or remove compliments as needed

## 🎨 Advanced Customization

### Change Color Scheme

**Primary Pink**: `#FF6B9D`
**Light Pink**: `#FFB6D9`
**Dark Red**: `#C41E3A`
**Gold**: `#FFD700`
**Cream**: `#FFF8F0`
**Lavender**: `#E8D5F2`

**To change colors:**
1. Open the HTML file in a text editor
2. Use Find & Replace (Ctrl+H or Cmd+H)
3. Find: `#FF6B9D`
4. Replace with: `#YourColorCode`
5. Repeat for other colors

**Popular color combinations:**
- **Purple Theme**: Replace `#FF6B9D` with `#9B59B6`
- **Blue Theme**: Replace `#FF6B9D` with `#3498DB`
- **Green Theme**: Replace `#FF6B9D` with `#27AE60`
- **Orange Theme**: Replace `#FF6B9D` with `#E67E22`

### Change Font Sizes

**Title Font Size**: Search for `.title { font-size:`
**Subtitle Font Size**: Search for `.subtitle { font-size:`
**Body Font Size**: Search for `.game-container { font-size:`

Example:
```css
.title {
    font-size: clamp(1.5rem, 8vw, 2.5rem);  /* Change these values */
}
```

### Change Background Gradient

Find this line:
```css
body {
    background: linear-gradient(135deg, #FFF8F0 0%, #FFE8F0 50%, #FFD9E8 100%);
}
```

Change the colors:
```css
body {
    background: linear-gradient(135deg, #E8F5E9 0%, #F3E5F5 50%, #FCE4EC 100%);
}
```

### Change Animation Speed

Find animations like:
```css
@keyframes catWave {
    animation: catWave 2s ease-in-out infinite;  /* 2s is the duration */
}
```

Change `2s` to a different value:
- `1s` = Faster
- `3s` = Slower
- `0.5s` = Very fast

## 📱 Mobile-Specific Customization

### Adjust Button Size
Find:
```css
.start-button {
    padding: clamp(12px, 3vw, 15px) clamp(30px, 8vw, 40px);
}
```

Change the values to make buttons larger or smaller.

### Adjust Game Container Size
Find:
```css
.crane-game {
    height: clamp(300px, 60vw, 400px);
}
```

Change to adjust the crane game height on mobile.

### Adjust Text Size
The `clamp()` function automatically scales text:
```css
font-size: clamp(1rem, 3vw, 1.1rem);
         /* min   |  scale  | max */
```

- Increase the first value to make text larger on small screens
- Increase the third value to make text larger on big screens

## 🎮 Game Mechanics Customization

### Change Crane Game Difficulty
**File**: `index_mobile.html` or `index.html`
**Line**: ~580 (search for "craneScore >= 5")

Change `5` to a different number:
```javascript
if (craneScore >= 10) {  // Catch 10 hearts instead of 5
    document.getElementById('nextCraneBtn').style.display = 'block';
}
```

### Change Typing Speed
**File**: `index_mobile.html` or `index.html`
**Line**: ~750 (search for "setTimeout(typeText, 50)")

Change `50` to a different value (in milliseconds):
```javascript
setTimeout(typeText, 30);  // Faster typing (30ms)
setTimeout(typeText, 100); // Slower typing (100ms)
```

### Add More Gift Boxes
1. Duplicate a gift-box div in the gifts section
2. Change the cat emoji
3. Change the cat name
4. Change the gift label
5. Add the openGift() function for the new cat

Example:
```html
<div class="gift-box" onclick="openGift('newcat')">
    <div class="cat-character">😺</div>
    <div class="cat-name">NEWCAT</div>
    <div class="gift-label">New Gift</div>
</div>
```

Then add the function:
```javascript
} else if (catName === 'newcat') {
    title.textContent = '😺 NEWCAT - NEW GIFT';
    body.innerHTML = `Your content here`;
}
```

## 🔤 Text Content Changes

### Game Titles
Search for and change:
- `💑 GUESS OUR YEAR 💑`
- `📅 GUESS OUR DAY 📅`
- `💗 HEART CRANE 💗`
- `🎁 YOUR GIFTS 🎁`

### Button Text
Search for and change:
- `START GAME`
- `SUBMIT`
- `NEXT GAME →`
- `Open Your Gifts →`

### Placeholder Text
Search for and change:
- `Enter year`
- `MM/DD/YYYY`
- `Tap and drag the hook`

## 🎯 Example: Complete Customization

Here's an example of customizing everything:

```javascript
// Change couple info
const COUPLE_YEAR = 2021;
const FIRST_DAY = "07/20/2021";

// Change love letter
const LOVE_LETTER = `
    My dearest [Name],
    
    From the moment I met you, I knew you were special.
    Every day with you is a gift I treasure.
    
    I love your smile, your laugh, and the way you make me feel.
    You are my everything.
    
    Forever and always,
    [Your Name] 💕
`;
```

Then customize the gifts:
```html
<!-- Lalay's Pictures -->
<div class="gallery-item">
    <img src="photo1.jpg" alt="Our first kiss">
    <div class="gallery-description">Our first kiss</div>
</div>

<!-- Chitchay's Music -->
<div class="music-item">
    <div class="music-icon">🎵</div>
    <div class="music-info">
        <div class="music-title">Your Song</div>
        <div class="music-artist">Your Artist</div>
    </div>
</div>

<!-- Kikay's Compliments -->
<div class="compliment-text">
    💕 You make me the happiest person in the world.
</div>
```

## 🆘 Troubleshooting Customization

### Changes Not Showing
1. **Clear browser cache**: Ctrl+Shift+Delete (Chrome) or Cmd+Shift+Delete (Safari)
2. **Hard refresh**: Ctrl+F5 (Windows) or Cmd+Shift+R (Mac)
3. **Close and reopen** the browser

### Text Looks Wrong
1. Check for missing quotes: `"text"` not `text`
2. Check for missing backticks: `` ` `` for multi-line text
3. Check for special characters that need escaping

### Game Doesn't Work After Changes
1. Check for syntax errors (missing commas, brackets)
2. Use browser developer tools (F12) to check console for errors
3. Revert changes and try again

### Colors Look Different
1. Different devices display colors differently
2. Try adjusting brightness/contrast on your device
3. Test on multiple devices for best results

## 📚 Resources

### Color Tools
- **Color Picker**: https://htmlcolorcodes.com/
- **Gradient Generator**: https://cssgradient.io/
- **Color Palette**: https://coolors.co/

### Text Editors
- **Desktop**: VS Code, Notepad++, Sublime Text
- **Mobile**: Textastic (iOS), QuickEdit (Android)

### Emoji Resources
- **Emoji List**: https://emojipedia.org/
- **Emoji Picker**: https://emoji-picker.com/

## 🎉 Have Fun!

Customize the game to make it truly yours! The more personal touches you add, the more special it will be for your loved one. 💕

---

**Need help?** Check the README.md or MOBILE_GUIDE.md for more information!
