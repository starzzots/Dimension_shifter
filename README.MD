# Game Development To-Do List
### Frame work
- Decided to use raylib in python because I hate myself :D. And because I can switch over to C at any time when game is complete if im running into performance issues and for learning game dev at its core.
## 1. Core Game Systems

### Unit System:
- Design the `Unit` class with attributes like health, damage, abilities, and timeline.
- Implement basic actions: attack, take damage, heal, and use abilities.
- Add unit classes or subclasses based on specializations (e.g., healers, tanks, damage dealers).

### Timeline System:
- Create a timeline manager that tracks and switches between different timelines (Alpha, Beta, etc.).
- Implement timeline-based effects (e.g., different resources, unit abilities, or map features for each timeline).

### Combat System:
- Implement a turn-based combat system: Each unit takes actions in a turn sequence (attack, ability use, etc.).
- Set up a combat state that handles initiating, progressing, and ending combat.
- Implement targeting logic (random or strategic targeting of enemies).

---

## 2. Game Flow

### Game Initialization:
- Create the starting point for the game (choose starting units, timeline, etc.).
- Set up basic unit creation and starting resources.

### Turn Management:
- Implement a system that advances the game in turns: combat phases, timeline shifts, and event triggers.
- Track turns and add effects based on turn progression.

### Victory/Defeat Conditions:
- Define what constitutes victory or defeat in a mission or combat scenario (e.g., all enemies defeated, timeline restored).

---

## 3. Map System

### Map Layout:
- Create a map generator that produces random maps (based on size and timeline).
- Design the map grid (could be a 2D grid with obstacles, areas to traverse, etc.).
- Implement obstacles, environmental effects, or special zones (depending on timeline).

### Map Events:
- Introduce special map events based on timelines (e.g., weather effects, terrain alterations, etc.).
- Handle unit movement and positioning on the map during combat.

---

## 4. Abilities and Skills

### Ability System:
- Implement an ability system for units with customizable effects (e.g., heal, buffs, debuffs, area attacks).
- Design and code a set of abilities for different unit types (e.g., healers, tanks, damage dealers).

### Ability Interactions:
- Handle ability interactions with the environment and other units (e.g., healing allies, damaging enemies, buffing defenses).
- Introduce new abilities or modify abilities based on timeline changes.

---

## 5. Game Progression & Story

### Story Integration:
- Design the basic story flow (starting point, timeline-shifting narrative, universe repair).
- Implement key story events based on player actions (e.g., timeline restoration, discovering hidden timeline events).

### Mission Design:
- Create different mission types based on the story (rescue, defend, assassinate, repair timeline).
- Include narrative choices that affect future gameplay (e.g., which timeline to repair first).

### Leveling/Progression:
- Introduce a system for leveling up units or gaining new abilities over time.
- Allow units to gain experience and improve based on combat performance.

---

## 6. UI/UX

### HUD (Heads-Up Display):
- Design a basic UI to show unit stats, health, abilities, and turn order.
- Include timeline information to show the current universe state and progress toward timeline restoration.

### Combat Interface:
- Build combat-related UI (selecting units, choosing abilities, showing enemy actions).
- Show health bars, action buttons, and enemy stats.

### World/Map Screen:
- Create a screen for the map where players can choose where to deploy units, or explore the universe.
- Implement visual indicators for timeline shifts and map events.

---

## 7. Enemy and AI Behavior

### Enemy Units:
- Create enemy unit types with similar attributes and abilities as the player’s units.
- Design the AI to take actions based on certain behaviors (e.g., healing, attacking, prioritizing specific units).

### AI Decision Making:
- Implement basic AI logic for combat (e.g., choosing targets, using abilities).
- Create difficulty scaling based on timeline (more aggressive or strategic enemies in later timelines).

---

## 8. Testing & Debugging

### Unit Testing:
- Write unit tests for core mechanics (e.g., unit health, damage calculation, ability effects).

### Combat Testing:
- Test the combat system with different unit combinations.
- Verify correct interactions with the environment (e.g., using abilities on obstacles or terrain).

### Bug Fixing:
- Debug common issues like incorrect ability effects, UI glitches, or combat logic errors.
- Test the game on multiple platforms to ensure compatibility.

---

## 9. Deployment & Future Enhancements

### Game Polish:
- Finalize combat animations, sound effects, and music for a smooth experience.
- Add polish to the UI/UX for ease of use.

### Future Enhancements:
- Introduce more complex abilities, new timeline types, and story events.
- Implement advanced enemy AI or multiplayer functionality (if desired).

---

## 10. Documentation

### Game Documentation:
- Write documentation for your game mechanics, how the combat system works, and the role of timelines in the story.
- Include a development roadmap for future updates or enhancements.

---

# Summary of Next Steps:
1. **Build out the core unit and combat mechanics**.
2. **Start with basic timeline and map generation**.
3. **Design a turn-based combat loop**.
4. **Iterate on game flow and integrate the story**.
5. **Work on adding enemy AI and progressing through the game**.
