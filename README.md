# Flappy Bird Game

A modern, responsive Flappy Bird clone with a sleek dark theme that works on both desktop and mobile devices.

![Flappy Bird Game Screenshot](https://api/placeholder/600/400)

## 🎮 Play Now

You can play the game by opening the HTML file directly in your browser, or by visiting:
[Your Deployment URL Here]

## ✨ Features

- **Cross-platform Compatibility**: Works on both desktop and mobile devices
- **Responsive Design**: Adapts to different screen sizes and orientations
- **Sleek Dark Theme**: Easy on the eyes with a modern UI
- **High Score System**: Your best scores are saved between sessions
- **Smooth Animations**: Parallax backgrounds, animated bird, twinkling stars
- **Simple Controls**: Tap screen (mobile) or press spacebar (desktop) to play

## 🛠️ Technical Details

- Built using pure HTML5, CSS, and JavaScript
- Uses the p5.js library for rendering and game logic
- No external dependencies beyond p5.js
- Single file architecture for easy deployment
- Optimized for 60 FPS performance

## 🚀 How to Deploy

### Method 1: Local Deployment
1. Download the `index.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, etc.)

### Method 2: GitHub Pages
1. Create a GitHub repository
2. Upload the HTML file and rename it to `index.html`
3. Enable GitHub Pages in repository settings
4. Your game will be available at `https://[username].github.io/[repository]`

### Method 3: Netlify
1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop the HTML file 
3. Get an instant deployment with a public URL

## 🎯 How to Play

1. Press the "Start Game" button
2. Control the bird by:
   - Desktop: Press SPACEBAR to make the bird flap
   - Mobile: Tap the screen to make the bird flap
3. Navigate through the gaps between pipes
4. Each successfully passed pipe earns you 1 point
5. Game ends when the bird hits a pipe or the ground/ceiling
6. Press "Play Again" to restart

## 🔧 Customization

You can easily customize aspects of the game by modifying the code:

- **Colors**: Change the `COLORS` object in the JavaScript section
- **Difficulty**: Adjust `gravity`, `jumpForce`, or `pipeSpawnInterval` variables
- **Gap Size**: Modify `this.gapSize` in the Pipe class
- **Speed**: Change `parallaxSpeed` or pipe speed settings

## 🧑‍💻 Development

Want to extend the game? Here are some ideas:
- Add power-ups
- Implement different bird characters
- Create different difficulty levels
- Add sound effects and music
- Implement a day/night cycle

## 📄 License

This project is available under the MIT License. Feel free to use, modify, and distribute it.

## 🙏 Credits

- Original Flappy Bird game was created by Dong Nguyen
- This version uses the p5.js library (https://p5js.org/)
- Game assets and code created by [Your Name]
