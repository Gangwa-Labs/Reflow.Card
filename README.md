# Reflow.Card
Reflow hotplate for soldering pcbs that uses USB-PD to deliver 100W to the heater board. This design uses two different PCBs: a heater control PCB and a heater PCB. This allows the heater boards to be consumable and swapped out if they become damaged without needing to replace the entire control PCB. This project was designed for the Hackaday business card 2024 challenge. Because there is no height limit for the challenge this design stacks both PCBs on top of each other with standoffs to be compliant.

Powered by an esp32-c3 Wroom-02 a web portal will publish the live temperature readings and allow users to upload new reflow curves. On the physical PCB there will be 2 buttons for interfacing and an mini 0.91" OLED display to know the live temperature and control.

I would like to give a huge shoutout to @Aylo6061 and his PCBHotplate Project that was the baseline for a ton of this project https://github.com/Aylo6061/PCBHotplate
