**CMPM 120 Project 1**

**Title:** Mission Possible

**Author:** Alice Gu  

**Game Description**

You play as a spy infiltrating a high-security building to steal encrypted data.  
The map includes multiple security rooms, keycards, and interactive hacking systems.

**Item Interactions**

1. **Flashlight** – Can be toggled on/off to explore dark rooms.  
2. **Crowbar** – Used to pry open panels and reveal hidden access cards.  
3. **Hack Terminal (USB + Access Code)** – Requires two items; unlocks the Locked Archive.  
4. **Combine Biometric + Token** – Multi-item interaction to fool the biometric scanner.  
5. **Distract Guard** – Optional action that changes world state and allows locker access.

**Scoring System**

Each item has an assigned value (defined in item_values).  
Final score = sum of collected item values ÷ number of steps taken.  
Rare or important items (like the encrypted drive) give higher scores.

**Bonus Features**

- Implemented **dark room mechanic** with flashlight requirement.  
- Added **multi-item crafting/hacking puzzles**.  
