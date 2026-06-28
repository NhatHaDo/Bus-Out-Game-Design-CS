# Bus Out! — Level Design Document

## Level Design Goals

The goal of the level design is to introduce mechanics gradually and increase difficulty step by step.

Each level should teach or combine one design idea:

- Color matching
- Movement order
- Blocking
- Temporary parking slots
- Limited moves
- Mixed passenger colors
- Multi-step planning

## Level 1 — Color Match Tutorial

### Goal

Teach the player that buses pick up passengers with the same color.

### Layout

- 1 red bus
- 3 red passengers
- Clear exit path
- No obstacles
- No parking slots

### Move Limit

3 moves

### Difficulty

Tutorial

### Expected Player Behavior

The player taps or drags the red bus and sees the red passengers board the bus.

### Design Purpose

This level teaches the basic color matching rule without pressure.

---

## Level 2 — Movement Order

### Goal

Teach the player that some buses block other buses.

### Layout

- 1 red bus
- 1 blue bus
- Red bus blocks the blue bus
- Blue passengers are near the exit
- No parking slots

### Move Limit

5 moves

### Difficulty

Easy

### Expected Player Behavior

The player moves the red bus first to open the path for the blue bus.

### Design Purpose

This level introduces the idea of movement order.

---

## Level 3 — Temporary Parking Slot

### Goal

Teach the player how to use a temporary parking slot.

### Layout

- 3 buses
- 2 passenger colors
- 1 temporary parking slot
- 1 blocked lane

### Move Limit

7 moves

### Difficulty

Medium

### Expected Player Behavior

The player moves one bus into the temporary parking slot to create a path for another bus.

### Design Purpose

This level teaches that parking slots are useful but limited.

---

## Level 4 — Mixed Passengers

### Goal

Teach the player to plan based on passenger colors and order.

### Layout

- 4 buses
- 3 passenger colors
- Mixed passenger groups
- 1 obstacle
- 1 parking slot

### Move Limit

10 moves

### Difficulty

Medium

### Expected Player Behavior

The player checks passenger colors before moving buses and chooses the correct bus order.

### Design Purpose

This level combines color matching and movement planning.

---

## Level 5 — Advanced Blocking Puzzle

### Goal

Combine blocking, color matching, parking slots, and limited moves.

### Layout

- 5 buses
- 4 passenger colors
- 3 obstacles
- 2 parking slots
- Multiple blocked paths

### Move Limit

12 moves

### Difficulty

Hard

### Expected Player Behavior

The player plans several steps before making the first move.

### Design Purpose

This level tests whether the player understands the main mechanics.

---

# Difficulty Progression

| Level | Main Mechanic | Difficulty Reason |
|---|---|---|
| 1 | Color matching | One bus, one color, no obstacle |
| 2 | Movement order | One bus blocks another bus |
| 3 | Parking slot | Player must use limited temporary space |
| 4 | Mixed passengers | Player must plan based on colors |
| 5 | Combined mechanics | Multiple buses, colors, obstacles, and move limit |

## Level Design Notes

Good puzzle levels should be:

- Clear
- Fair
- Solvable
- Easy to understand
- Harder through planning, not confusion

A good level should make the player think:

"What should I move first?"