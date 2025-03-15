
---

# RPG - Dragon Repeller  
You can access the game in this link down below:
https://fadliazharr.github.io/RPG-game/

**Dragon Repeller** is a simple text-based RPG where players embark on a quest to defeat a powerful dragon terrorizing the town. Players can explore different locations, fight monsters, upgrade weapons, and manage health and gold to survive.  

## Features  

- **Explore Different Locations** – Visit the town square, store, and cave, or engage in battles.  
- **Fight Various Monsters** – Battle slimes, fanged beasts, and the final boss: the dragon.  
- **Upgrade Weapons** – Buy and sell weapons to increase attack power.  
- **Manage Resources** – Track experience (XP), health, and gold while making strategic choices.  
- **Dynamic Combat System** – Attack, dodge, and take risks with breakable weapons.  
- **Easter Egg Minigame** – A hidden number game where you can win extra gold.  

## How It Works  

1. **Start in the Town Square**  
   - Choose between **going to the store**, **exploring the cave**, or **fighting the dragon** directly (not recommended at first).  

2. **Buy Supplies at the Store**  
   - Purchase health potions for **10 gold** to restore HP.  
   - Upgrade weapons for **30 gold**, increasing attack power.  
   - Sell weapons for **15 gold** if needed.  

3. **Battle Monsters in the Cave**  
   - Fight a **Slime**, **Fanged Beast**, or the **Dragon**.  
   - Each monster has a different **health level** and **attack power**.  
   - Use weapons wisely—some may **break** during battle.  

4. **Combat Mechanics**  
   - **Attack**: Deals damage based on your weapon and XP.  
   - **Dodge**: Avoid enemy attacks (but doesn't deal damage).  
   - **Run Away**: Return to the town square safely.  

5. **Defeat the Dragon to Win the Game**  
   - Survive battles, upgrade your gear, and take on the dragon to win.  

## Technologies Used  

- **HTML** – Structure of the game interface.  
- **CSS** – Styling for UI elements.  
- **JavaScript** – Game logic, interactions, and event handling.  

## Code Overview  

### **HTML (`index.html`)**  
- Creates the main game UI with sections for **stats, controls, and combat information**.  
- Uses **buttons** to allow players to navigate and interact with the game.  

### **CSS (`styles.css`)**  
- Styles the game with a **dark RPG aesthetic**.  
- Uses color coding for different UI sections (**red for danger, gold for interactions**).  

### **JavaScript (`script.js`)**  
- **Manages Game State**: Tracks XP, health, gold, weapons, and inventory.  
- **Location System**: Players move between **town, store, cave, and battles**.  
- **Battle Mechanics**: Damage is calculated dynamically, and weapons can break.  
- **Win/Lose Conditions**: Defeat the dragon to win, or lose all health to restart.  
- **Easter Egg**: A fun **number-guessing minigame** for extra gold.  

## Expected Output  

- **Example Scenario:**  
  ```
  Welcome to Dragon Repeller! 
  You are in the town square. Where do you want to go?  
  [Go to store] [Go to cave] [Fight dragon]
  ```
- **After Buying a Weapon:**  
  ```
  You now have a sword. In your inventory: stick, dagger, sword.
  ```
- **During Combat:**  
  ```
  The fanged beast attacks!  
  You strike with your sword.  
  The fanged beast has 10 health left.
  ```
- **Victory Message:**  
  ```
  You defeat the dragon! YOU WIN THE GAME!
  ```

---

