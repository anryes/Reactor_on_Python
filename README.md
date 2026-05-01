# Reactor Temperature Simulator

## Description

A simple reactor temperature simulator written in Python.

The program simulates reactor operation:
- the reactor heats up automatically,
- the user can cool the reactor or increase its power,
- the system monitors critical temperature levels,
- the simulation stops if the temperature becomes dangerous.

This project was created as practice for:
- loops
- conditions
- state simulation
- user interaction
- basic system logic

---

# Features

- Automatic reactor heating
- Manual cooling system
- Power increase mode
- Critical temperature control
- Interactive console menu
- Infinite simulation loop until reactor shutdown

---

# Technologies

- Python 3
- while loop
- if / elif conditions
- input()
- f-strings

---

# How It Works

1. Reactor temperature increases automatically every cycle.
2. User chooses an action:
   - cool the reactor
   - increase reactor power
3. Program checks reactor state.
4. Simulation stops if:
   - temperature reaches critical level
   - temperature falls below zero

---

# Example

```python
Temperature of reactor: 55

1 - to lower the temperature of reactor
2 - to rise the temperature of reactor

You will choose: 2

Temperature of reactor: 65
