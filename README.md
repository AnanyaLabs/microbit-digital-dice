# Digital Dice Using micro:bit

## Project Image

(Project image will be added soon.)

## Project Overview

This project demonstrates how the micro:bit can simulate a digital dice.

When the user presses a button, the micro:bit generates a random number between 1 and 6 and displays it using the LED matrix.

## Learning Objectives

- Understand random number generation.
- Learn micro:bit programming concepts.
- Explore button inputs and LED outputs.
- Build an interactive electronic project.

## Components Required

| Component | Quantity |
|------------|----------|
| BBC micro:bit | 1 |
| USB Cable | 1 |
| Battery Pack | 1 |

## Working Principle

1. User presses Button A.
2. micro:bit generates a random number.
3. Number is displayed on the LED matrix.
4. User can roll again by pressing the button.

## MakeCode Program

```javascript
input.onButtonPressed(Button.A, function () {
    basic.showNumber(randint(1, 6))
})
```

## Applications

- Educational games
- Probability demonstrations
- Interactive learning
- Beginner coding projects

## Future Improvements

- Shake-to-roll feature
- Multiplayer dice game
- Score tracking
- Wireless communication

## Author

AnanyaLabs
