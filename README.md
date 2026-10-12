# The Ladybird Book of the Comms Rack Calculator

*A guide for sensible people who wish to put their network things in a tidy box.*

---

## Page 1: The Rack

*Picture: a tall metal box with holes in it, standing in a cupboard under the stairs.*

This is a **rack**. It is a metal cupboard for machines.

The machines are called **network kit**. Switches, routers, and little boxes with blinking lights all live in the rack.

The rack is only **ten inches** wide. It is a small rack for small places.

The rack is measured in **U**. One U is one shelf-space. A small switch takes one U. A big video recorder takes two.

---

## Page 2: Peter Has Too Many Boxes

*Picture: Peter surrounded by network boxes, cables everywhere. Jane looks cross.*

Peter has bought a switch, a router, a recorder for the cameras, and a box that keeps the lights on when the power goes off.

"Will it all fit?" says Peter.

"Let us do some sums," says Jane.

Doing sums about racks is called **planning**. Planning is very sensible.

This book is about a program called the **Comms Rack Calculator**. It does the sums for Peter and Jane.

---

## Page 3: The Shiny Calculator

*Picture: a computer screen showing a tall rack, filling up with coloured boxes.*

Here is the calculator. It lives at:

**https://itsfja.github.io/Comms-Rack-calculator/**

Peter clicks on the things he has bought. Click, click, click.

As he clicks, the picture of the rack **fills up**. Each coloured stripe is a thing. Each stripe says which U it sits in.

At the top there are numbers. **Used. Free. Percentage.** The numbers change as Peter clicks, like magic.

---

## Page 4: The Jack Panel

*Picture: a small panel with lots of little square holes, like a hotel for plugs.*

Some machines need a **jack panel** in front of them. It is a panel with holes, so Peter can plug cables in and out without reaching behind the rack.

The calculator can save a space for a jack panel in front of **each** machine. There is a little switch that says yes or no.

When the switch says yes, a grey stripe marked *"Jack panel"* appears above the machine in the picture. Jane is pleased. Everything has its hole.

---

## Page 5: Uh Oh, Too Many Things

*Picture: the rack overflowing. A red arrow says "9U over". Peter looks worried.*

Sometimes Peter gets carried away and clicks too many things.

If the things do not fit, the calculator says **"You are 9U over"** in red letters. It is telling Peter to take something out, or buy a taller rack.

Peter takes out the fan tray. Now it fits. *"Fits with 2U to spare,"* says the calculator. Peter and Jane have a biscuit.

---

## Page 6: How to Use It

1. **Choose the rack.** Four U, six U, nine U, ten U, or twelve U.
2. **Choose the numbering.** Some racks start counting at the bottom, from nought. Some count from the top. Peter does not know which his rack will be, so the calculator lets him choose.
3. **Click your kit.** Switches, patch panels, recorders, and more. Or type in your own.
4. **Say yes or no to jack panels** for each thing, with the little switch.
5. **Watch the picture** fill up and the numbers change.
6. **Press Print** if you would like the plan on paper.

The calculator **remembers** your plan in the browser, so it is still there when you come back.

---

## Page 7: Peter's Real Kit

*Picture: Peter's actual machines lined up on the table. Each has a label with its holes.*

Peter has put his **real things** in the calculator. They are:

* Two **Intel NUCs** (2U each)
* A **Raspberry Pi 4**
* A **UniFi Cloud Gateway Fiber**, which has very fast holes
* Two **UniFi Flex Minis** and two **Flex Mini 2.5Gs**
* A **MikroTik 10G switch**
* A big **TerraMaster NAS** called F4-425 Pro

Each thing shows its **holes** — how many plugs it has, and how fast they go. The calculator counts them all up. Peter's kit is **15U**. Uh oh. The TerraMaster is very tall — **fifteen centimetres**, which is nearly four U on its own. Peter needs a much bigger rack.

The TerraMaster has **no printed mount**. Nobody has made one yet. It must sit on a **shelf**, like a fat cat on a very tall ledge.

---

## Page 8: The Plastic Brackets

*Picture: a 3D printer printing a bracket. The ladybird wears tiny safety goggles.*

Most of Peter's things need a **bracket** to live in the rack. A bracket is a piece of plastic with holes that screws the thing in place.

Kind people on the internet make brackets and share them for free. They are called **STL files**.

The first time Peter adds a thing, the calculator says: *"Here is the bracket for this one."* Peter can click and get the file. It only asks once per thing. It never nags.

---

## Page 9: The Magic Bricks

*Picture: Peter snapping together colourful bricks. Each brick is an instruction.*

Peter has found **magic bricks**. They are called Blockly bricks.

Peter snaps bricks together like this: *set rack to twelve U. Add two NUCs. Add the gateway, with its jack panel. Add the big TerraMaster.*

Then Peter presses **Run**. The calculator does everything the bricks say, all at once. The rack fills up by itself!

There are special bricks too:
* A **repeat** brick, for doing something lots of times
* an **if** brick, which only does a thing **if** there is room
* a **free U** brick, which knows how much room is left

The bricks stay saved, so Peter can change one and press Run again. Jane says it is like teaching the calculator to build the rack itself.

*(If the magic bricks cannot be found — the internet is asleep — the rest of the calculator still works.)*

---

## Page 10: For Grown-Ups Who Read to the End

The calculator is one file called `index.html`. It has no moving parts and needs no installing.

Open it in any browser and it just works.

*The ladybird is now sitting on the top U of the rack. It likes the warm air from the fan tray.*
