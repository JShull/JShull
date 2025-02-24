### Hey 👋, [I'm John](https://youtu.be/rY-Vs6r7Q8E)!

<a href="https://www.linkedin.com/in/xr-johnshull/">
  <img align="left" alt="John's LinkdeIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>
<a href="https://fuzzphyte.com">
  <img align="left" alt="Personal Website" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/html5.svg" />
</a>
<a href="https://twitter.com/TheJohnnyFuzz">
  <img align="left" alt="John's Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/twitter.svg" />
</a>

<br />
<br />

Hi there, I'm **John Shull**, a **Lead Project Scientist** :rocket: at the Virginia Modeling Analysis Simulation Center ([VMASC](https://vmasc.org/)🌍) and an **Adjunct Instructor** with the [Game Studies & Design Program](https://www.odu.edu/academics/programs/undergraduate/game-studies-design) :space_invader: at [ODU](https://www.odu.edu) 🚀!  Currently, I'm working with some amazing students on projects that deal with large agent based simulations, working towards funded projects that deal with mixed reality (XR), and using Game Engines to do all sorts of fun things! When I'm not tinkering about, I'm probably learning life lessons from my amazing significant other :heart: or perhaps I'm on XBox :video_game: playing with my core group trying to break EA physics junk 😉 under the handle, **The JohnnyFuzz**, or maybe just jamming to some [Above & Beyond](https://music.apple.com/us/artist/above-beyond/20318188), and in some circumstances hanging out with the other Fuzz's... :eyes:

  <img align="right" alt="GIF" src="https://media.giphy.com/media/szAb0eLo0zWBpFdgpz/giphy.gif" />

**Personal Stuffs:**

- 👨🏽‍💻 I’m currently a Lead Project Scientist at [OERI](https://oduinnovate.org/) formally [VMASC](https://www.vmasc.org/) working on :shell:Oysters, XR, & Education!
- 🌱 I’m currently learning how to be a better educator
- 🤔 My interests are using XR for everyday people
- 💼 I’m swapping PhD programs to Instructional Design & Technology... I think...
- 💬 Ask me about anything, I am happy to help
- 📫 Please email via jshull@odu.edu to reach me
- 😄 Pronouns: He/Him
- 📝 See my [Curriculum Vitae](https://github.com/JShull/JShull/blob/main/JShull_CV.pdf) (updated 2024) to get more info
- ⚡ Fun fact: When I was in highschool, I helped some internet friends create [DayOfDefeat](https://www.dayofdefeat.com/)! You won't find my name in the credits but you might find my dad **[FuzzDad](https://dayofdefeat.fandom.com/wiki/Glider)**
- "...nothing lasts, nothing is finished, and nothing is perfect." - *Powell, Richard R. (2004). Wabi Sabi Simple. Adams Media. ISBN 1-59337-178-0*

**Unity Package Stuff:**

The repositories below are in the public domain under a dual license and are based on years of me using Unity and coming up with my own custom libraries. They might not be helpful but they sure as hell have saved me a ton of effort! In most cases these repositories rely on the FP_Utility and a lot of them use a scriptable object pipeline that's built around a 'Data Factory' model via FP_Data.cs. They all are formatted to work directly with Unity's Package Manager (UPM) System and can be brought in using the [Git URL approach via UPM](https://docs.unity3d.com/Manual/upm-ui-giturl.html).

- [FuzzPhyte Utility](https://github.com/JShull/FP_Utility) a Utility package that is considered core to all FuzzPhyte code
- [FuzzPhyte EDU Utility](https://github.com/JShull/FP_Utility_EDU) an extension of Utility that has data objects related to VA state requirements and FP_Vocab
- [FuzzPhyte XR](https://github.com/JShull/FP_XR) a library that provides some high level abstraction for me to write generic XR code that has zero dependencies on OVR or Unity XR. You use this package by deriving classes from it which then have the references as needed by your deployment hardware. For example things like Surface Lock, Label Tags, World Check, World Item, check alignment of transforms, and a beta of a socket system (not running yet) that mimics how OVR does attachable sockets.
- [FuzzPhyte XR OVR](https://github.com/JShull/FP_XR_OVR) an extension of XR that does have dependencies on OVR. A higher level set of scripts that interact with OVR and extend OVR for other Unity Events.
- [FuzzPhyte Event](https://github.com/JShull/FP_Event) a simple event system that utilizes a priority queue. Abstract set of classes that require an FPEVent derived data object. Other libraries use this FP_Event for misc. things as needed
- [FuzzPhyte Dialogue](https://github.com/JShull/FP_Dialogue) a simple dialogue chaining system that uses the UI, Utility, and Utilty EDU packages to combine a way to generate a sequence/list of dialogues that have text, audio, and object references. Allows for up to 4 user different prompt responses all driven by an elaborate scriptable object set of data objects. There is no graph representation but there is a way to link Dialogues to other Dialogues giving you a way to have simple graph 'logic'. Originally written for the UIToolkit but also supports World Canvas operation with standard Unity UI elements.
- [FuzzPhyte Ray](https://github.com/JShull/FP_Ray) a wrapper that sits ontop of Unity Raycast and gives you a way to easily drop in multiple different 3D and 2D rays all from the same data objects. A lot of setup but once you generate your data objects via scriptable objects super easy to modify, adjust, and utilize. A sort of 'one raycaster' to rule them all. 

**Student Stuffs:**

I constantly am working with different individuals through my work and I want to recognize a few students that I'm sure will go on to greatness!:fire:
- Jykeim was the first student I had the privilege of working with! Jykeim was working 1-off and 1-on semesters from 2019 through his graduation in 2022! He graduated with honors from the [Cyber Security Program](https://www.odu.edu/academics/programs/undergraduate/cybersecurity)! :partying_face: Jykeim now works on secret stuff :boat: and :gun: in Dahlgren VA!
- [Jared](https://github.com/BaconStrps) started working with me in the summer of 2022, finished his associated at [TCC](https://www.tcc.edu/programs/transfer/old-dominion-university/) and now is enrolled at ODU under the [Computer Engineering Program](https://www.odu.edu/academics/programs/undergraduate/computer-engineering). Jared is a fantastic student and has already excelled in multiple projects - I cannot wait to see where Jared goes once he finishes at ODU! 🎉 
- [Nate](https://github.com/nhallen272) started working with me in the summer of 2023, he will be graduating from the [Cyber Security Program](https://www.odu.edu/academics/programs/undergraduate/cybersecurity) in the fall of 2023!
- [Avantika](https://github.com/AvantikaMittapally53) started working with me the summer of 2023 and she will be completing her [Masters in Computer Science](https://www.odu.edu/academics/programs/masters/computer-science) at ODU in the fall of 2023!
- [Catherine](https://github.com/catowens) worked with me in the summer of 2022 as a collaboration effort with [VIMS](https://www.vims.edu/). She is currently enrolled in the [Industrial and Interaction Design Program at Syracuse University](https://vpa.syr.edu/academics/design/programs/industrial-interaction-design-bid/) and her [2022 summer project portfolio can be found here](https://catowensdesign.myportfolio.com/vims-x-odu-vmasc-internship) :fire:
- Rachel worked with me 2021 as a graduate student on the [Modeling Religious Change Project](https://mindandculture.org/projects/modeling-social-systems/modeling-religious-change/). She currently has her [Masters in Applied Linguistics](https://www.odu.edu/academics/programs/masters/applied-linguistics) 

**Software Stuffs:**  

<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/csharp.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/arduino.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/python.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/meta.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/markdown.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/unity.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/git.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/azuredevops.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/amazondynamodb.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/linux.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/ios.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/microsoft.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/autodesk.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/adobeillustrator.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/visualstudiocode.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/apachekafka.svg"></code>
<code><img height="32" src="https://cdn.jsdelivr.net/npm/simple-icons@7.7.0/icons/steam.svg"></code>

⭐️ From [JShull](https://github.com/JShull)

![John's GitHub Stats](https://github.com/JShull/github-stats/blob/master/generated/overview.svg#gh-dark-mode-only)
![John's GitHub Language](https://github.com/JShull/github-stats/blob/master/generated/languages.svg#gh-dark-mode-only)

<a href="https://lumalabs.ai/embed/835864e9-1dab-4436-a53f-f3e4b50d65a3?mode=slf&background=%230091ff&color=%23FFFFFF&showTitle=true&loadBg=true&logoPosition=bottom-left&infoPosition=bottom-right&cinematicVideo=undefined&showMenu=false"><img align="left" alt="Custom Arcade Cabinet Built around a Laptop" height="300px" src="https://github.com/JShull/JShull/blob/main/SpaceJunk.JPG"/></a>
<a href="https://lumalabs.ai/embed/3704305b-d146-4701-b25d-c0f3933336e8?mode=sparkles&background=%231abaff&color=%23000000&showTitle=true&loadBg=true&logoPosition=bottom-left&infoPosition=bottom-right&cinematicVideo=undefined&showMenu=false"><img align="left" alt="OERI Willoughby Spit Boat Ramp Research Location" height="300px" src="https://github.com/JShull/JShull/blob/main/GitHubLuma_Willoughby.PNG"/></a>

<br />
<br />

