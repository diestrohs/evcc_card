# EVCC Card
Home Assistant EVCC Card for EVCC Integration near original WebGUI of EVCC

I find the EVCC WebGUI very well designed. After a developer took the effort to implement an integration for EVCC, I set myself the goal of implementing the EVCC WebGUI as a card in Home Assistant using existing tools from many developers.
## Disclaimer
Please note that this card was created for personal use and is made available for free use. However, I do not guarantee that it is free of errors. Use this card at your own risk.
## Note
This implementation is in a very early development stage and currently only covers a small fraction of the original EVCC WebGUI.
## Requirements
- A running and configured EVCC instance in your network
- Home Assistant with HACS
- Installation of the evcc integration other hacs
- Installation of the following cards other hacs:
  - Vertical Stack In Card
  - Mushroom
  - Sankey Chart Card
## Info
The implementation consists of two main cards:
- Energy card
- Charging point and the vehicle connected to it
