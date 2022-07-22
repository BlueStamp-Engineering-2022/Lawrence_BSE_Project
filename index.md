# Custom Audio Synthesizer
This device utilizes buttons and potentiometers to send digital and analog inputs to an arduino. The arduino is programmed to convert these inputs into MIDI(Musical Instrument Digital Interface) signals. Your computer is then able to interpret these signals using your favorite audio software.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Lawrence | Cupertino High School | Electrical Engineering | Incoming Sophomore

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLWnYIfiMCrzhEexiC3B2EEer0BGVDTiks_QQd0Zyyy9Psq_ozUOEsBgSgJYAcShyENWfNOVctX_ONRWoCizGWyJKkC3TQB5bZFOFmDW8A2pqlZgV1c52TIlhpcvTy-RLyLoDBID8I_iC3Sy7uwdK8s=w1230-h1640-no?authuser=0)
  
# Final Milestone
My final milestone was the modification of using a slide potentiometer to change the octave of the notes played. This was a pretty simple modification but I had been struggling with it for a while due to a syntax error. I learned that I could not write conditionals like math equations(Ex. if(0 <= x < 250)) in arduino because (0 <= x) would be interpreted as a boolean with value 1 or 0, which are both less than 250, and therefore the if statement would always be true. This type of syntax worked in other progamming languages, but I was unaware that it didn't work in arduino. It was a struggle to solve the issue without knowing that information, but finally working the problem out was very satisfying.

[![Final Milestone](https://img.youtube.com/vi/tV5cgRTGr7Q/maxresdefault.jpg )](https://www.youtube.com/watch?v=tV5cgRTGr7Q "Final Milestone")

# Second Milestone
My second milsetone was finishing the hardware portion of my project, which consisted of constructing the box and wiring all the components to a breadboard. To accomplish this, I had to learn how to use a handheld drill and a file in order to create all the necessary holes in the box. Afterwards, I soldered wires to all the buttons and potentiometers and then secured them onto the box. I really enjoyed this process, as it was the first time I had worked on hardware after only working on software for 2 weeks. However, the next step of wiring all the components to the breadboard and fitting everyhting inside the box was quite challenging.

[![Second Milestone](https://img.youtube.com/vi/sewwkrGGfmg/maxresdefault.jpg)](https://www.youtube.com/watch?v=sewwkrGGfmg "Second Milestone")

# First Milestone
My first milestone was setting a up a functional circuit with 1 button and multiple potentiometers. In order to accomplish this, I had to find a new program that was compatible with my arduino model and make many edits so it could support multiple potentiometers, since the program provided in the project instructions was outdated. I learned how to program with the arduino programming language, how to execute functions in MIDI(Musicanl Instrument Digital Interface), and how to create a circuit with jumper wires and a breadboard. Making the necessary edits to the code was certainly challenging, as the original code performed a control change function whenever it detected a change from any analog pin, instead of designating specific commands for each analog pin. It was fun testing out the verious MIDI controls and producing my first sound, though.

[![First Milestone](https://img.youtube.com/vi/HvIb2GSrOdo/maxresdefault.jpg)](https://www.youtube.com/watch?v=HvIb2GSrOdo "First Milestone")

# Starter Project
My starter project was Simon Says. In order to complete this project, I learned soldering as well as the functions of each part to ensure that I constructed it correctly. For example, I needed to know that LEDs had positive and negative polarity in order to place them accordingly. Soldering the components, especially the microcontroller, was somewhat challenging considering it was my first day. However, it was definitely satisfying to do the final assembly and see the project finally come together.

[![Starter Project](https://img.youtube.com/vi/-b-rGRhXx58/maxresdefault.jpg)](https://www.youtube.com/watch?v=-b-rGRhXx58 "Starter Project")

# Circuit Diagram
Below is a circuit diagram for the circuitry involved in my project. Note that I used the arduino micro as my arduino of choice and only had 2 knob potentiomerers instead of 4.

[![Circuit Diagram](https://raw.githubusercontent.com/BlueStamp-Engineering-2022/Lawrence_BSE_Project/gh-pages/MIDI%20Controller%20Circuit%20Diagram.png)]
