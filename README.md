# Bloody Costmetics
Cosmetic Tweaks for NotBlood (and NBlood)! Normally for network play.

# What's the purpose?
These are meant to be something done for fun and to spice things up when playing Blood multiplayer. Thanks to the .DEF format used in EDuke32, one can replace graphics without directly modifying the game's contents. If done right, this will allow custom assets to be loaded without causing desyncs.

# Limitations
- Using Polymost is HIGHLY recommended! Otherwise not all graphics will be loaded correctly.
- Some graphic replacement aren't always friendly with transparency. The minimal HUD and inventory item icons are a example of this.
- Sound replacements can not be defined in .DEF (Can be done in EDuke32 but hasn't been implemented in NBlood/NotBlood yet)
- Custom sounds must match the frequencies of the original. And it must be in exported in .RAW Unsigned 8-bit PCM encoding, otherwise I am not reponsible for whatever happens to your eardrums.
This means you will need to drag and drop the .RAW files into the game's root directory.
- The resolution of tiles must match the original, otherwise the game will desync. However using 'texture' instead of 'tilefromtexture' can be a workaround given you are mindful about the automatic resizing and the fact you have to make varients with different colors. (palette color changing)

# Contributing
Contributions to this is welcome through pull requests.

Better yet, I recommend joining the NukemNet Discord as most of the Blood Multiplayer activity is in here.
https://nukemnet.com
