# Two-Stage Mini Op-Amp
In my CE-Amplifier repository I designed a Common-Emitter Amplifier using a BJT. Single-transistor amplifiers do a good job at amplifying input signals, however, there are two major isues with them:
  * Single-transistor amplifiers require too many passive components for bypassing and biasing, which is undesirable for ICs.
  * Single-transistor amplifiers, amplify their input signal as well as any noise that accompanies it.

In this repository I explore the differential amplifier, which solves (at least in theory) the two issues above. Along the way 

## Components Used
Two four-transistor array chips were used:
- npn: MQP3904
- pnp: MQP2907

## Differential Amplifier

