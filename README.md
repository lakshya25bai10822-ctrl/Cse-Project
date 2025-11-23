<h1>Description</h1>

This project is a simple console-based Slot Machine game written in Python.
It allows the user to deposit money, choose how many lines to bet on, place bets, spin the slot machine, and see winnings based on matched symbols.

The program uses Python’s random module to simulate slot spins and calculates winnings according to preset symbol values.


---

<h2>🧠 Features</h2>

Deposit money before playing

Choose number of lines to bet (1–3)

Choose bet amount for each line

Validations for input and bet limits

Simulated 3×3 slot machine spin

Winnings calculated based on matching symbols

Displays winning lines and updated balance

Loops until the user quits



---

🔧 How the Game Works

1. Deposit Money

The game begins by asking the player how much they want to deposit.
Only positive integers are accepted.

2. Select Betting Lines

You can bet on 1 to 3 lines, where each line represents a horizontal row on the slot grid.

3. Place Bet

You choose how much to bet on each line.
The allowed bet range per line is $1 to $100.

4. Spin

The slot machine will spin and produce random symbols based on preset probabilities.

Symbols are:

A (rare, highest payout)

B

C

D (most common, lowest payout)


5. Check Winnings

If all three symbols match on a line, the player wins money based on the symbol’s value.

Symbol Values

Symbol	Value

A	
5× bet
B	
4× bet
C	
3× bet
D	
2× bet


6. Continue or Quit

The game continues until the player types q.# Cse-Project
