# Bus Out! — Game Design Case Study

![Bus Out Game Design Overview](assets/images/bus-out-game-design-overview.png)

## Overview

**Bus Out!** is a casual mobile puzzle game design case study inspired by bus-route planning and passenger-matching mechanics.

The player manages a crowded bus station where buses are blocked in traffic and passengers are waiting in a strict queue. Each bus has a color and capacity, while passengers can only board buses of the same color. The player must dispatch buses in the correct order, use limited parking spots wisely, and avoid deadlock situations.

This project focuses on game design thinking, including core loop design, puzzle mechanics, level progression, balancing, player experience, and paper-based playtesting.

## Project Goals

* Create a clear Game Design Document.
* Define core mechanics, game rules, win/lose conditions, and player goals.
* Design sample puzzle levels with increasing difficulty.
* Analyze player experience and possible deadlock situations.
* Plan balancing factors such as bus colors, bus capacities, passenger queue order, parking spots, obstacles, and move limits.
* Practice paper-based playtesting and design iteration.

## Core Gameplay Loop

**Observe → Plan → Dispatch Bus → Match Passengers → Free Parking Spot → Clear Level → Unlock Next Level**

The player first observes the station layout and passenger queue, then decides which bus should be dispatched first. A correct decision helps passengers board and frees space for the next bus. A wrong decision can block parking spots and create a deadlock.

## Core Mechanics

### 1. Passenger Color Matching

Each passenger has a color, and each bus also has a color.
Passengers can only board buses of the same color.

### 2. Strict Passenger Queue

Passengers board in order.
If the first passenger in the queue cannot board a matching bus, the boarding process stops even if other passengers behind them have matching buses available.

### 3. Limited Parking Spots

The station has a limited number of parking spots.
Each dispatched bus occupies one spot until it becomes full and leaves the station.

### 4. Bus Blocking / Route Planning

Some buses are blocked by other buses or obstacles.
The player must choose the correct dispatch order to open paths and avoid getting stuck.

### 5. Deadlock

A deadlock happens when no useful move is left, parking spots are occupied, and the remaining passengers cannot board.

## Key Design Areas

* Game Design Document
* Core Loop Design
* Puzzle Mechanics
* Level Design
* Player Experience
* Difficulty Balancing
* Paper-based Playtesting

## Documents

* [Game Design Document](docs/BusOut_GDD.md)
* [Level Design Document](docs/Level_Design.md)
* [Balancing Sheet](docs/Balancing_Sheet.csv)
* [Playtesting Notes](docs/Playtesting_Notes.md)
* [Sample Level Layouts](docs/Sample_Level_Layouts.md)

## Target Platform

Mobile devices:

* Android
* iOS

## Target Audience

Casual mobile players who enjoy:

* Short puzzle sessions
* Simple rules
* Colorful visual feedback
* Logic and planning challenges
* Gradually increasing difficulty

## Design Highlights

* Simple rules that are easy to understand.
* Strategic challenge created by bus order, passenger queue, and parking limits.
* Clear win/lose conditions.
* Difficulty progression through more colors, more buses, fewer parking spots, obstacles, and stricter move limits.
* Paper-based playtesting to evaluate rule clarity, level fairness, and player experience.

## Project Status

First portfolio version completed.

Future improvements may include:

* More sample levels
* Detailed UI mockups
* A hint system design
* A reward and progression system
* A playable prototype
* Additional playtesting results

## Skills Demonstrated

* Game Design Documentation
* Core Loop Design
* Puzzle Mechanics Design
* Level Design
* Player Experience Analysis
* Game Balancing
* Paper-based Playtesting
* Design Communication
