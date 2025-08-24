# ⚔️ Epic RPG 2D Battle Arena

A browser-based, wave-based RPG battle game with animated 2D avatars, auto-attacking enemies, and multiple difficulty modes. Survive 10 waves of increasingly tough enemies and defeat the Ancient Dragon Lord!

---

## Features

- **Three Difficulty Modes:** Easy, Normal, Hard (affecting enemy damage, player health, and supplies)
- **10 Waves:** Each wave brings stronger enemies; the final wave is a boss fight
- **Animated 2D Battle Arena:** Player and enemies have animated avatars and battle effects
- **Auto Enemy Attacks:** Enemies attack automatically every 2 seconds
- **Player Actions:** Attack, Defend, Use Potion, Use Bomb, Next Wave, Restart
- **Auto Combat Mode:** Let the AI fight for you
- **Leveling System:** Gain XP, level up, and grow stronger after each wave
- **Responsive UI:** Modern, RPG-inspired interface with visual feedback

---

## How to Play

1. **Open `epic-rpg-2d-working.html` in your browser.**
2. **Choose a difficulty** and click "Start Adventure".
3. **Battle enemies** using the action buttons:
   - **Attack:** Deal damage to the selected enemy.
   - **Defend:** Reduce incoming damage on the next enemy attack.
   - **Use Potion:** Restore a portion of your HP.
   - **Use Bomb:** Damage all living enemies.
   - **Next Wave:** Advance to the next wave after defeating all enemies.
   - **Restart:** Restart the game at any time.
4. **Survive all 10 waves** to win!

---

## Controls

- **Mouse:** Click action buttons and enemies to select targets.
- **Auto Mode:** (If enabled) The AI will choose actions for you.

---

## Game Structure

- **Main Menu:** Select difficulty and start the game.
- **Battle Arena:** Fight waves of enemies in a 2D animated arena.
- **Player Panel:** Shows your stats, HP, XP, potions, bombs, and wave number.
- **Enemy Panel:** Shows all current enemies, their stats, and health bars.
- **Battle Effects:** Animated damage, healing, and critical hit effects.
- **Action Buttons:** Attack, Defend, Heal, Bomb, Next Wave, Restart.
- **Auto Mode:** Toggle to let the AI play for you.

---

## Technical Details

- **Single HTML file:** No dependencies, just open in your browser.
- **All logic in JavaScript:** No backend required.
- **Responsive CSS:** Works on desktop and most tablets.
- **No external assets required:** All graphics are CSS/emoji-based.

---

## Customization

- **Enemy Types:** Edit the `enemyPool` array in the JS section to add or modify enemies.
- **Boss:** Edit the `bossTemplate` for the final boss stats.
- **Player Stats:** Change the `player` object for starting stats.
- **Difficulty Multipliers:** Adjust the `difficultyMultipliers` object for game balance.
- **UI/Graphics:** Tweak CSS for a different look or add your own images.

---

## File List

- `index.html` — Main game file (open this in your browser)

---

## Note

This project is for personal use.  
Feel free to share any modification and share with others!

---

Enjoy your adventure!
