# Bus Out! — Game Design Document

## 1. Game Overview

**Bus Out!** is a casual mobile puzzle game where players organize buses and passengers in a crowded bus station.

The player must move buses in the correct order, match passengers with buses of the same color, and clear the station within a limited number of moves. The challenge comes from blocked paths, limited parking slots, mixed passenger colors, and increasing puzzle complexity.

The game is designed for short mobile play sessions, simple controls, colorful feedback, and gradually increasing difficulty.

## 2. Game Genre

- Casual Puzzle
- Mobile Puzzle
- Logic / Route Planning Game

## 3. Target Platform

- Android
- iOS

## 4. Target Audience

The game is designed for casual mobile players who enjoy:

- Simple one-touch or drag controls
- Short levels
- Color-matching puzzles
- Gradual difficulty progression
- Satisfying visual feedback
- Games that are easy to understand but harder to master

## 5. Design Goals

The main design goals are:

1. Make the rules easy to understand within the first level.
2. Give players a sense of planning and problem-solving.
3. Increase difficulty gradually without making the game feel unfair.
4. Use color, movement, and feedback to make actions satisfying.
5. Encourage replay when players fail due to wrong move order.

## 6. Core Gameplay Loop

The core loop is:

1. Observe the bus station layout.
2. Identify which buses and passengers match by color.
3. Decide the correct movement order.
4. Move a bus or place it in a temporary parking slot.
5. Pick up matching passengers.
6. Clear blocked paths.
7. Complete the level.
8. Receive reward and unlock the next level.

In short:

**Observe → Plan → Move → Match → Clear → Reward → Next Level**

## 7. Player Objective

The player's objective is to clear all required buses and passengers from the station.

To complete a level, the player must:

- Move buses in the correct order.
- Match buses with passengers of the same color.
- Avoid blocking all possible movement paths.
- Stay within the move limit.

## 8. Core Mechanics

### 8.1 Bus Movement

Players tap or drag buses to move them out of the station.

A bus can move only if its path is not blocked by another bus, an obstacle, or the station boundary.

### 8.2 Color Matching

Each bus has a color. Each passenger also has a color.

A bus can only pick up passengers of the same color.

Example:

- Red bus picks up red passengers.
- Blue bus picks up blue passengers.
- Yellow bus picks up yellow passengers.

### 8.3 Blocking System

Some buses block the path of other buses.

Players must decide which bus should move first. If the wrong bus is moved too early, the player may lose available space or waste moves.

### 8.4 Limited Moves

Each level has a move limit.

The move limit creates pressure and encourages players to think before acting.

### 8.5 Temporary Parking Slots

Some levels include temporary parking slots.

A parking slot allows a bus to move aside temporarily. However, the number of slots is limited, so the player must use them carefully.

### 8.6 Obstacles

Obstacles block movement paths and increase level difficulty.

Examples:

- Road barriers
- Station signs
- Blocked lanes
- Fixed buses

## 9. Game Rules

1. A bus can only move if its path is clear.
2. A bus can only pick up passengers with the same color.
3. Each movement counts as one move.
4. The player must clear all required passengers and buses to win.
5. If the player runs out of moves, the level fails.
6. If no valid move remains, the level fails.
7. Parking slots can be used only if they are empty.

## 10. Win Condition

The player wins when:

- All passengers are picked up by matching buses.
- All required buses leave the station.
- The player completes the level within the move limit.

## 11. Lose Condition

The player loses when:

- The move limit reaches zero.
- No valid moves remain.
- Remaining passengers cannot be matched with available buses.
- Important paths become completely blocked.

## 12. Level Progression

The game starts with simple levels that teach one mechanic at a time.

Difficulty increases by adding:

- More buses
- More passenger colors
- More obstacles
- Fewer parking slots
- Stricter move limits
- More complex blocking situations
- Mixed passenger order

## 13. Tutorial Design

The tutorial should teach mechanics gradually.

### Level 1

Teach color matching.

### Level 2

Teach movement order.

### Level 3

Teach temporary parking slots.

### Level 4

Teach mixed passenger colors.

### Level 5

Combine all basic mechanics.

## 14. UI / UX Flow

Basic player flow:

1. Open game.
2. Tap Play.
3. Enter Level 1.
4. Read a short tutorial hint.
5. Move buses.
6. Complete or fail the level.
7. See result screen.
8. Continue to next level or retry.

## 15. Feedback Design

The game should provide clear feedback for every player action.

Examples:

- Matching passengers jump or walk into the bus.
- Wrong bus selection gives a small shake animation.
- Completed level shows celebration effects.
- Low move count shows warning feedback.
- Blocked path is highlighted when the player tries an invalid move.

## 16. Reward Design

Possible rewards:

- Stars based on remaining moves
- Coins for completing levels
- New bus skins
- New station themes
- Daily challenge rewards

## 17. Monetization Ideas

Possible monetization options:

- Rewarded ads for extra moves
- Rewarded ads for hints
- Cosmetic bus skins
- No-ads purchase
- Special theme packs

The monetization should not make the game feel unfair. Players should be able to complete levels without paying.

## 18. Balancing Factors

Important balancing factors include:

- Number of buses
- Number of passenger colors
- Number of obstacles
- Number of parking slots
- Move limit
- Passenger order
- Available movement paths
- Level completion time

The goal is to make levels challenging but understandable.

## 19. Player Experience Goals

The intended player experience is:

- Easy to understand
- Satisfying to solve
- Slightly challenging
- Visually clear
- Rewarding after completion
- Encouraging retry after failure

The player should feel that failure comes from poor planning, not unfair design.

## 20. Future Improvements

Future improvements could include:

- More level themes
- Special buses with unique rules
- Timed challenge mode
- Daily puzzle mode
- Hint system
- Level editor
- Player analytics for balancing