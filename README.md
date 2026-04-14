# Hardware Hackathon

## Overview
For the second extracurricular activity, I participated in the 2026 Hardware Hackathon. This event went over 2 days, going from 4/11/26 to 4/12/26. I mainly spent time working on this project on the first day of the event as I was also participating in the individual National Cyber League challenge. The theme of the event was to create
something that "improved daily life." The project my team worked on was an alarm clock that you had to turn off via a QR code located in another room. This project improves daily life over time as it helps a person get into a routine easier. While it is more difficult at first, it can help the person be more productive throughout the day,
encouraging a healthy lifestyle. 

## Deliverable
This alarm clock was run on an ESP32 board running Arduino IDE that had a speaker connected to it via wires connected to the pins. At a predetermined time, the speaker would kick on and create a noise that could only be stopped by physically getting up and turning it off in another room. The QR code was another ESP32 board that
had a 3-D printed box to allow it to be hung on the wall or placed wherever the user wanted it to be. 

## Reflection

### Activity Description
My expectations for this event were very different than a regular hackathon type event such as the NCL Cyber Challenge. As the name shows, this event was much more centered around creating a piece of hardware. I do not have much familiarity with the hardware side of computing, but I was willing to learn and try my very best to 
understand the task at hand and help the people that knew what they were doing. 
### Technical Decisions
In this project, we created the alarm using 2 ESP32 boards, a speaker, and a box to hold  the QR code ESP32. We chose the ESP32 due to its built-in WiFi and Bluetooth capabilities as well as its compatibility with Arduino IDE, which made it accessible for rapid prototyping. The speaker was connected directly to the GPIO 
pins of the ESP32 to trigger  the alarm sound at a predetermined time. The QR code was used as the off switch, requiring the user to physically relocate to scan it and stop the alarm.
### Contributions
This was a team event. My specific contributions included wiring the hardware components together and contributing to the code running on the ESP32 boards. This gave me hands-on experience with embedded systems and low-level hardware interfacing, which connected directly to my Systems Programming coursework.
### Quality Assessment
Given the time I had available, as I was simultaneously participating in the NCL Individual Cyber Challenge, I feel I participated well and contributed meaningfully to the team. If I  were to redo this event, I would dedicate more time to the hardware side of the project and come in with a stronger foundation in embedded systems. 
Moving forward, I plan to continue developing my hardware skills through my ESP32 Secure Boot project to better prepare for future events like this.

### Proof of Participation
While unfortunatly I do not have the code I wrote, I do have a photo of me creating wires for my teammates to use in the project - or rather learning to make them. I also have a photo of the physical harware parts used to create the alarm.
![CPTS 427 - EA 2 SS1](https://github.com/user-attachments/assets/c2e1b7f4-ccbd-4fb4-86f6-ce3ec0840832)
![CPTS 427 - EA 2 SS2](https://github.com/user-attachments/assets/84cde7be-dcaa-4a29-b880-8f33b1328a7f)

