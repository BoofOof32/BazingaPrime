# BazingaPrime
A texture pack for Metroid Prime that replaces everything with Bazinga

## What's left to finish
* Replace the sound effects in AudioGrp
* Maybe rig a sheldon model onto Samus (don't expect this for a *long* time)

### What the hell is this?
A Byproduct of my own boredom, it replaces every texture (and eventually every sound effect, I'm working on it.) in the game with Bazinga

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
* once it's done extracting, download this git repository (`git clone https://github.com/BoofOof32/BazingaPrime.git`. Or click *Code*, then click *Download ZIP*, and extract the contents into their own folder)
* In the extraction directory, go into the MP1 folder and drag and drop the folders from the Bazinga Prime folder into the MP1 folder to replace all the textures
* Then open `Metaforce-gui` again and click `package`
* Enjoy

### What about Dolphin?
The thing with Dolphin is that the way the textures are named differ from Metaforce, so if I were to make this pack compatible with Dolphin, I would need to rename all of the textures for them to work. Not only that, I also have plans to replace things such as the sound effects and maybe change some models, and I can't really do that on Dolphin without just modifying the iso. An Xdelta file for this mod could be made for Dolphin, but I sadly don't know how to make those. If someone actually knows how to make one, I'll gladly accept a pull request for that.   
