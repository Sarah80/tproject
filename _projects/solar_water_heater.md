---
permalink: /projects/Solar-Water-Heater/

title: Solar Water Heater
date: 2019-07-07
layout: page
id: 0008
guid: http://terlamonte.pt/?page_id=0008
---

### The goal: build a solar shower for our guest rooms

### What does it consist of?

- Solar panels, built from black PET-tube under a glass plate
- Heat storage to keep warm water over night
- Control system to have a consistent temperature coming out of the warm water tap

### Possible problems

- Water doesn't get hot enough
- Significant temperature differences in summer and winter
- Water gets too hot (damage to tank or tubes?)
- Too high maintenance
- Legionella

### Useful resources

- [Water system calculations](https://www.engineeringtoolbox.com/hot-water-systems-t_29.html)
- [Hot water system design](https://www.engineeringtoolbox.com/design-hot-water-system-d_92.html)

### Theory and calculations

#### Efficiency:
We have to calculate the power output of our panel. The average irradiance of the sun on the earth surface is 1000 W/m2. Our panel has ca. 0.5 m2, the solar irradiance for this area is 500 W. We know that we can get a 24° temperature difference (water enters at 26°C and is heated to 40°C) with our panel with a throughput of 10 l/h. We calculate the volume of the panel with 3.53-10^-4 m3. Now, at our throughput speed we exchange the water in the panel at 7.85x10^-3 times/s. To heat one panel full of water we need 2.958x10^4 J. Combining these values we find that our panel has a power output of 232 J/s or 232 W. This gives an efficiency of 33.4 %.

### Panel 1 prototype

- Size 0.61 x 102 m
- Tube diameter 16 mm
- Tube length 16 m

### Panel 2 prototype

- Size 0.61 x 102 m
- Tube diameter (internal) 3 mm
- Tube length 50 m

### Results

The water temperature at the tap is 20°C and arrives at the panel at 26°C. Which is strange, as it appears to heat more inside the garden hose than inside of the panel.

| Weather & Panels       | Throughput        | Temp.  |
| --- | --- | --- |
| cloudy, panel 1 & 2     | 20 l/h | 39°C |
| cloudy, panel 1 & 2     | 10 l/h  | 39.8°C |
| sun, 100m tube + panel 1 & 2 | 55 l/h  | 50°C |

### Considerations for the final system

- Needs a thermostatic mixer to arrive at the tap with consistent temperature
- Probably will need about 500 l per day when we have guests
- Safety valve and expansion baloon for the hot water tank
- Solar pump to fill the cold water tank



