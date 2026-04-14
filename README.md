<img width="1023" height="697" alt="Screenshot 2026-04-08 234225" src="https://github.com/user-attachments/assets/be92a60b-4568-4b50-9213-2c8516cdc291" />
<img width="1621" height="889" alt="Screenshot 2026-04-14 151807" src="https://github.com/user-attachments/assets/9f61089c-e588-466c-8f0c-970aaf9e9f1b" />
<img width="711" height="898" alt="Screenshot 2026-04-12 151147" src="https://github.com/user-attachments/assets/9271256d-ad3e-4df7-a860-8027860c1b0f" />
<img width="423" height="559" alt="Screenshot 2026-04-12 151227" src="https://github.com/user-attachments/assets/5293b328-d4da-460d-aa7f-ed95c7e3778b" />
<img width="1289" height="869" alt="image" src="https://github.com/user-attachments/assets/a197bd3a-1290-4845-8da1-0be1afe9ef0c" />


# QuackyGrammer ~ The portable, Type C PIC Programmer

Recently, I rediscovered a collection of PIC Microcontrollers and was fascinated on how they work, programming them, and the simplicity of a REAL microcontroller. Before this, I was learning assembly through a previous project of mine, LindlesOS, so these microcontrollers were a great way of demonstrating the practicality of Assembly. I picked up a k150 from AliExpress, only to realise the drivers are impossible to find, setup and are mind-numbing to install...

This is what brought me to my project, I was wondering, how could I improve the programming of PIC Microcontrollers while making it portable, and simplistic. I stumbled upon the PICKIT 2 and learnt about the difference between ZIF and ISCP sockets, learning that ISCP was wayyy more accessible, and may be suitable for my project. After countless hours of planning, wondering, and researching I agreed on things to include in my project

- USB Type C Connector ~ Usually on programmers they use USB Type B because of it's constant power rather than being wired to power.
  
- PIC18F2550 ~ The heart and brains of the project. The K150 uses PIC16F628A but I wanted to add further programming capabilities and not include excess chips, like on the K150.
  
- Connector ~ The defining factor of the PICKIT 2 is the ability to plug about 5 wires into the microcontroller, and upload your code from a PICKIT application, which is exactly what I can replicate with this project, for even more accessibility.

Which brings me to my project, QuackyGrammer ✨

The QuackyGrammer is a USB Type C powered, portable, ISCP connecting PIC Programmer, powered by the mighty PIC18F2550. The Programmer is aimed to make PIC Programming easy with a flawless, PICKIT 2 inspired connecting system, and a very portable USB Type C connection port. The duck theme is inspired by a new nickname I recently acquired, Quackery, and as you can tell by my other projects, I stick with this theme now.

The Bill of Materials is in BOM.csv

The firmware for this project, is uploading the PK2V023200.hex into the PIC18F2550 with the PICKITV2 programmer software.
