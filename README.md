HauntedPumpkin
==============
An arduino-controlled haunted pumpkin. The pumpking will normally flicker a yellow LED, simulating a candle flame. When someone approaches the ultrasonic sensor reads the proximity and the pumpkin turns red and says "I see you" in a spooky voice.

Inspired by Matt Richardson's Pimp Your Pumpkin project: https://github.com/mrichardson23/PimpYourPumpkin

Tutorial can be found here: http://www.shatteredhaven.com/2012/10/1319365-haunted-pumpkin-part-2.html

**Overview:** 
An arduino sketch that senses someone approaching and changes from simulated candle flicker to red & plays a scary voice that says "I see you."

**Files Used:**
- damellis-PCM library from: http://hlt.media.mit.edu/?p=1963 (Rename this to PCM)
- EncodeAudio-windows from: http://hlt.media.mit.edu/?p=1963
- ultrasonic library from: http://letsmakerobots.com/node/30209 -- NOTE: The library included in this github has been updated to for arduino 1.0
- HauntedPumpkin.ino
- HauntedPumpkinSketchwithaudiojack.fzz - use Fritzing to open

**Materials Used**
- Arduino Uno 
- breadboard (preferably mini-breadboard)
- prototyping shield (optional)
- HC-SR04 Ultrasonic Sensor 
- one (1) orange LED (or yellow - which is all I could find)
- one (1) red LED
- one (1) 3.5mm audio jack
- two (2) 200 Ohm resistors (or whatever would be appropriate for your LED)
- size M coaxial DC power plug
- snap connector
- battery holder
- wire
- electrical tape (optional to cover power LED on arduino board)
- pumpkin
- gauze (optional)
- metal can (optional to use as base to mount your arduino)
