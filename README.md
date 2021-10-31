# BazingaPrime
A texture pack for Metroid Prime that replaces everything with Bazinga

## What's left to finish
* Metroid4 (Tallon Overworld)
* Metroid5 (Phazon Mines)

### What the hell is this?
A Byproduct of my own boredom, it replaces every texture (and eventually every sound effect once I figure out how to convert to DSP) in the game with Bazinga

### Why did you make this?
no good reason really, was just bored. I was inspired by a L4D2 mod that turned everything into Bazinga (mod was made by CriticalChrius, [go check his mod out](https://steamcommunity.com/sharedfiles/filedetails/?id=314961446))

### Ok I'm mildly interested, how do I try this?
I made this texture pack with Metaforce in mind, so I'm gonna tell you how to use it that way.

* Download the latest version of [Metaforce](https://releases.axiodl.com)
  * It's recommended  you download from the `continuous` folder, as those builds are much more up to date
* Download [Blender](https://www.blender.org/download/) as well, anything from `2.83` to `2.93` should work just fine
  * make sure Blender is located in the `C:\` drive, specifically `C:\Program Files\Blender Foundation`, as that's where Metaforce looks for it
* Open `Metaforce-Gui`
  * select a directory for Metaforce to extract to (The shorter the directory path is, the better, so sorta like `C:\Metaforce` or `/home/Metaforce` for Linux)   
  * Click `Extract` then select your iso of Metroid Prime
* once it's done extracting, download this git repository (`git clone https://github.com/BoofOof32/BazingaPrime.git`. Or download a Zip of the repo)
* In the extraction directory, go into the MP1 folder and drag and drop the folders from the Bazinga Prime folder into the MP1 folder to replace all the textures
* before replacing all the textures in the `MP1` folder, I split the textures in the `Shared` folder into 2 folders due to Github's file limit per folder, so make sure to take out the textures from both folders and put them into the `Shared` folder
* Then open `Metaforce-gui` again and click `package`
* Enjoy

### What about Dolphin?
The thing with Dolphin is that the way the textures are named differ from Metaforce, so if I were to make this pack compatible with Dolphin, I would need to rename all of the textures for them to work. I might make it compatible with Dolphin someday (or someone forks this and does it themselves, whichever comes first), but right now, I just wanna finish this texture pack for Metaforce first. Alternatively, an Xdelta file for this could be made, but I sadly don't know how to make those, so .
