*Complex Sequential Circuit*

A Combination lock controlled by three buttons (A, B, C). The lock will open when the buttons are pressed in the correct (ACBC) order. The code will have 4 digits. If an error occurs when entering the code, the machine will return to its initial state.

Pressing multiple buttons is either a don’t care.

Decoder made at the input, which reduces the number of FSM inputs.

Entering the code correctly unlocks the lock. When the lock is unlocked, the LED lights up. The code lock will lock again by pressing any button. The number of the automaton’s current state is shown on the display (for debugging purposes only).
The flip-flop clocks here are connected directly to the 50 MHz oscillator of the development kit. So you have to solve the problem with the debounce blocks (debounce blocks).

To consider states when no button is pressed. The following is an example of going through each state an edge detector is used.
