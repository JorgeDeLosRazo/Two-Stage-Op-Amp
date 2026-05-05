# Two-Stage Mini Op-Amp
In my CE-Amplifier repository I designed a Common-Emitter Amplifier using a BJT. Single-transistor amplifiers do a good job at amplifying input signals, however, there are two major isues with them:
  * Single-transistor amplifiers require too many passive components for bypassing and biasing, which is undesirable for ICs.
  * Single-transistor amplifiers, amplify their input signal as well as any noise that accompanies it.

In this repository I explore the differential amplifier, which solves (at least in theory) the two issues above. The end goal is to design a tw-stage operational amplifier using BJTs. However, since this repo is mainly for learning, not direct design specifications will be followed---the goal will simply to design an operational amplifier with a high gain, low high input resistance, and low output resistance.

## Components Used
Since a differential amplifier requires that the two transistors used are identical, using discrete transistor components would pose a lot of problems. Which is why a single chip with a four transistor array will be used:
* NPN Four Transistor Array Chip: MQP3904
* PNP Four Transistor Array Chip: MQP2907

## Differential Amplifier

