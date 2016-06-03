![argent](http://i.imgur.com/hzaQFBCm.png)

argent
=====

Argent (stylized "ARGENT") is a Classic Doom mod that brings the arsenal
from id's 2016 DOOM reboot into the hands of the OG Doomguy. The goal is
to create a faithful-yet-balanced recreation of the new game's weapons,
with just enough aesthetic 'oomph' to not distract from the classic Doom
gameplay style.

The mod is directly based on Neccronixis's [excellent spritework](http://forum.zdoom.org/viewtopic.php?f=37&t=51919),
so major props to him for effectively authoring this mod. Code, secret
sauce, and further sprite edits (pending) are by Xaser (me), with a few
miscellaneous credits flying about -- see credits.txt for more details.


Where to get
---------------------------
 - [angryscience.net](http://static.angryscience.net/pub/doom/mods/argent/) (archive of releases)

How to build locally
---------------------------

### Prerequisite modules

Despite not actually being a node.js project, this mod uses
[grunt](http://gruntjs.com/) for its build pipeline because
it happens to be the tool the Xaser-person had handy.

Make sure the following packages are installed on your machine
* node.js
* npm

### Install dependencies
```
argent$ npm install
```

### Build
```
argent$ grunt build
```

### Run
```
zdoom -file xa-argen.pk3
```

License
--------------------

While Argent is pending a formal license declaration for organizational
reasons, the code portions of this mod will be released under the
MIT License. More to come on this front soon.
