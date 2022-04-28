# KSTAR tokamak simulator
- KSTAR is a tokamak (donut-shaped nuclear fusion device) located in Daejeon, South Korea.
- This repository provides a tokamak simulation tool with LSTM-based neural network.

# Installation
- You can install by
```
git clone https://github.com/Jaemin-Seo-0614/KSTAR_tokamak_simulator.git
cd KSTAR_tokamak_simulator
```

# Try it out
- Open the GUI by typing below. It might take a bit depending on your environment.
```
python kstar_simulator_v0.py
```
<p align="center">
  <img src="https://user-images.githubusercontent.com/46472432/165520027-c4f79698-a816-49a3-8e75-fd44985ad95c.png">
</p>

- Slide the toggles in the left side and see the fusion plasma evolution in the right side.
<p align="center">
  <img src="https://user-images.githubusercontent.com/46472432/165654530-c8230a8c-e9a7-4574-bae3-bab646bb61dc.gif">
</p>

- I hope you get insight with this tool!

# Note
- This simulation has been validated with many real discharges, and shows acceptable prediction.
<p align="center">
  <img src="https://user-images.githubusercontent.com/46472432/165522817-bc56771f-600b-4c7c-a9c3-4da0256bfe3e.png">
</p>

- But it does not always guarantee perfect predictions since it doesn't account for all factors.
- For example, the discharges #18672 and #22671 were conducted under almost the same setting, but showed quite different behaviors.
- In this case, the simulation shows quite a reasonable, average prediction as shown below.
<p align="center">
  <img src="https://user-images.githubusercontent.com/46472432/165521918-bd6969bf-31e0-4bf8-8848-f6ee6afeefaa.png">
</p>


# References
- Seo, Jaemin, et al. "Feedforward beta control in the KSTAR tokamak by deep reinforcement learning." Nuclear Fusion 61.10 (2021): 106010.
- Seo, Jaemin, et al. Nuclear Fusion (2022) (In review).
