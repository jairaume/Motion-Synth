# Motion-Synth
Motion Synth is a pure data patch that lets you control a *synthesizer* and a *sample launcher* with the movement of your phone.

<img src="https://user-images.githubusercontent.com/60481472/115005905-9d8eae00-9ea8-11eb-859d-1af9154e6c6a.png" width="500">

---

## Install and configuration : 
- **Clone** the repository onto your computer or download the archive 
  
- **Launch** the app *oscHook* on your phone :
  - **Host IP/port settings** -> enter the *ip adress* of the computer on which the patch is running and specify *port* (default is 9001)
  - **Advanced settings** -> set sending frequency to *high*
  - Tick the *Send OSC* box in **orientation** and **linear acceleration** settings
  - Tap on the **round Hook button** at the bottom to begin sending osc messages   
    
- **Launch** main.pd with *Purr-Data* (Pd-l2ork 2)
- **Enjoy** ! :+1: 

---

## Features : 
- **FM Synthesizer** :  
  - **Modulating frequency slider** : controlled by the *orientation* of the phone.    
  - **ADSR vertical sliders** : basic *envelope* tweaking.
  - **Orientation/Normal switch** : switch between normal *ADSR* envelope and *orientation recorded* envelope.
  - **Record envelope button** : lets you *record*, for 5 seconds, the *envelope* with the *orientation* of the phone.

- **Sample launcher** (x3) : 
  - **Main button** : launchs sound when *clicked* or when the phone detects a *sudden acceleration* on the corresponding axis (x,y,z).
  - **File explorer button** : opens a *file explorer* to replace the sound played (default sounds are drums sounds).

---

CIR²-ISEN (2021)
