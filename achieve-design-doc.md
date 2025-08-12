How to achieve the different ideas.


Physical screen.

Research screens and which libraries they have for a ESP32 module.

Battery-driven

Research power needs for the system to decide battery format and mAh.

Modify code-wise.

Include way to access the USB-port of the ESP32 device. Smartest way is keeping the base port and using it for both charging and debugging.

Optimize battery-life

In the hardware, calculate power usage and minimize power loss through intelligent design of the circuits. Components should also be considered for power use when picked.

In the software, creative use of deepsleep and waking the system up only when needed is the way to start, but more time sohuld be spent researching it.

Rechargable via {Unknown}

Most likely will be via USB-port, but design that allows recharging of battery while also debugging the system must be considered. ( Transistors? Research!)

Non-self combusting.

Design device to decrease risks of catastrophic failure, triple check physical design and calculations.

3D-printed chassis.

Theoretically easy, but will take a few passes to get just right for feel, design and proportions.

Accelerometer.

Must include a accelerometer to allow the device to sense it's orientation. ( For use in "physically" rolling the device.) Can be combined with vibration for haptic feedback. (Cool!)

Compact.

Device should be designed in mind to save space and maximize efficiency, to allow different designs without being constrained.

Basic UI / Info.

Device should have some basic form of UI and information displayed on the physical screen, that can describe for example current time, rolled dice, or perhaps see history of rolled dice.

Robust.

Shouldn't explode when dropped, and the 3D-chassis and circuit design should be designed to reduce failure under stressed conditions.

Vibration function. 

To allow for haptic feedback and notifying users of their turn.

Nice to have.

Small speaker / piezo buzzer.

Speaker would be nicer, to allow inserting 1:1 sounds, but a buzzer may also work for simple tones and melodies for alerting users.

Bigger screen.

To allow users to see the UI easier.

Touch-screen.

To allow users to interact with the device and configure it on the fly.

More advanced UI.

Collaborates with the Touch-screen to allow more in-depth customization of the dice-thing by users.

Future improvements.

Adaptive to played boardgames. 

This is much more up in the air, but a kind of menu of different games that users can "customize" their dice-thing for to show specific info relevant to the game. For example, in Root it will show a faction-specific die, and you could open a menu to explain your faction specialties ( So the player won't have to flip their board.)

Smaller version.
This could either be for a smaller, more convenient form factor or to allow for interaction with a bigger dice-thing.
An example would be a four player game, with a "big" dice-thing acting as a manager and different smaller dice-things act are distributed to each player to act as a turn timer and turn reminder, while also being able to display faction info etcetera.


Smaller PCB.
This is for rule of cool.
Customized PCB to avoid use of wires and to gentrify all designs. Only done if i feel like losing money though.

