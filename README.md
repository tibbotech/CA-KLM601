# KLM610 Burn-in Test

This is a little program we developed in-house to test our KLM610 devices. It keeps sending a command string over and over again, and then measures how long the KLM610 takes to respond. If the KLM610 doesn't respond on time, the burn-in test causes the buzzer to beep.

The program is also smart enough to re-establish the connection if it breaks.