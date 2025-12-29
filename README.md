# Space Invaders (FXGL)

A JavaFX/FXGL implementation of Space Invaders with multiple levels, enemies, and power-ups. This repository contains the source code for the game.

## Diagram

```mermaid
flowchart LR
    Input[Player input] --> GameLoop[Game loop]
    GameLoop --> Update[Update entities]
    Update --> Render[Render scene]
    Render --> Input
```

## Project Structure

```
SpaceInvadersCW2/
  src/main/java/...  # Game code
  src/main/resources # Assets
  REQUIREMENTS.md
```

## Requirements

See `REQUIREMENTS.md`.

## How to Run

This repo does not include a build configuration. The simplest way to run it:

1. Open the project in your IDE.
2. Add FXGL and JavaFX to the classpath.
3. Run `SpaceInvadersApp`.

Main class:

```
com.almasb.fxglgames.spaceinvaders.SpaceInvadersApp
```

## Controls

- Move left/right: `A` / `D`
- Shoot: Mouse left button
- Laser: Mouse right button
