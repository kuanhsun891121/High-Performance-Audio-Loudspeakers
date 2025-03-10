
# Circuit Diagram Explanation
The schematic diagram below illustrates the signal path and amplification stages of the TDA1519C-based audio amplifier system.


🧠 Key Sections
## Input Stage (AUX-IN / MIC-IN):

The circuit supports both AUX input (R14, R15, R11, C11) and MIC input (R1, C9, Q1).
The microphone signal passes through a pre-amplification stage using a transistor amplifier, providing sufficient gain before feeding into the main amplifier.

## Gain Control Section

Gain is controlled using VR1 (variable resistor) along with biasing resistors (R3, R4, R8) and coupling capacitors (C6, C8).
The pre-processed signal is then sent to the amplifier IC.

## Power Amplifier 

The main amplification is handled by TDA1519C, a dual-channel audio power amplifier.
Signals are input through pins 1 and 9, while output is provided at SP+ and SP- (pins 4 and 6).
Additional components (C1–C5) serve as decoupling, bypass, and output filtering capacitors to stabilize power and enhance sound quality.
## Power Supply and Filtering
  
The circuit uses a 12V DC power supply, with capacitors C1, C2, C3, C4 for filtering ripple and stabilizing voltage.
C10 and C11 provide high-frequency noise filtering on input signals.
