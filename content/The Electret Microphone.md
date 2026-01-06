## What it is

A [[Electret Microphone|electret microphone]] is a type of [[Condenser Microphone|condenser microphone]] that converts [[Sound Waves|sound waves]] into a very small electrical signal. 

The [[Electret|electret]] [[Microphone Capsule|microphone capsule]] contains:
- A thin membrane called a  [[Diaphragm|diaphragm]]
- A fixed [[Backplate|backplate]]
- An electret material

## How it works

The diaphragm vibrates to the changes of sound waves, which causes the distance between the diaphragm and the fixed backplate to change. These two materials act as a [[Capacitor|capacitor]], while the change in the distance changes the [[Capacitance|capacitance]]. This causes a tiny [[Voltage|voltage]] variation that captures sound waves. The signal produced is extremely small, so it needs amplification before it can be used.
<p align="center">
  <img src="media/Diagrams/Electret Condenser Microphone.png" width="400">
</p>

## Why a [[JFET]] is used

The signal coming from an electret capsule has very high [[Impedance|impedance]]. This means if you connect the electret microphone to most circuits, the electric signal is too tiny and unusable. The JFET is used to amplify the signal so that it can be used or recorded. 


## Why [[Biasing|biasing]] matters

An [[Electret Microphone|electret microphone]] requires biasing because the JFET needs the right voltage to amplify the electric signal properly and the [[Microphone Capsule|microphone capsule]] needs power to generate a signal properly in response to sound. If the bias is too low, there will be no electric signal. If the bias is too high, there will be distortion to the signal. If the biasing is unstable, there will be a lot of noise.

<p align="center">
  <img src="media/Diagrams/JFET Datasheet.png" width="400">
</p>


## Basically...

[[Electret]] [[Condenser Microphone|condenser microphones]] are look simple on the outside but more intricate than you would think.

<p align="center">
  <img src="media/Diagrams/Electret Condenser Mini Microphone.png" width="400">
</p>
If you want to follow along with the DIY step by step tutorial for a electret condenser microphone, here it is: <a href="Step By Step Process/Step 00.md">Click Me!</a>



