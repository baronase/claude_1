# 🐒 Monkey Stacks

**My first Claude project** - A modern web-based remake of the classic DOS puzzle game "Monkey Business".

## About

Monkey Stacks is a Tower of Hanoi-inspired puzzle game where you stack monkeys of different sizes to collect apples. This is a complete HTML5 implementation with no external dependencies.

The original inspiration comes from the retro DOS game "Monkey Business," where the puzzle mechanics revolve around carefully moving creatures to reach goals while following stacking rules.

## How to Play

### Goal
Collect both apples! 🍎

### Rules
- **Move one monkey at a time** - Only the top monkey in a stack can be moved
- **Size constraint** - A smaller monkey can only be placed on top of a larger monkey
- **Apple collection** - When all monkeys are properly stacked on a peg with an apple, it's consumed
- **Win condition** - Collect both apples by stacking all monkeys on each peg with an apple

### Controls
- Press **1**, **2**, or **3** to select pegs
  - First press: Select the peg to move FROM (highlighted in gold)
  - Second press: Select the peg to move TO and execute the move
- Press **R** to reset the current level

### Difficulty Levels
- **Easy (3 monkeys)** - Great for beginners
- **Medium (4 monkeys)** - A classic Tower of Hanoi challenge
- **Hard (5 monkeys)** - For puzzle enthusiasts

## Running the Game

Simply open `index.html` in any modern web browser. No installation or build process required!

```bash
# Clone and play
git clone https://github.com/baronase/claude_1.git
cd claude_1
open index.html  # macOS
# or just open it in your browser
```

## Strategy Tip

This is essentially the Tower of Hanoi puzzle - use the third peg as a helper to move monkeys between pegs. The minimum number of moves needed is 2^n - 1 (where n is the number of monkeys).

---

Built with ❤️ using Claude AI
