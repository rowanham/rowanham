## Rowan Hamilton


(...my first name is actually ["William"](https://en.wikipedia.org/wiki/William_Rowan_Hamilton)...)

<!--
**rowanham/rowanham** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### Projects


* The [BioScope]() - This is my new project - a device that reads EEG (and ECG and EMG and IMU). It is built on a crowd sourced project [from WallySci](wallysci.com), and I am starting with their example code. The hardware is based on an ESP32 WROOM board, with daughter boards hanging off it that provide the front-end electronics (really just two op-amps) for the signals coming off the body.
  + [target](https://github.com/rowanham/BioScopeTarget) - This is the repo for the firmware, which is entirely written in C++.
  + [host](https://github.com/rowanham/BioScopeHost) - This is the repo for the software, which is entirely written in Python.


* The [RoScope]() - This is my previous hobby/project. It's an oscilloscope made from a little ARM board. (A SparkFun Artemis board, which has an Ambiq Apollo3 SOC.)
  + [embedded](https://github.com/rowanham/RoScopeTarget) - This is the embedded code - just straight C code, thought it does use the [Ambiq Suite SDK]() and the Jasmine ([jsmn]()) package for lightweight JSON parsing.
  + [host](https://github.com/rowanham/RoScopeHost) - This is the host code - it is all Python, and like most Python uses a bazillion packages. (`pyserial`, `numpy`, `pysimplegui`, etc.)
  + I got this working with a reasonable set of first-pass features. However, the performance was *way* too slow. If I were to continue working on this project I would have to completely redesign the code. I have ideas on how I would do that, but I got distracted by the BioScope. (Which may end up using the RoScope in the future.)


----


(I need to create PDF versions of all the notebooks and put them in a separate folder with public access.)

* Documentation - all my [logbooks](https://bitbucket.org/RowanHamilton/logbooks/src/main/). (I like to use jupyter notebooks because they format nicely, they easily include figures, and they support (a subset of) LaTex.) They are all on [bitbucket](), so I will make them available when I have time. (Except for the work logbooks, those will have to wait until I am dead.)
    + On the BioScope:
        * The Host
        * The Target
        * Associated Hardware
    + On the RoScope:
        * The Host
        * The Target
        * Associated Hardware
    + Math & Physics:
        * For Angus...(College prep stuff for my son.)
            + [Dual Spaces...](https://bitbucket.org/RowanHamilton/angus/src/main/Dual%20Space%20for%20Angus.pdf)
            + [Linear Vector Spaces...](https://bitbucket.org/RowanHamilton/angus/src/main/LinearStuffForAngus.pdf)
    + Logbooks:
        * [Foretellai]()
        * [iCoin]()
        * [One Drop]()


----
