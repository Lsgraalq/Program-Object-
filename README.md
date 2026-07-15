# Program-Object-

Early practice with **object-oriented programming in Python** — a set of small classes covering the basics: defining classes and methods, `__init__`, properties/setters, static methods, encapsulation, and simple text menus.

> The files have no `.py` extension, but they are plain Python scripts. Run them with, e.g. `python pervoe`.

## Programs

### `pervoe` — Football roster
A `Footbaleri` class that stores a team's players and their shirt numbers as methods, then prints the full lineup. A first look at classes and calling methods on an object.

### `Vtoroe` — Virtual pet
A `Critter` class implementing a small "virtual pet" console game. Demonstrates more advanced OOP features:
- private attributes (`__name`, `__pass_time`)
- `@property` / `@name.setter` for controlled access
- `@staticmethod` and a class-level counter (`total`)
- `__init__` and `__str__`
- a mood system based on hunger/boredom, driven by an interactive menu (feed, play, talk).

### `trerie` — TV controller
A `Telik` class that simulates configuring a TV: it validates the channel (1–50) and volume (1–100) with input checks and an interactive settings menu.

## Stack

- Python 3
