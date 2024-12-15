![2](https://github.com/user-attachments/assets/bb7bff12-f1ed-46bf-b5cb-f4c5dfb10c3d)# Ender 3 V3 SE dual fans upgrade

What you need:
  - soldering iron (with tin and flux)
  - wire cutters
  - heat shrink tubing
  - additional wire
  - 2x4010 blower fans (24V)
  - optional 4010 fan for heatsink
  - screws/nuts (check with the BOM of the shroud you are using)

## Step 1: print the shroud

There are many dual 4010 fans shrouds for the V3 SE, and here are the ones I recommend:
  - https://www.printables.com/model/910918-ender3-v3-seke-dual-4010-blower-shroud-for-k1-hote
  - https://www.printables.com/model/619049-ender-3-v3-se-dual-4010-shroud
  - https://www.printables.com/model/776177-ender-3-v3-se-dual-4010-shroud-k1-edition
  - https://www.printables.com/model/818919-slim-ender-3-v3-se-dual-4010-shroud-k1-edition
  - https://www.printables.com/model/809391-ender3-v3-se-dual-4010-shroud-for-k1ke-hotend

Choose one and print it. Usually you want to print at least the ducts in a material that has a higher melting temperature than the material that you usually print with. For example, if you mostly print PLA, you could use PETG ducts. If you print mostly PETG, you could do the ducts in ABS/ASA (careful at health concerns). Keep in mind that the ducts will probably deform over time.

In my case, i chose the 1st one, and printed it fully in PETG. Keep in mind that this process is applicable to any shroud, fans or printer.

## Step 2: prepare the fans

Take your fans, and find the polarity. Usually, the red wire is + and the black one is -. 

Cut the fan wires and remove the insulation.
Also get the original fan and cut the wires at about 2-3 cm from the end to get the connector.
![fans prepare](./pictures/1.jpg)

Twist the exposed ends of the fans by polarity (red with red, black with black), then add the heat shrink tubing. Make sure it is long enough to cover the entire soldering job (a little longer than the exposed end of the wire).
![solder prepare](./pictures/2.jpg)

Then, cut 2 pieces of wire (about 10cm each should be more than enough), and solder them with the ends of the fan wires.

Alternatively, one could replace the fan wires with longer ones (desoldering the existing ones and soldering newer ones).

Solder the connector to the ends of the wires.
**DOUBLE CHECK YOUR WORK** by pulling the wires and seeing if they come apart. Aditionally, you can check the continuity with a multimeter and make sure that the cables are not touching.
After that, slide the tubing over the joint and shrink it with a lighter/heaat gun/soldering iron.
![solder](./pictures/3.jpg)

## Step 3: testing the fans
After making sure that the assembly is correctly made, you can proceed and test if it actually works.
Power off the printer, and connect the fans to the correct ports.
Turn the printer back on and test the fans, by sending a command via the console or using the menu.

If the fans are working, congratulations, you have made it 🥳
If not, I suggest keeping calm, and redoing everything from step 2.

## Step 3: finishing the shroud

Now all that's left to do is putting the fans into the shroud and then mounting it on the printer.

Happy printing!
