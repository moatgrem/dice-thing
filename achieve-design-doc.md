<h1>How to achieve the different ideas.</h1>


<h3>Physical screen.</h3>

Research screens and which libraries they have for a ESP32 module.

<h3>Battery-driven.</h3>

Research power needs for the system to decide battery format and mAh.

<h3>Modify code-wise.</h3>

Include way to access the USB-port of the ESP32 device. Smartest way is keeping the base port and using it for both charging and debugging.

<h3>Optimize battery-life.</h3>

In the hardware, calculate power usage and minimize power loss through intelligent design of the circuits. Components should also be considered for power use when picked.

In the software, creative use of deepsleep and waking the system up only when needed is the way to start, but more time sohuld be spent researching it.

<h3>Rechargable via {Unknown}.</h3>

Most likely will be via USB-port, but design that allows recharging of battery while also debugging the system must be considered. ( Transistors? Research!)

<h3>Non-self combusting.</h3>

Design device to decrease risks of catastrophic failure, triple check physical design and calculations.

<h3>3D-printed chassis.</h3>

Theoretically easy, but will take a few passes to get just right for feel, design and proportions.

<h3>Accelerometer.</h3>

Must include a accelerometer to allow the device to sense it's orientation. ( For use in "physically" rolling the device.) Can be combined with vibration for haptic feedback. (Cool!)

<h3>Compact.</h3>

Device should be designed in mind to save space and maximize efficiency, to allow different designs without being constrained.

<h3>Basic UI / Info.</h3>

Device should have some basic form of UI and information displayed on the physical screen, that can describe for example current time, rolled dice, or perhaps see history of rolled dice.

<h3>Robust.</h3>

Shouldn't explode when dropped, and the 3D-chassis and circuit design should be designed to reduce failure under stressed conditions.

<h3>Vibration function. </h3>

To allow for haptic feedback and notifying users of their turn.

<h1>Nice to have.</h1>

<h3>Small speaker / piezo buzzer.</h3>

Speaker would be nicer, to allow inserting 1:1 sounds, but a buzzer may also work for simple tones and melodies for alerting users.

<h3>Bigger screen.</h3>

To allow users to see the UI easier.

<h3>Touch-screen.</h3>

To allow users to interact with the device and configure it on the fly.

<h3>More advanced UI.</h3>

Collaborates with the Touch-screen to allow more in-depth customization of the dice-thing by users.

<h1>Future improvements.</h1>

<h3>Adaptive to played boardgames. </h3>

This is much more up in the air, but a kind of menu of different games that users can "customize" their dice-thing for to show specific info relevant to the game. For example, in Root it will show a faction-specific die, and you could open a menu to explain your faction specialties ( So the player won't have to flip their board.)

<h3>Smaller version.</h3>
This could either be for a smaller, more convenient form factor or to allow for interaction with a bigger dice-thing.
An example would be a four player game, with a "big" dice-thing acting as a manager and different smaller dice-things act are distributed to each player to act as a turn timer and turn reminder, while also being able to display faction info etcetera.


Smaller PCB.</h3>
This is for rule of cool.
Customized PCB to avoid use of wires and to gentrify all designs. Only done if i feel like losing money though.

