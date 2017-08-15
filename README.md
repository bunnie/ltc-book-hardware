# ltc-book-hardware

PCB design files for the LTC Book

A basic boost regulator to take 3-cell AA to 5V.

Max design output is 500mA. In practice, designs should stay
clear of this limit, or else as the battery runs low the system
will oscillate between a low-battery power down mode and powered
on as the battery relaxes into a deep-discharge state.

Anticipated average draw is ~20-30mA, maybe 200mA peak with RGB tape;
not for use as a mobile phone charger.

Features low battery protection (to prevent deep-discharge & damage of
NiMH batteries), wide operating range (supports both NiMH and alkaline
chemistries), reverse input voltage protection (so reverse battery
polarity doesn't blow up the circuit), reverse output current
protection (e.g. external voltage source connected to output of
boost), output ESD protection, and current limiting.



