# 🍀 Bad Luck Yuval - Avoid the Money! 💰

A hilarious web-based game where Yuval desperately tries to avoid falling money from the sky!

[![Static Badge](https://img.shields.io/badge/%F0%9F%92%B0%20Click%20to%20play%20online!-green?style=for-the-badge)](https://shakedzy.xyz/bad-luck-yuval)


## 🎮 Game Concept

Poor Yuval has the worst luck imaginable - money keeps falling from the sky and he absolutely HATES money! Help him dodge massive piles of cash for 60 seconds in this fast-paced, increasingly difficult arcade game.

## 🕹️ How to Play

### Objective
- **Avoid ALL falling money** for 1 minute
- **Higher money values** = more points when successfully avoided
- **Getting hit by money** = penalty and bad luck for Yuval!

### Controls
- **Arrow Keys** (← →) or **A/D** keys to move left and right
- **Movement**: Fast and responsive for quick dodging

### Game Progression
- **Every 10 seconds**: Yuval grows bigger (making him a larger target!)
- **Every 5 seconds**: Money falls faster and spawns more frequently
- **Multiple money pieces** can fall simultaneously
- **6 growth levels** throughout the 60-second game

## 💰 Money Types & Values

| Emoji | Type | Value | Size |
|-------|------|-------|------|
| 💵 | Bill | $1,000 | Small |
| 💴 | Bill | $5,000 | Small |
| 💶 | Bill | $10,000 | Medium |
| 💷 | Bill | $25,000 | Medium |
| 💰 | Money Bag | $50,000 | Large |
| 🏆 | Jackpot | $100,000 | Extra Large |

## 🎯 Game Features

### 🎨 Visual Design
- **Colorful gradient backgrounds** for a fun, playful look
- **Character design**: Yuval with his actual face, body, arms, and legs
- **Progressive growth**: Yuval gets bigger every 10 seconds
- **Explosion effects** when hit by money
- **Smooth animations** and transitions

### 🔊 Sound Effects
- **Start sound**: Cheerful ascending tones
- **Hit sound**: Ominous low tones when struck by money
- **Avoid sound**: Happy chirp for each successful dodge
- **Growth sound**: Ascending notes when Yuval grows
- **Game over sound**: Descending jingle

### ⚡ Progressive Difficulty
- **Spawn rate**: Starts at 400ms, drops to 150ms minimum
- **Fall speed**: Progressively increases throughout the game
- **Money size**: Ranges from 65px to 110px
- **Multiple spawns**: 1-3 money pieces can fall at once
- **Limited movement area**: Confined to center 60% of screen

### 📊 Scoring System
- **Points earned**: Each avoided money piece adds its value
- **Penalty system**: Getting hit deducts 2x the money value
- **Smart formatting**: Displays as "150K" or "1.2M" for readability
- **Achievement levels**: Different messages based on final score

## 🏆 Achievement Levels

| Score Range | Achievement |
|-------------|-------------|
| 500K+ | 🏆 Master Money Avoider! |
| 300K+ | 😎 Successfully avoided capitalism! |
| 150K+ | 😊 Dodged some serious cash! |
| 50K+ | 😅 Got a bit wealthy, but not bad! |
| <50K | 😂 Accidentally became rich! |

## 🔧 Technical Details

### Built With
- **HTML5** - Game structure
- **CSS3** - Styling, animations, and character design
- **Vanilla JavaScript** - Game logic and mechanics
- **Web Audio API** - Sound effects

### Game Mechanics
- **Collision detection**: Precise hit detection between Yuval and money
- **Dynamic sizing**: CSS custom properties for character growth
- **Responsive design**: Adapts to different screen sizes
- **Performance optimized**: Efficient animation and memory management

### Browser Compatibility
- **Modern browsers** with ES6+ support
- **Chrome, Firefox, Safari, Edge** (latest versions)
- **Mobile responsive** design

## 🚀 How to Run

### Method 1: Direct File Opening
1. Download `bad-luck-yuval.html` and `the-yuval.png`
2. Double-click the HTML file to open in your browser
3. Press "START GAME" and begin avoiding money!

### Method 2: Local Server (Recommended)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## 🎪 Game Tips

### 🧠 Strategy
- **Keep moving**: Standing still = certain doom!
- **Watch for patterns**: Money often falls in predictable sequences
- **Use the edges**: But don't get trapped!
- **Prepare for growth**: Position yourself well before Yuval grows

### ⚠️ Warnings
- **Movement becomes harder** as Yuval grows
- **Money gets HUGE** - some pieces are 110px wide!
- **Multiple pieces** can corner you quickly
- **Speed increases dramatically** in the final 20 seconds

## 🎭 Character Details

**Yuval** starts as a modest character but grows every 10 seconds:

### Growth Progression
- **Body**: 80px → 180px (6 levels)
- **Arms**: 60px → 135px (6 levels) 
- **Legs**: 40px → 90px (6 levels)
- **Hands**: 14px → 29px (6 levels)

## 🌟 Fun Facts

- **Theme**: Based on the humorous concept of someone who genuinely hates free money
- **Character**: Features the actual face image of Yuval
- **Sound Design**: All sounds generated in real-time using Web Audio API
- **No External Dependencies**: Completely self-contained game
- **Favicon**: 💰 Money bag emoji for that extra polish

## 🐛 Known Issues

- **Audio**: Some browsers may require user interaction before playing sounds
- **Mobile**: Touch controls not yet implemented (keyboard only)
- **Performance**: Very old browsers may experience lag with many money pieces

## 🤝 Contributing

Feel free to fork and improve the game! Some ideas for enhancements:
- Touch/mobile controls
- Power-ups or special abilities
- Different character skins
- Multiplayer mode
- Leaderboard system

## 📜 License

This code is open source and available under the [MIT License](LICENSE).
The images and photos are not allowed to be re-used or redistributed in any form or method
without written approval.

---

**Have fun avoiding money and may Yuval's bad luck not rub off on you!** 🍀💸

*Created with ❤️ and a sense of humor*
