# Faith Quest — Starter (Godot + C#)

This repository is a minimal starter for the "Faith Quest" mobile game built with Godot (C# / Mono). It is intentionally small so you can open it in Godot, let the engine generate its C# solution files, and start developing.

## Prerequisites

- Godot 4.x with Mono (C#) support installed
- .NET SDK compatible with your Godot version (usually .NET 6 or .NET 7)
- git

## What's included

- .gitignore — recommended ignores for Godot + C#
- LICENSE (MIT)
- src/Main.cs — tiny C# script that prints a startup message
- scenes/Main.tscn — a minimal scene that uses the script

## Quick setup

1. Clone the repo:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-directory>
   ```

2. Open the project folder in Godot (choose `project.godot` if present, otherwise open folder and create/import a project). If Godot hasn't created the C# solution files yet, open the Editor and Godot will generate them when needed.

3. Ensure the Mono / C# support is enabled in your Godot installation. If you see prompts to generate solution files, allow it.

4. From the Godot editor, open `scenes/Main.tscn` and press Play to run the scene. You should see the message `Hello Bible Trivia Adventure!` in the output console.

5. Commit and push:
   ```bash
   git add .
   git commit -m "chore: initial Godot C# starter for Bible Trivia Adventure"
   git push origin main
   ```

## Next suggestions

- Open Godot and confirm the project runs.
- Configure a consistent project.godot (Godot will create/update it) and commit it.
- Add a basic project icon and launcher scene for mobile export later.
- When you're ready, I can: create an initial scene UI prototype, set up input mapping for touch controls, or scaffold a small quiz mini-game.

Happy coding — we can take the next tiny step when you're ready.
