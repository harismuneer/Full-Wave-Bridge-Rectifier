# ✨ Full-Wave-Bridge-Rectifier

<a href="https://github.com/harismuneer"><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=harismuneer&style=flat-square" width="125"/></a>
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/harismuneer/Full-Wave-Bridge-Rectifier.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/harismuneer/Full-Wave-Bridge-Rectifier/fork)
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

<hr>

## Author
You can get in touch with me on my LinkedIn Profile: [![LinkedIn Link](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=linkedin&longCache=true&style=social&label=Follow)](https://www.linkedin.com/in/harismuneer)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/harismuneer)

If you liked the repo then kindly support it by giving it a star ⭐ and share in your circles so more people can benefit from the effort.


## Contributions Welcome
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Full-Wave-Bridge-Rectifier.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Full-Wave-Bridge-Rectifier/issues)

If you find any bugs, have suggestions, or face issues:

- Open an Issue in the Issues Tab to discuss them.
- Submit a Pull Request to propose fixes or improvements.
- Review Pull Requests from other contributors to help maintain the project's quality and progress.

This project thrives on community collaboration! Members are encouraged to take the initiative, support one another, and actively engage in all aspects of the project. Whether it’s debugging, fixing issues, or brainstorming new ideas, your contributions are what keep this project moving forward.

With modern AI tools like ChatGPT, solving challenges and contributing effectively is easier than ever. Let’s work together to make this project the best it can be! 🚀

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](../master/LICENSE)

Copyright (c) 2018-present, harismuneer                                                        

<!-- PROFILE_INTRO_START -->

<hr>

<h1> <a href="#"><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" alt="Waving hand" width="28"></a>
Hey there, I'm <a href="https://www.linkedin.com/in/harismuneer/">Haris Muneer</a> 👨🏻‍💻
</h1>


<a href="https://github.com/harismuneer"><img src="https://img.shields.io/github/stars/harismuneer" alt="Total Github Stars"></a>
<a href="https://github.com/harismuneer?tab=followers"><img src="https://img.shields.io/github/followers/harismuneer" alt="Total Github Followers"></a>

<hr>

- <b>🕸️ Founder of Cyfy Labs:</b> At <a href="https://www.cyfylabs.com">Cyfy Labs</a>, we provide advanced social media scraping tools that enable businesses, researchers, and marketers to extract actionable insights from platforms like Facebook, Instagram, and X (formerly Twitter). Our tools are designed for use cases such as lead generation, market research, social listening, and more. Learn more at <a href="https://www.cyfylabs.com">www.cyfylabs.com</a>

- <b>🌟 Open Source Advocate:</b> Passionate about making technology accessible, I’ve developed and open-sourced several software projects for web, mobile, desktop, and AI on my <a href="https://github.com/harismuneer">GitHub profile</a>. These projects have been used by thousands of learners worldwide to enhance their skills and knowledge.

- <b>📫 How to Reach Me:</b> To learn more about my skills and work, visit my <a href="https://www.linkedin.com/in/harismuneer">LinkedIn profile</a>. For collaboration or inquiries, feel free to reach out via <a href="mailto:haris.muneer5@gmail.com">email</a>. For Cyfy Labs related queries, please contact us through our <a href="https://www.cyfylabs.com">company website</a>.

<hr>

<h2 align="left">🤝 Follow my journey</h2>
<p align="left">
  <a href="https://www.linkedin.com/in/harismuneer"><img title="Follow Haris Muneer on LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/harismuneer"><img title="Follow Haris Muneer on GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.youtube.com/@haris_muneer?sub_confirmation=1"><img title="Subscribe on YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a> 
   <a href="https://x.com/harismuneer99"><img title="Follow Haris Muneer on Twitter(X)" src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/></a>
 <a href="https://www.facebook.com/harism99"><img title="Follow Haris Muneer on Facebook" src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/></a>
   <a href="https://www.instagram.com/harismuneer99"><img title="Follow Haris Muneer on Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
  <a href="https://www.tiktok.com/@harismuneer99"><img title="Follow Haris Muneer on TikTok" src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white"/></a> 
  <a href="mailto:haris.muneer5@gmail.com"><img title="Email" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>



<!-- PROFILE_INTRO_END -->


