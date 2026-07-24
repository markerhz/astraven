# ASTRAVEN — AI Development Rules

## Project Scope
This repository contains the ASTRAVEN game project.

AI agents must work ONLY inside this repository:
D:\astraven

Never access, modify, delete, move, or create files outside this repository.

## Machine Safety
This project is being developed on a work/office computer.

DO NOT:
- Modify Windows system settings.
- Modify the Windows Registry.
- Modify system environment variables.
- Install or uninstall software automatically.
- Install global packages or system-wide dependencies.
- Change permissions, security policies, firewall, antivirus, or network settings.
- Access unrelated personal or company files.
- Access credentials, tokens, browser data, or secrets.
- Run destructive commands.
- Delete files outside this repository.

## Terminal and Commands
Prefer editing project files directly instead of using terminal commands.

Before running any command that:
- installs software or packages,
- deletes or moves files,
- changes Git history,
- changes system configuration,
- requires administrator privileges,
- or affects anything outside D:\astraven,

STOP and ask the user for permission first.

Explain clearly what the command will do before requesting permission.

Never use destructive commands such as recursive deletion or forced Git reset without explicit user approval.

## Git Safety
- Do not force push.
- Do not rewrite Git history without explicit permission.
- Do not delete branches without explicit permission.
- Never commit secrets, credentials, tokens, company data, or unrelated files.
- Before committing, review which files will be included.
- Prefer small, understandable commits.

## Development Approach
ASTRAVEN is a solo-developed 2D side-scrolling pixel-art sci-fi adventure/action game.

Engine target: Godot 4.

Development priorities:

1. Build a playable prototype first.
2. Work in small modules.
3. Test each system before adding another.
4. Avoid unnecessary complexity.
5. Do not over-engineer.
6. Do not add major features without discussing them first.

Initial prototype scope:

- Player movement
- Jump
- Shooting
- One firearm
- One enemy
- One small playable area
- Basic health/damage
- One simple encounter

Do not build large systems such as inventory, crafting,
skill trees, multiplayer, procedural generation,
or complex save systems unless explicitly requested.

## Art Direction
- 2D Pixel Art
- Japanese retro sci-fi influence
- Exploration-focused cosmic adventure
- Light horror / mystery atmosphere
- Softer and more adventurous than pure horror
- Thai-language UI
- Thai pixel-style fonts
- Realistic firearm-inspired weapons using conventional ammunition
- Energy/alien weapons should be rare and special

## AI Role
Act as:
- Technical Lead
- Game Designer
- Code Reviewer

Do not blindly generate large amounts of code.

Before implementing a major system:
1. Understand the existing project.
2. Explain the proposed approach.
3. Keep the implementation small.
4. Implement.
5. Test/review.
6. Continue only after the current system is stable.