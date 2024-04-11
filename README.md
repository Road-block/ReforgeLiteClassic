#### Original versions by d07.RiV (Iroared)

### Overview
ReforgeLite is a lightweight reforging calculator that helps you figure out the optimal strategy to reforge your gear given your stat weights and caps without leaving the game.

### How to use it
To open the addon window, type /reforge or talk to the reforging master. On the left half of the window you can see your current item stats for reference.
On the right side you can set up stat weights/caps, or select an existing preset.
In the simplified mode, you can specify the stat priority, along with up to two capped stats (each capped stats can have an arbitrary number of breakpoints). If you want more control, you can go into advanced mode and enter the exact stats specific for your gear, obtained from a tool such as SimulationCraft.
Behind the hood, simplified mode sets the lowest stat to a weight of 100, and each next stat adds 20. When you switch between the two modes, ReforgeLite converts your current weights to the other format.

When you're done setting up weights/caps, press Calculate. The calculations are fairly memory/time intensive, so ReforgeLite might trade some precision for speed, though the losses should be minimal. You can press the Calculate button a few times if you want to try getting a better result, the output will always display the best result so far.

Once the calculation finishes, you will see a section with your stats after reforging, and the difference from your current stats. Click on the Show button to see which items should be reforged.
If the reforging UI is open, you can click on the Reforge button to automatically reforge all items in the selected way. Do not interfere in the process (clicking the cancel button or closing the reforging UI is fine)

#### FAQ: I'm using certain items for my off-spec and I don't want their reforge changed.
Simply click on an item icon in the large stats table, this will lock the item's reforge.
