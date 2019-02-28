
# LED: Light Emitting Diode

## Knowledge Base
Job of LED|Polarity Matters|Resistors Always Needed| Symbol for an LED
---|---|---|---
What does an LED do?   Why is it good at this job?|What does **polarity** mean? Why is important when dealing with LED’s? How can you tell the polarity on a naked LED?|Why are resistors needed whenever you use an LED?|What is the symbol for an LED|
 



 ###### Bonus Material:   [The LED was invented at the University of Illinois](https://www.youtube.com/watch?v=KKkzBVNozjI)
 <br>
	
## Circuits
Circuit |Explaination
--------|---
LED with a Switch| Make a circuit that electricity passes through a LED.
LED’s in Series|How many LED’s can you light when they are all in series?   Why is this the case?
LED’s in Parallel|How many LED’s can you light when they are all in parallel? Why is this?
1 Bright       1 Dim|Use a resistor to make one light noticeably dimmer than another light. 
Push Button Off|Use a push button switch and make a circuit that is always on, unless you push the button to turn it off.   *No short circuits!*



<br>

## LED Background 
[Information Adapted from Sparkfun Electronics](https://learn.sparkfun.com/tutorials/light-emitting-diodes-leds)

LEDs are all around us- In our phones, our cars and even our homes. Any time something electronic lights up, there’s a good chance that an LED is behind it. \$$ 5 + 5 $$

They come in a huge variety of sizes, shapes, and colors, but no matter what they look like they have one thing in common: they’re the bacon of electronics. They’re widely purported to make any project better and they’re often added to unlikely things (to everyone’s delight).

<p align="center"> <img src="https://cdn.sparkfun.com/assets/b/7/6/0/4/51f1ba6bce395f3c20000003.jpg"> </p>

Unlike bacon, however, they’re no good once you’ve cooked them. This guide will help you avoid any accidental LED barbecues! First things first, though. What exactly is this LED thing everyone’s talking about?
LEDs (that’s “ell-ee-dees”) are a particular type of [diode](https://learn.sparkfun.com/tutorials/diodes/introduction) that converts electrical energy into light. In fact, LED stands for “Light Emitting Diode.” (It does what it says on the tin!) And this is reflected in the similarity between the diode and LED schematic symbols:


<p align="center"> <img src="img\ledDiode.png"> </p>

In short, LEDs are like tiny lightbulbs. However, LEDs require a lot less power to light up by comparison. They’re also more energy efficient, so they don’t tend to get hot like conventional lightbulbs do (unless you’re really pumping power into them). This makes them ideal for mobile devices and other low-power applications. Don’t count them out of the high-power game, though. High-intensity LEDs have found their way into accent lighting, spotlights and even automotive headlights!

Are you getting the craving yet? The craving to put LEDs on everything? Good, stick with us and we’ll show you how!

## How to Use Them
  

So you’ve come to the sensible conclusion that you need to put LEDs on everything. We thought you’d come around. Let’s go over the rule book
### Polarity Matters
In electronics, polarity indicates whether a circuit component is symmetric or not. LEDs, being diodes, will only allow current to flow in one direction. And when there’s no current-flow, there’s no light. Luckily, this also means that you can’t break an LED by plugging it in backwards. Rather, it just won’t work.

The +  positive side of the LED is called the “anode” and is marked by having a longer “lead,” or leg. The other, negative side of the LED is called the “cathode.” Current flows from the anode to the cathode and never the opposite direction. A reversed LED can keep an entire circuit from operating properly by blocking current flow. So don’t freak out if adding an LED breaks your circuit. Try flipping it around.
### Voltage Requirement
If you try to light up an LED on a single 1.5 V AA battery,  it will not light up because there is not enough potential.   Similarly, if you put the LED’s in series, each one is going to drop the potential by 2 volts.  So, if you have a 6V power potential, and each LED is pulling it down 2 volts, you might   not have enough voltage to light the bulbs.   You need less lights in series, or more voltage. Design your circuits accordingly.  


### Always use with a resistor!
If you connect an LED directly to a current source it will try to dissipate as much power as it’s allowed to draw, and, like the tragic heroes of olde, it will destroy itself. That’s why it’s important to limit the amount of current flowing across the LED.
For this, we employ resistors. Resistors limit the flow of electrons in the circuit and protect the LED from trying to draw too much current. 
The basic template for an LED circuit is pretty simple, just connect your battery, resistor and LED in series.
