# Taranium Pico


RP2040 Devboard thats wonky and horizontal for packaging reasons.

## 7th of May

Okay so I was working on the driving macropad when i ran out of pins. :( thats not very fun.  And all the microcontrollers I found were like either too big or the same size. So here I am making something that solves my problems and gets me a mircocontroller with more pins.

![bleh](https://cdn.hackclub.com/019e193f-291d-7648-8c5b-3632d3b35abe/Screen%20Shot%202026-05-07%20at%209.05.02%20am.png)

Put down stuff. at minimum i need 2 more pins for my use case to work so will probably do that via 4 pins in a line on the bottom, 4 pins cuz if i can have more pins then its more useful for future.


![capatito](https://cdn.hackclub.com/019e19b2-fbfd-7355-b9fb-602819694c3e/Screen%20Shot%202026-05-07%20at%209.36.16%20am.png)

Capacitors added cuz cool beans

![image](https://cdn.hackclub.com/019e19b3-83c9-7e62-842b-6a68f98e2445/Screen%20Shot%202026-05-07%20at%209.36.21%20am.png)

Usb C cuz usbC is superior.

Also i currently just trying to plop down all the parts I need and then route it all later

Helps me visualise stuff and whatnot

![reset](https://cdn.hackclub.com/019e19bc-8991-769c-a91e-5c92832281ca/Screen%20Shot%202026-05-07%20at%209.36.28%20am.png)

Made a reset button.

It resets the microcontroller. cuz reset buttons are cool

![led](https://cdn.hackclub.com/019e19bd-5963-7066-8c8f-eeedf7976b31/Screen%20Shot%202026-05-07%20at%209.39.42%20am.png)

Made an indicator led. Might add more LEDs later depending on my mood and how much cool stuff I wanna add.

![cccc](https://cdn.hackclub.com/019e19bf-aa26-7b21-86be-8eabf3e03510/Screen%20Shot%202026-05-07%20at%2010.59.37%20am.png)

Routed the usbc and voltage regulator kinda sorta half half. Still need to do a bit more but most of the way there.

![banana](https://cdn.hackclub.com/019e19c6-4501-72aa-b11d-53ca09054597/Screen%20Shot%202026-05-07%20at%2010.59.41%20am.png)

USBc was routed with reference to this schematic I found on the internet. I have done this so many times before yet I lways for got how to do it. so hooray for the internet.

![farts](https://cdn.hackclub.com/019e1a29-c277-77b5-9b01-350b7603fb25/Screen%20Shot%202026-05-07%20at%201.58.04%20pm.png)

While searching for usbc schematics, I found this and remembered about seeing something like this(like the 6 pin ic) on my undercity badge. after some looking aruond I saw that its used to reduce noise in the trace.


![bleh](https://cdn.hackclub.com/019e1a2c-aa6e-7130-9a95-53b55dfa94c0/Screen%20Shot%202026-05-07%20at%201.58.18%20pm.png)

Also found this in the datasheet of the part and it matches what the thing from above shows so imma trust it.

![bleh](https://cdn.hackclub.com/019e1a2d-654d-7000-8d54-e57138316399/Screen%20Shot%202026-05-07%20at%202.03.33%20pm.png)

Routed it as shown in the datasheet.



![chris](https://cdn.hackclub.com/019e19c7-432b-7192-8489-0178eac8824b/Screen%20Shot%202026-05-07%20at%2011.08.53%20am.png)

Crystal wired done. this one is pretty easy. just funny R thingy with resistors and caps and stuff

![plash](https://cdn.hackclub.com/019e19c8-5df7-776b-80f3-2585a4d66a80/Screen%20Shot%202026-05-07%20at%2011.10.06%20am.png)

Flash. with the boot button and thats about it for now, imma do the rest later.


Time spent: 2 hours

## 8th Of May


first thing I had to change my usbc footprint to change the mounting pin numbers from s1 to 0 so it could match my symbol since it didnt match before.

![bleh](https://cdn.hackclub.com/019e1a2f-9df8-762f-9a6c-47d91448ee67/Screen%20Shot%202026-05-08%20at%203.19.59%20pm.png)
![image](https://cdn.hackclub.com/019e1a2f-cea5-700a-a211-6e46f643be3e/Screen%20Shot%202026-05-08%20at%203.20.07%20pm.png)


![image](https://cdn.hackclub.com/019e1a30-1b87-7f10-b0cc-17e024bf8503/Screen%20Shot%202026-05-08%20at%204.53.41%20pm.png)


the parts are too big. tspmo im gonna slime nimit. 

anywasy time to thonk up a solution. giving it more pins to give more space would just defeat the purpose of making my own dev board

So I go to the drawing board. And now an idea forms. what if I put the port at a 90 degree angle. that way It would just need to be wider and not longer. so like it would still fit on my board for the macropad. I also think it would be something cool to do since I haven't really seen horizontal dev boards before so would be cool

Time Spent: 1 hour

## 11th of May

![layout](https://cdn.hackclub.com/019e1b29-6189-7470-8b3b-2e4b283a3891/Screen%20Shot%202026-05-11%20at%209.04.30%20am.png)

Layed out my port and the mircocontroller

![wire](https://cdn.hackclub.com/019e1b2e-6dff-78cc-9f6b-6e36ee14e242/Screen%20Shot%202026-05-11%20at%209.04.26%20am.png)

Wire this thingy with the data lines

![image](https://cdn.hackclub.com/019e1b2f-40ee-7bc6-9900-6e0b8ebac70f/Screen%20Shot%202026-05-11%20at%209.42.19%20am.png)

Layed out the rest of the parts(mostly)

![image](https://cdn.hackclub.com/019e1b30-4715-73a0-9942-03ceec1312bf/Screen%20Shot%202026-05-11%20at%209.51.22%20am.png)

Finished laying out the parts(this was annoying)(almost as annoying as nimit)

![image](https://cdn.hackclub.com/019e1b34-4951-7001-8448-a635487f5849/Screen%20Shot%202026-05-11%20at%2010.21.51%20am.png)

route it up, route it, route it up

also problem :) 

the flash

it no worky

as in if i want to route it

the lines cross over the usb data lines

meaning that i need to put the flash above the usb and not the other way around

so in other wordds

I

am

gonna

crash

out

because I need to bascially reroute this whole thing and also reposition all the parts. but eh this was kinda messy so hopefully it gets better???

idk we look and see and pray and cry


![image](https://cdn.hackclub.com/019e1b37-47e1-7bd8-b715-00bfadd53783/Screen%20Shot%202026-05-11%20at%209.21.15%20pm.png)

did a thing

repositioned everything and routed the flash first. its kinda wonky though sincce i need the traces to go away from the thingy. which is fun

![image](https://cdn.hackclub.com/019e1b38-3297-7878-ac47-432e30946145/Screen%20Shot%202026-05-11%20at%209.14.25%20pm.png)

idk if thats a problem so i asked around and am waiting response. in the meantime imma route the rest of the stuff.


![image](https://cdn.hackclub.com/019e1b39-5434-7e8d-b433-b0aa18c5b202/Screen%20Shot%202026-05-11%20at%209.49.41%20pm.png)

made a wibbly wobbly line for length matching for the usb data line. cuz thats cool and i also finally learnt how to use the fillet feature on kicad and am now spamming it everywhere.


![image](https://cdn.hackclub.com/019e1b3a-5b92-765b-9b69-5a37f5a2d40a/Screen%20Shot%202026-05-11%20at%209.55.01%20pm.png)

feedback from the niminator came back and says its hella cooked.

so i did another thing and rotated it 45 degrees so the traces are more even and stuff.

![image](https://cdn.hackclub.com/019e1b3b-3490-7e02-a873-aefacd8dfd57/Screen%20Shot%202026-05-11%20at%2010.09.27%20pm.png)

I added a 3 pin header at the top over there and also extended the other header to 6 pins cuz i had space and the more pins the merrier

![image](https://cdn.hackclub.com/019e1b3c-b610-76c4-a97e-668ddc49c15e/Screen%20Shot%202026-05-11%20at%2010.20.12%20pm.png)

routing the headers

![image](https://cdn.hackclub.com/019e1b42-0d4f-79b2-845f-e0c8af66f757/Screen%20Shot%202026-05-11%20at%2010.30.18%20pm.png)

Routing is finished :)


![image](https://cdn.hackclub.com/019e1b43-d77f-75eb-a02e-45a636b92d29/Screen%20Shot%202026-05-11%20at%2010.36.42%20pm.png)

here is how large it ended up. I will probably also need to make a symbol and footprint for this since I will need to put it on a pcb


![image](https://cdn.hackclub.com/019e1b44-c644-7db3-8b37-90aa4fba6102/Screen%20Shot%202026-05-11%20at%2010.57.51%20pm.png)


Okay nevermind its not finished routing im stupid.

So i added a 3v3 pin on the 3 at the top and also added gnd pins cuz i forgot to add them before

Then I added the board edgeline, gave it a fillet, and then added a ground pour and spammed vias to let it spread and connect everything properly

![image](https://cdn.hackclub.com/019e1b47-0f05-7511-ba49-b1dae2c60b75/Screen%20Shot%202026-05-11%20at%2010.58.24%20pm.png)

3d model of the pcb. somehow with all the parts there


Time spent: 2 hours

## 12th of May

![image](https://cdn.hackclub.com/019e1b47-8bc3-7ebb-81c1-21ea0bad3e32/Screen%20Shot%202026-05-12%20at%208.10.52%20am.png)

amogus


Needa put a silkscreen on this thang I also wanna wiggle some stuff around cuz some of it looks a tad bit iffy.







