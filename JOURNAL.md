# Taranium Pico

Total time spent: 12 hours

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

Okay im home and can work more now.


![image](https://cdn.hackclub.com/019e20e1-049f-726e-bfc3-a5c5786774d9/Screen%20Shot%202026-05-12%20at%206.43.05%20pm.png)


Changed the pins here to include run in the middle so i can externally control the reset button if I want


![image](https://cdn.hackclub.com/019e20e2-573b-7e30-a4f0-18b581abf160/Screen%20Shot%202026-05-12%20at%206.43.21%20pm.png)

Moved the capacitor closer to the flash and moved the resistor closer to the pin it needs to go to.


![image](https://cdn.hackclub.com/019e20e5-1927-7f9a-a210-3e71e215b644/Screen%20Shot%202026-05-12%20at%206.46.58%20pm.png)

repositioned this slightly so the ground pour could connect and give a better return path for the GND pin at the top cuz before it was kinda cooked.
What are return paths you might ask? Idk i saw a reel on them once and apparently they cause noise and stuff if you dont have a clear path

![image](https://cdn.hackclub.com/019e20e5-f98d-7a9f-8ba6-429ee5d26757/Screen%20Shot%202026-05-12%20at%206.49.10%20pm.png)

More adjusting stuff to improve return paths and so they dont take a marathon around the whole board to get back to ground.

![image](https://cdn.hackclub.com/019e2110-4ebb-7605-a2e4-bdef3eace602/Screen%20Shot%202026-05-12%20at%207.01.09%20pm.png)

The whole board
Now its time to make the silkscreen


![image](https://cdn.hackclub.com/019e2110-dedd-75aa-8af0-0278d9941f09/Screen%20Shot%202026-05-12%20at%207.56.00%20pm.png)

Here is what the size for my board is

okay the bottom got clipped out but the dimensions are 39.1x26.9mm


![image](https://cdn.hackclub.com/019e211d-9501-72a2-ba7a-784ced3b864d/Screen%20Shot%202026-05-12%20at%208.20.33%20pm.png)

made a card with the same aspect ratio and rounded the corners by multiplying the aspect ratio by the number of pixels on one side and then by 2

![image](https://cdn.hackclub.com/019e211e-76ee-71d9-b8c5-8f5fcb9f7d02/Screen%20Shot%202026-05-12%20at%208.30.45%20pm.png)


Made this with my logo

Its tuff frfr

![image](https://cdn.hackclub.com/019e211e-f186-7712-895e-e06f44df22ec/Screen%20Shot%202026-05-12%20at%2011.30.26%20pm.png)

Spent way too long making my own globe symbol thing.

I wasnt bothered to search the web so I just did it myself.

Time Spent: 4 hours

## 13th of May

![image](https://cdn.hackclub.com/019e211f-d88d-7db1-99fe-319b2a42caec/Screen%20Shot%202026-05-13%20at%2012.22.31%20am.png)


Inversed the colours because the black logo and text on white bg lowkey looked better than the other way around and I wanna keep the top black

The github logo was not made by me. i just imported it from their branding website. I am not gonna sit here and replicate the octocat from memory.


![image](https://cdn.hackclub.com/019e2121-8688-7f8e-a4ad-bd940ac13374/Screen%20Shot%202026-05-13%20at%208.27.00%20am.png)

I had to fiddle with this because figma was being sucky and wouldnt subtract it the way I wanted. so like that was annoying/fun. I did get it after a lot of trail and error


![image](https://cdn.hackclub.com/019e2123-614e-79fb-aec5-d6f167b6fe74/Screen%20Shot%202026-05-13%20at%208.38.24%20am.png)

Tada

it looks nice. I had to fidle with the text a bit to get it to line up properly/not get covered


![image](https://cdn.hackclub.com/019e2124-2ead-73ee-84ef-2a57ddcd0e9f/Screen%20Shot%202026-05-13%20at%208.46.01%20am.png)

Here is what the top looks like

![image](https://cdn.hackclub.com/019e2124-8e46-75d8-bd4b-d1ee60c35a62/Screen%20Shot%202026-05-13%20at%209.46.00%20am.png)

After that I made a pinout diagram for the thing

This was the initial thing. but rudy told me about orthogonal view on the render and I used that instead. I also found out that kicad lets you take renders with invisible backgrounds so thats fun.

![bleh](pinout.png)

Here is the final pinout.


![image](https://cdn.hackclub.com/019e2129-aacd-742f-9c3b-3ba994f03b7d/Screen%20Shot%202026-05-13%20at%203.02.59%20pm.png)

After that I started writing the readme and also got this sick render of the board.

Now its footprint and symbol time. 

Since I am making this for my other project, I need a footprint and a symbol so i can actualy import it properly into the pcb.

![image](https://cdn.hackclub.com/019e212b-b399-7b2f-9fd5-927102652aed/Screen%20Shot%202026-05-13%20at%206.50.43%20pm.png)

Footprint was simple enough. just some pins and then copy the cutlines, replace as silkscreen + keepout

I then copy pasted the usbc footprint and positioned it properly at the right distance. then deleted everything except the front silkscreen

![image](https://cdn.hackclub.com/019e212d-3f43-7fe7-8758-836c7d1379d8/Screen%20Shot%202026-05-13%20at%206.18.55%20pm.png)

Paired the 3d model to the footprint.


![image](https://cdn.hackclub.com/019e212d-c089-7fff-992f-1fe784287a55/Screen%20Shot%202026-05-13%20at%206.50.33%20pm.png)

After that I made the symbol.


Then I finished up on the readme and the bom. 

And thats is. im done. its all over. until someone sanity checks this and finds 50 million problems.


Time spent: 

3 hours


