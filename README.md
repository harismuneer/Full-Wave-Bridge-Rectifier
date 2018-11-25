# ✨ Full-Wave-Bridge-Rectifier

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/harismuneer/Full-Wave-Bridge-Rectifier.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/harismuneer/Full-Wave-Bridge-Rectifier/fork)
[![Build Status](https://semaphoreapp.com/api/v1/projects/d4cca506-99be-44d2-b19e-176f36ec8cf1/128505/badge.svg)](#)
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Full-Wave-Bridge-Rectifier.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Full-Wave-Bridge-Rectifier/issues)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)


## How to Run:
Install MATLAB and just open the "FWBridgeRectifier.slx"

## Introduction:

### What is a Bridge Rectifier?
A bridge rectifier is an arrangement of four diodes in a bridge circuit configuration which provides the same output polarity for either input polarity. It is used for converting an alternating current (AC) input into a direct current (DC) output.

**Full Wave Bridge Rectifier**
![Image of FW Bridge Rectifier](../master/images/main.PNG) 



The four diodes labeled D1 to D4 are arranged in “series pairs” with only two diodes conducting current during each half cycle.
Working:

## 1) The Positive Half-Cycle:
During the positive half cycle of the supply, diodes D1 and D2 conduct in series while diodes D3 and D4 are reverse biased and the current flows through the load as shown below.

**Positive Half Cycle**
![Image of Positive Half Cycle](../master/images/p.png) 


## 2) The Negative Half-Cycle:
During the negative half cycle of the supply, diodes D3 and D4 conduct in series, but diodes D1 and D2 switch “OFF” as they are now reverse biased. The current is flowing through the load in the same direction as before.
 
**Negative Half Cycle**
![Image of Negative Half Cycle](../master/images/n.png) 




## Conclusion:
 As the current flowing through the load is unidirectional, so the voltage developed across the load is also unidirectional. Hence the AC voltage signal has been rectified to a uni-directional DC voltage signal.




## Circuit Diagram of Full Wave Bridge Rectifier (MATLAB Implementation): 

**Design on MATLAB**
![Matlab Implementation of FWBR](../master/images/m.png) 
                  

                  
## Design Detail:

* AC Voltage Source used to generate Sinusoidal wave.
* Four diodes for rectification purposes 
* During Positive Half Cycle, diode 4 and 3 would be on.
* During Negative Half Cycle, diode 2 and 1 would be on.
* A load resistance of any value. 
* Then a voltage sensor to sense the voltage.
* After that a PS-Simulink Convertor which converts the input Physical Signal to a unit less Simulink output signal.
* After that Scope is used to obtain the output waveform. (Graph)


## Graphs:

**Input Waveform (AC)**

![Input Waveform](../master/images/i.png) 


**Output Waveform (DC)**    

![Output Waveform](../master/images/o.png) 


-------------------------------
## Author
You can get in touch with me on my LinkedIn Profile: [![LinkedIn Link](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect
)](https://www.linkedin.com/in/harismuneer)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/harismuneer)

If you liked the repo then kindly support it by giving it a star ⭐!

## Contributions Welcome
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](#)

If you find any bug in the code or have any improvements in mind then feel free to generate a pull request.

## Issues
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Full-Wave-Bridge-Rectifier.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Full-Wave-Bridge-Rectifier/issues)

If you face any issue, you can create a new issue in the Issues Tab and I will be glad to help you out.

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](../master/LICENSE)

Copyright (c) 2018-present, harismuneer                                                        
