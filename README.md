# BJTlogiggateproject
aims to create faster and more energy efficient BJT logic gates and tries to maintain itself cooler than 30°C



IEA-PC: Inverted Electric Archithecture to Positive Conversion



about it:
IEA-PC is a BJT based family logic, it works by using negative logic and converts the negative outputs to positive ones.
It was born for personal need of reliable and space efficient logic gates able to work in a circuit (uses NPN and PNP transistors to work, PNP transistors will be used in future, currently only NPN transistors are being used)
and to be fast and to produce less heat possible as to not generate noise created by temperature, it is independent from RTL or TTL, ECL or CML, where static power usage is high, 
while in IEA-PC is low thanks to it requiring external inputs to open paths for electrons.
Uses natural flow of electricity instead of forcing it through the transistors, lowering the generated tension and heat produced by the circuit.



tests made:
I personally tested a full adder with IEA-PC logic gates at 2-3Hz for 20s on a dusty breadboard near a phone (these conditions are a stress test for the circuit, I prefer to run the circuit in harsh conditions to verify reliability),
the circuit did not fail, it maintained its integrity and boolean logic, showing functional logic gates in real life testing
rather than simulated only.
LTspice (Windows 10 64bit) is currently being used to test gates at faster speeds reaching MHz.



project structure:
physical tests at lower Hz: on breadboard


simulated higher speeds at GHz: LTspice (Windows10 64-bit)


LICENSE: Legal protections under the CERN Open Hardware License


goals (Hack club| AMD Blueprint):
phase 1: achieve higher MHz speeds on LTspice with effective low power usage with low temperature increase.


phase 2: design a high-speed PCB to verify real world capacity at max 10MHz. (Initial tests will be run initially at KHz and only after at MHz)



LICENSE clarifications:
This project is licensed under the CERN Open Hardware License-Strongly Reciprocal (CERN-OHL-S).
Read the LICENSE before doing or sharing anything related to this project.
