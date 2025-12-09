# tictactoepcb
TicTacToe on a PCB

I created this project because I wanted to learn more about PCBs and electronics in general.

I desided to use the ATmega328P-P as the MCU because it has plenty of pins, is cheap or can be optained from an Arduino Uno.
9x addressable LEDs. "APA-106-F5" or any other kind that can handle 5v should work.

It's being powered by an USB-C port at the top.

The top 9 LEDs show the current field. The single LED below the MCU indicates which player should take their turn.
The 9 bottom buttons allow you to select your move.


# PCB
Layout:

![layout](pics/pcb_layout.png?raw=true)


Front:

![layout](pics/pcb_front.png?raw=true)


Back:

![layout](pics/pcb_back.png?raw=true)


Schematics:

![layout](pics/schematics.png?raw=true)


Button wiring is a mess... because I wanted the pins to be aligned on the actual PCB
