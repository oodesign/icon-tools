<img src="https://github.com/oodesign/icon-tools/blob/master/Images/Hero.jpg" alt="Icon tools logo"/>

# Icon tools (Sketch plugin)

Sketch.app plugin to clean icons and to prepare them for a clean export without tints and masks. 

## Clean icons in Sketch

Clean icons from undesired layers, groups, texts, etc.

Simply run the "Icon tools > Clean icons" from the Plugins menu.

The plugin will scan automatically all groups/symbols in the selected page, and remove all the undesired layers for you. It will also remove useless layer groups.
You may choose if you want to remove everything but shapes, juste texts, or othing at all.
<br/>
You may also choose if you want to combine all those shapes into a single shape group (which will combine them all using the Union option). 
<br/>

## Prepare icons for export

We are all using the <a href="https://medium.com/design-prototype/sketch-tint-icons-using-nested-symbols-2d52867e0d29">tint hack</a> in our Sketch icons, so that we can have just a single icon, and then override its color in each one of its instances.

The point is that when you generate assets for the Dev team, the 'hack' is also exported in your SVGs, making the SVG file larger and dirtier. We created 'Icon tools' to help with that.

Just run the "Icon tools > Prepare icons for export" from the Plugins menu.

The plugin will scan your whole Sketch file looking for symbols containing a specific string in the name. By default, the string is "ExportableIcon/", but you may change it for the one you use to identify your icon symbols in the Sketch file.
<br/><br/>
You may also choose the name of your tint layer. Layers with this name will be removed from the final exportable icons. By default, the tint layer name is "🎨 color" - if you use the <a href="https://github.com/AMoreaux/Sketch-Icons">Sketch Icons plugin</a> (you should, really :) ) that will be familiar to you - . 

The plugin will process all of your icon symbols and generate a new page (called ExportIcons) with all of your icons, but just with the layers that are needed for export (without tints), and with the slices already created.

And that's it! You just need to go for Export (the default Export, in Sketch), and export all your clean icons.

<br/>
-----------------

You may run the "Prepare icons for export" as many times as you want. The ExportIcons page is removed and generated again each time you run the plugin (which is cool to avoid clutter, but something you need to be careful with).

## Manual Installation

1. Download [IconTools.zip](https://github.com/oodesign/icon-tools/archive/master.zip) archive with the plugin.
2. Reveal plugins folder in finder ('Sketch App Menu' -> 'Plugins' -> 'Manage Plugins...' -> 'Gear Icon' -> 'Show Plugins Folder').
3. Delete previously installed version of the plugin (`Icon tools` folder or `Icon tools.sketchplugin` bundle)
4. Un-zip downloaded archive and double-click `Icon tools.sketchplugin` file inside it.


## Considering a gift? :)

What a great plugin - <a href="https://www.paypal.me/oodesign/3" target="_blank">Donate 3€</a>

Wow! That really helped me! - <a href="https://www.paypal.me/oodesign/5" target="_blank">Donate 5€</a>

This totally saved my life! Shut up and take my money! :) - <a href="https://www.paypal.me/oodesign/10" target="_blank">Donate 10€</a>

