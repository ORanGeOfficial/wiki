## Processing paths chart
There is **[chart with some important processing paths](https://github.com/McZapkie/TerraFirmaProgressivePack/blob/master/doc/processingpaths.pdf)**, including flux, leather, mortar, efficient iron and steel production, zinc plating with cadmium recovery, aluminum smelting and some basic chemical components (natrium hydroxide, sulfuric, nitric and hydrochloric acid).  

For another processing paths please refer NEI readings.  

I advise to use some in-game manuals (Achievements book, IE manual, IFL manual).  

## Below there are some hints.  

### Usage of iron workbench.

Iron workbench have three slot groups: shapeles input of tools, shapeless input of materials and multiple slots for output. Therefore you can put additional tools and materials and choose output, unused materials will remain on the table.  
Below there is example: the only material required for piston is hot steel ingot, additional stick is not needed but doesn't interfere with recipe and will remain intact. Most of tools also is not needed and only lathe will be used and slightly damaged:

![iron workbench gui](https://github.com/McZapkie/TerraFirmaProgressivePack/blob/master/doc/ironworkbench_gui.png)

Left border of GUI, belo iron workbench icon, contain requirements for additional machines, in above case it is lathe table. Additional machines must to be placed close to workbench. In case of lathe table, both parts must be placed, see picture below:
![lathe placement](https://github.com/McZapkie/TerraFirmaProgressivePack/blob/master/doc/ironworkbench_latheplacement.png)

Some of machines need to be powered and have electric motor in its slot. Welding station must to be filled with oxygen (left bottle) and water with carbide (right bottle).  

### Efficient steel production.  

Transfer Ladle, filled with ore batch and flux, must to be placed into IE blast furnace:
![Immersive Engineering blast furnace](https://github.com/McZapkie/TerraFirmaProgressivePack/blob/master/doc/improvedblastfurnace.png)

This will produce Transfer Ladle filled with liquid pig iron. The next step is Bessemer Blast Furnace, which need heat source and compressed air to convert pig iron into liquid steel:
![Bessemer convertor](https://github.com/McZapkie/TerraFirmaProgressivePack/blob/master/doc/bessemerfurnace.png)

Transfer Ladle block should be placed 5 tiles above refractory hopper (funnel for hot liquids) which will catch molten steel and transfer it to the Metal Caster or other Foundry device located below this hopper. Once placed, it will immediately spill 5 cubes of molten metal (vertically, if there are air blocks beneath it), use sneak mode with shift to place without skip.
Hint: it is wise to make 5 block high chimney above refractory hopper:

![one side of chimney is transparent for better view](https://github.com/McZapkie/TerraFirmaProgressivePack/blob/master/doc/transferladle2.png)

If everything is OK, you should see metal caster slowly filled with liquid steel:
![metal caster gui](https://github.com/McZapkie/TerraFirmaProgressivePack/blob/master/doc/filledcaster.png).  

One Transfer Ladle contain 5000 mb of liquid steel, equivalent of about 40 ingots.  
If metal caster and hopper are empty, probably Transfer Ladle was placed too high. Place additional hopper above to solve such problem. 
In case of any failure, molten metal can be extinguished with water (you will get metal blocks from full liquid blocks and useless slag blocks from flowing blocks.

Complete setup for fast steel production and casting - IE blast furnace with preheaters, Bessemer furnace with electric heater, foundry metal caster with funnel chimney above, and RF/EU cables:
![steel processing setup](https://raw.githubusercontent.com/McZapkie/TerraFirmaProgressivePack/master/doc/steelprecessingsetup.jpg)

### Efficient black steel production.  
Molten Weak Black Steel (for example from Foundry Alloy Mixer) can be upgrade in Foundry Infuser into Carbonized Black Steel. Full stack of 5000mB Carbonised Black Steel can be poured into Transfer Ladle and proceed in Bessemer Furnace to obtain Transfer Ladle with regular Black Steel.
Finally you can place Transfer Ladle above Refractory Hopper to acquire molten metal, similar as was described for Steel.