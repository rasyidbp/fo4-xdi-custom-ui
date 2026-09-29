# How to
If you want to change my configuration you can follow this .md.
1. Get your swf decompiler. For this project I'm using [JPEXS Free Flash Decompiler](https://github.com/jindrapetrik/jpexs-decompiler) by jindrapetrik.
2. Download my `DialogueMenu.swf`.
3. Unzip it and open it using the JPEXS Free Flash Decompiler (FFdec).
4. Inside the `DialogueMenu.swf` you can navigate to `Interface/DialogueMenu.swf/scripts/<default package>/DialogueListEntry.as`. Ten look at the ActionScript source.

Here is some of the variable you can configure:
* FONT_BOLD = For font weight.
* FONT_SIZE = For font size and dynamically control the icon scale too.
* FONT_LEADING = For font leading.
* PADDING = For padding around the dialogue option and icon.
* ICON_OFFSET = For icon offset.

If you want to configure the XDI from the ground up on your own, use the file by registrator2000. You need to extract the mod `.ba2` file first. I'm using the [BSA Browser](https://www.nexusmods.com/skyrimspecialedition/mods/1756) by AlexxGG. Locate the XDI mod files at `Fallout 4\Data\XDI - Main.ba2`. Open it using the BSA Browser and extract it, you can find `DialogueMenu.swf` inside the `Interface` subfolder. You can follow my [Logs](logs.md) pages and see what I've changed, etc.