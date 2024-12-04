[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/PX83n--N)
# NeXtCS Project 01
### Name0: Solomon Binyaminov
### Name1: Georgy Krasnov
---

### Overview
Your mission is create either:
- Life-like cellular automata [life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), [life-like](https://en.wikipedia.org/wiki/Life-like_cellular_automaton), [demo](https://www.netlogoweb.org/launch#https://www.netlogoweb.org/assets/modelslib/Sample%20Models/Computer%20Science/Cellular%20Automata/Life.nlogo).
- Breakout/Arkanoid [demo 0](https://elgoog.im/breakout/)  [demo 1](https://www.crazygames.com/game/atari-breakout)
- Space Invaders/Galaga

This project will be completed in phases. The first phase will be to work on this document. Use markdown formatting. For more markdown help [click here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)


---

## Phase 0: Selection, Analysis & Plan

#### Selected Project: Cellular Automata

### Necessary Features
- Grid display with cell states
- Start/pause simulation
- Game of Life rules implementation
- Cell toggling
- Generation counter
- Grid wrapping
- Reset functionality

### Extra Features
- Preset patterns
- Color schemes
- Speed control
- Grid size options
- Statistics display
- Grid lines toggle
- Save/load patterns

### Array Usage

1D Array:
- idk

2D Array:
- Main cell grid
- Next generation calculation

### Controls

Keyboard Commands:
- SPACE: Start/pause
- R: Reset
- G: Toggle grid
- Arrows: Speed control
- 1-9: Load presets

Mouse Control:
- Click: Toggle cell
- Drag: Draw cells
- Right click: Erase cells

### Classes

Cell
- Instance variables:
  - boolean isAlive
  - int x, y
  - int age
  - color displayColor
- Methods:
  - toggle(), update(), display()
  - countNeighbors()
  - setColor()

Grid
- Instance variables:
  - Cell[][] grid
  - int rows, cols
  - boolean isRunning
  - int generation, updateRate
- Methods:
  - updateGrid(), display(), reset()
  - getPopulation(), savePattern(), loadPattern()
  - setUpdateRate(), toggleCell(), loadPreset()
