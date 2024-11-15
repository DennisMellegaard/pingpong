# Tennis Score Counter

A Raspberry Pi-based tennis score counter with physical buttons and web interface display.

## Overview

This project implements a tennis score counting system using:
- Two physical buttons (white and black) connected to a Raspberry Pi
- A web interface for score display
- Flask backend for handling button inputs and serving the web interface

## Features

- **Score Management**:
  - Short press: Increment score
  - Long press (>1 second): Decrement score
  - Press both buttons (>0.5 seconds): Reset both scores to zero

- **Web Interface**:
  - Split-screen display (white/black)
  - Real-time score updates
  - Responsive design that works on any screen size
  - Instructions displayed on the white side

## Hardware Requirements

- Raspberry Pi (any model with GPIO pins)
- 2 push buttons
  - White button connected to GPIO 3
  - Black button connected to GPIO 17
- Pull-down resistors for each button (if not using internal pull-down)

## Software Requirements

- Python 3
- Flask
- gpiozero
- jQuery (included)

## Installation

1. Clone the repository:
2. `pip install -r requirements.txt`

## What I did
- Added a debugging mode that shows the buttons and reset button
- Added a winner check
- Added a instructions fade in and out
- Added a random team name generator
- Added a confetti effect when a player wins
- Added a cake animation when a player wins 11-0

