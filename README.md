
# ENGR103FinalProjectMemoryGame

A simple memory matching game using the Adafruit Circuit Playground Express. 


## Features

- Audible speech feedback
- LED feedback
- Scoring System (10 points to win)
- Difficulty increases each round


## Input Guide
![cpx01](https://github.com/nicholasqle/ENGR103FinalProjectMemoryGame/assets/131207716/a4203aa8-c005-4d56-ad78-c2a187d576fb)

## How To Play
1. Start new game using the A button.
2. Listen for numbers. The game starts out with one number but progressively gets more difficult as it continues. After each successful sequence, an additional integer gets added and new random numbers are chosen.
3. Start inputting the sequence of numbers using the capacitive touchpads. 
4. If the number is correct, the lights will turn green. If not, the lights will turn red and you can try again. You get up to 3 attempts to retry the sequence.
5. The game ends if you win by getting the final sequence of 10 numbers correct, or lose by quitting early or getting 3 incorrect attempts. You will receive your score of how many sequences you got correct through the number of LED lights. If you win by getting 10 correct, they will be green! 

## Author

- [@nicholasqle](https://www.github.com/nicholasqle)


## Acknowledgements

Incorporates speech from Adafruit Circuit Playground [Speech_Demos](https://github.com/adafruit/Adafruit_CircuitPlayground/tree/master/examples/Speech_Demos) 
Talkie Library Copyright 2011 Peter Knight.
