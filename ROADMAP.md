# ASTRAVEN — Development Roadmap

## Current Status

Project Stage: PRE-PROTOTYPE

Current Goal:

Build the smallest playable version of ASTRAVEN in Godot 4.

The priority is gameplay, not final graphics.

Use placeholder assets when necessary.

Do not expand the scope until the current phase is playable and tested.

---

# PHASE 1 — PLAYABLE CORE

## Goal

Create one small test scene where the player can:

- Move left and right
- Jump
- Aim / face direction
- Shoot
- Damage one enemy
- Take damage
- Die and restart

## Systems

### 1. Godot Project Setup

Create the basic Godot 4 project structure.

Suggested structure:

assets/
scenes/
scripts/
audio/
fonts/

Do not create unnecessary folders yet.

---

### 2. Player Controller

Implement:

- Left / right movement
- Acceleration and deceleration
- Jump
- Gravity
- Ground detection
- Character facing direction

Movement should feel responsive.

Do not add:

- Dash
- Wall jump
- Double jump
- Climbing
- Advanced parkour

until basic movement is tested.

---

### 3. Camera

Implement:

- Camera follows player
- Smooth movement if appropriate
- Basic level boundaries

Avoid complex cinematic camera systems.

---

### 4. First Weapon

Prototype weapon:

ASSAULT RIFLE

Design direction:

Realistic sci-fi firearm using conventional ammunition.

Prototype features:

- Fire
- Fire rate
- Magazine
- Reload
- Damage
- Muzzle flash placeholder
- Recoil feedback
- Basic gun sound placeholder

Initial test values may be temporary.

Do not build a large weapon inventory system yet.

---

### 5. First Enemy

Create one simple alien enemy.

Prototype behavior:

- Idle
- Detect player
- Approach player
- Attack
- Take damage
- Die

Focus on readable behavior.

Do not create complex AI.

---

### 6. Health and Damage

Implement a simple reusable system for:

- Player health
- Enemy health
- Damage
- Death

Keep the system simple and reusable.

---

### 7. Test Environment

Create ONE small test area.

Use placeholder graphics.

Include:

- Floor
- Platforms if needed
- Walls
- One enemy encounter
- Space for movement and shooting

This is NOT Mission 1.

It is a gameplay laboratory.

---

### 8. Basic UI

Only display information needed for testing:

- HP
- Ammo
- Reload state if necessary

Primary game language:

Thai

Final visual design is NOT required yet.

---

## PHASE 1 — DEFINITION OF DONE

Phase 1 is complete only when:

1. The project launches without critical errors.
2. The player can move reliably.
3. The player can jump reliably.
4. The camera works.
5. The player can shoot.
6. The weapon can reload.
7. One enemy can detect and attack the player.
8. Player and enemy can damage each other.
9. Enemy can die.
10. Player can die and restart.
11. The complete gameplay loop can be tested in one scene.

After completion:

STOP.

Review the prototype before starting Phase 2.

---

# PHASE 2 — GAME FEEL

DO NOT START UNTIL PHASE 1 IS REVIEWED.

Possible goals:

- Improve movement feel
- Improve gun recoil
- Better muzzle flash
- Shell casing effects
- Hit reactions
- Impact effects
- Camera shake
- Better enemy feedback
- Basic sound design
- Basic lighting
- First temporary pixel-art assets

The goal is:

MAKE THE BASIC GAME FUN.

Do not add large new systems.

---

# PHASE 3 — FIRST VERTICAL SLICE

DO NOT START UNTIL PHASE 2 IS REVIEWED.

Build a short section representing the real ASTRAVEN experience.

Possible structure:

Alien Planet
    ↓
Explore landscape
    ↓
Discover abandoned facility
    ↓
Enter facility
    ↓
Something feels wrong
    ↓
First hostile encounter
    ↓
Discover evidence of survivors
    ↓
Reach temporary ending

Target experience:

Approximately 5–10 minutes.

Include:

- Japanese retro sci-fi pixel-art direction
- Thai UI
- Atmospheric lighting
- Environmental sound
- Realistic firearm feel
- Exploration
- Mystery
- Light horror
- One memorable encounter

This vertical slice becomes the foundation for future development.

---

# NOT NOW

The following features are explicitly OUT OF SCOPE
until the prototype proves they are necessary:

- Multiplayer
- Online services
- Crafting
- Large inventory systems
- Skill trees
- Procedural generation
- Open world
- Large dialogue systems
- Complex quests
- Multiple playable characters
- Large weapon arsenal
- Vehicle systems
- Base building
- Complex save systems
- Final boss
- Full story implementation

Do not implement these without explicit approval.

---

# DEVELOPMENT RULE

At every development step ask:

"Does this help us reach a playable ASTRAVEN prototype?"

If NO:

Do not build it yet.