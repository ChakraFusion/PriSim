This Excel VBA table is able to accurately advise you about your individual upgrade values based on your TH level and attacking troops.
Because of many defenses which deal splash damage it was necessary to build a complete simulation of moving troops to closely resemble the in-game behaviour of troops swarms.

![image](https://github.com/ChakraFusion/PriSim/assets/112588066/058017a3-5f65-407f-b5ac-6fdabde440a8)
All the controls you need are on the first sheet. The second and third sheet contain tables with the data used by the simulation script.

You can:
- edit the 'default settings' (green numbers) on the top left
-   drop angle: sets the range (in degrees) in which the selected amount of troops is evenly dropped
-   drop delay: time between every single drop of a selected troop
-   drop pause: time between different troops being dropped

- edit the individual troop and defense levels
- use the TH level preset selections, save and load level buttons

- edit visualised troops by clicking on the colored shapes
- edit troops directly by modifying, or pasting the drop code (it gets parsed automatically)

- Important: select the output mode; it also influences the scatter plot
-   recommended: 'DPS increase per upgrade time'

- hit the 'simulate' button to process the currently displayed troop selection

VBA needs to be activated for anything to work! I designed the table with Excel 365. Compatability with other versions hasn't been checked.
