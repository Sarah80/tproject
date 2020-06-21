---
title: Solar Parabolic Cooker
layout: page
permalink: /projects/parabolic-solar-cooker/
---

### The goal: build a solar cooker to bake bread and cook food

### What does it consist of?

- Parabolic mirror (polished aluminium)
- Car window lift motors to move the structure
- Oven tube to hold the food
- Control system to track the sun, sensor-based, running on Arduino, with 6 relays and 4 LDRs

### Problems

- Sensor-based system gets confused with a partially cloudy sky
- Very high risk of wind damage (the mirror is basically a giant sail)

### Pictures of the system

<img src="https://user-images.githubusercontent.com/31141052/85223802-8c2a6180-b3bd-11ea-8fa5-23d57b70a2be.jpg">
<img src="https://user-images.githubusercontent.com/31141052/85223806-8f255200-b3bd-11ea-84a6-43e316f083e8.jpg">
<img src="https://user-images.githubusercontent.com/31141052/85223809-93516f80-b3bd-11ea-8155-91671c520643.jpg">
<img src="https://user-images.githubusercontent.com/31141052/85223812-977d8d00-b3bd-11ea-8d4d-0d7a9cb7c71f.jpg">
<img src="https://user-images.githubusercontent.com/31141052/85223814-9c424100-b3bd-11ea-8e8d-8d1f42e66a0b.jpg">
<img src="https://user-images.githubusercontent.com/31141052/85223816-a106f500-b3bd-11ea-8691-59637bac2774.jpg">
<img src="https://user-images.githubusercontent.com/31141052/85223821-a5cba900-b3bd-11ea-9c06-43c21ba69250.jpg">

### Useful resources

- The original model, the [Yaholnitsky Parabolic Cooker] (https://vignette.wikia.nocookie.net/solarcooking/images/e/ea/T-188_PARABOLIC_TROUGH_BAKING_DEVICE%2C_Ivan_Yaholnitsky%2C_1-17-17.pdf/revision/latest?cb=20170117224820)

### Conclusions

While we managed to bake bread and potatoes in the oven and reach a temperature of around 100°C, we find that the danger of the system being destroyed by wind is too high. Also, we think that using the calculated sun position is preferable to the sensor-based system. To address these issues, we are planning to develop a Fresnel mirror system.
