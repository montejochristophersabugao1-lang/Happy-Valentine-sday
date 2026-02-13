# 📱 Mobile Installation & Setup Guide

## Quick Start for Mobile Users

### Option 1: Direct Browser Access (Easiest)
1. On your mobile device, open any web browser
2. Navigate to the location where you saved the HTML file
3. Tap on `index_mobile.html` to open it
4. Enjoy the game!

### Option 2: Create a Home Screen Shortcut (iOS/Android)

#### For iPhone/iPad (iOS):
1. Open Safari browser
2. Navigate to your HTML file
3. Tap the **Share** button (square with arrow)
4. Select **Add to Home Screen**
5. Give it a name (e.g., "Valentine Games")
6. Tap **Add**
7. The app will now appear on your home screen as a shortcut

#### For Android:
1. Open Chrome or your preferred browser
2. Navigate to your HTML file
3. Tap the **Menu** button (three dots)
4. Select **Add to Home Screen** or **Install app**
5. Confirm the installation
6. The app will appear on your home screen

### Option 3: File Manager Access
1. Extract the zip file on your device
2. Open your file manager
3. Navigate to the extracted folder
4. Tap on `index_mobile.html`
5. Select "Open with" and choose your browser

## 📋 Which File to Use?

| File | Best For | Features |
|------|----------|----------|
| `index_mobile.html` | **Mobile devices** | Touch controls, responsive design, optimized for small screens |
| `index.html` | Desktop/Laptop | Mouse controls, larger layout, better for big screens |

**Recommendation**: Use `index_mobile.html` on phones and tablets for the best experience!

## 🎮 Mobile Game Controls

### Guessing Games
- **Tap** the input field
- **Type** your answer
- **Tap** SUBMIT button or press Enter

### Heart Crane Game (Mobile)
- **Tap and hold** the golden hook
- **Drag left and right** to move the hook
- **Release** to drop it
- **Catch 5 hearts** to win!

### Gift Boxes
- **Tap** on each cat to open their gift
- **Swipe** through pictures in the gallery
- **Tap** the X button to close the gift

## 🔧 Customization on Mobile

You can edit the HTML file on your mobile device using:

### Text Editors for Mobile:
- **iOS**: Textastic, Koduo, or iSH
- **Android**: QuickEdit, Turbo Editor, or Acode

### Steps to Customize:
1. Open `index_mobile.html` with a text editor
2. Find these lines (around line 510-515):
   ```javascript
   const COUPLE_YEAR = 2020;           // Change to your year
   const FIRST_DAY = "02/14/2020";     // Change to your date
   const LOVE_LETTER = `...`;          // Change the message
   ```
3. Save the file
4. Open it in your browser to see changes

## 📱 Mobile Browser Compatibility

| Browser | iOS | Android | Status |
|---------|-----|---------|--------|
| Safari | ✅ | N/A | Fully supported |
| Chrome | ✅ | ✅ | Fully supported |
| Firefox | ✅ | ✅ | Fully supported |
| Samsung Internet | N/A | ✅ | Fully supported |
| Edge | ✅ | ✅ | Fully supported |

## 🎯 Mobile Optimization Features

### Responsive Design
- Automatically adjusts to any screen size
- Readable text on small screens
- Touch-friendly button sizes (minimum 44x44px)

### Touch Controls
- Tap instead of click
- Swipe support for galleries
- Drag support for crane game
- No hover effects (uses active states instead)

### Performance
- Lightweight (~40KB)
- Smooth animations on mobile
- Minimal battery drain
- Works offline

### Accessibility
- Large, easy-to-tap buttons
- Clear, readable fonts
- High contrast colors
- Keyboard support for inputs

## 📲 Sharing with Your Loved One

### Method 1: Email
1. Attach the HTML file to an email
2. Send to your loved one
3. They can open it directly from their email

### Method 2: Cloud Storage
1. Upload the file to Google Drive, Dropbox, or OneDrive
2. Share the link with your loved one
3. They can download and open it

### Method 3: Messaging Apps
1. Send the file via WhatsApp, Telegram, or other apps
2. Recipient opens it directly from the message

### Method 4: QR Code
1. Use a QR code generator to create a code from your file path
2. Share the QR code
3. Recipient scans it to open the file

## 🐛 Troubleshooting

### Game Won't Load
- **Solution**: Clear your browser cache and reload
- **iOS**: Settings → Safari → Clear History and Website Data
- **Android**: Chrome Menu → Settings → Privacy → Clear browsing data

### Touch Controls Not Working
- **Solution**: Make sure you're using `index_mobile.html` (not `index.html`)
- **Solution**: Try a different browser
- **Solution**: Restart your device

### Text Too Small
- **Solution**: Pinch to zoom (if needed)
- **Solution**: The game automatically scales to your screen size
- **Solution**: Try landscape mode for a larger view

### Crane Game Difficult
- **Solution**: Move slowly and deliberately
- **Solution**: Try using your thumb instead of finger
- **Solution**: Ensure you have enough screen space

### Input Fields Not Responding
- **Solution**: Make sure the input field is focused (highlighted)
- **Solution**: Try tapping directly in the text box
- **Solution**: Use your device's keyboard

## 💡 Tips for Best Mobile Experience

1. **Use Landscape Mode** - More space for games, especially crane game
2. **Full Screen** - Tap the full-screen button in your browser
3. **Disable Auto-Brightness** - Prevents screen dimming during gameplay
4. **Close Other Apps** - Frees up memory for smoother performance
5. **Use WiFi** - Faster loading (though it works offline)
6. **Portrait Mode** - Better for reading the love letter

## 🎁 Customization Tips for Mobile

### Adding Real Pictures
1. Save pictures to your device
2. Use a text editor to edit the HTML
3. Replace emoji with image URLs:
   ```html
   <img src="path/to/your/photo.jpg" style="width:100%; height:100%; object-fit:cover;">
   ```

### Changing Colors
Search for color codes in the file:
- `#FF6B9D` (Pink)
- `#FFB6D9` (Light Pink)
- `#FFD700` (Gold)
- `#C41E3A` (Dark Red)

Replace with your favorite colors!

### Adding More Music
Find the music section and add more songs:
```html
<div class="music-item">
    <div class="music-icon">🎵</div>
    <div class="music-info">
        <div class="music-title">Your Song Title</div>
        <div class="music-artist">Artist Name</div>
    </div>
</div>
```

## 📞 Support

If you encounter any issues:
1. Check the troubleshooting section above
2. Try a different browser
3. Restart your device
4. Re-download the file
5. Check that you're using `index_mobile.html`

## 🎉 Enjoy!

This game is optimized for mobile devices. Have fun playing and celebrating your love! 💕

---

**Pro Tip**: Save this guide to your device for easy reference while playing!
