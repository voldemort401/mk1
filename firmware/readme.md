# FIRMWARE

This keyboard uses the qmk firmware i also have setup some keybindings that are pretty neat so this file also acts like a documentation for the keybindings 
before i go into the keybindings lets first see the keyboard layout 

┌──┐ ┌──┐┌──┐┌──┐┌──┐ ┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐
│es│ │f1││f2││f3││f4│ │f5││f6││f7││f8││f9││f1││f1││f1││de│
└──┘ └──┘└──┘└──┘└──┘ └──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘
┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──────┐
│~`││1 ││2 ││3 ││4 ││5 ││6 ││7 ││8 ││9 ││0 ││- ││+=││backsp│
└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──────┘
┌────┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐
│tab`││q ││w ││e ││r ││t ││y ││u ││i ││o ││p ││{ ││} ││| │
└────┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘
┌─────┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌───────┐
│capsl││a ││s ││d ││f ││g ││h ││j ││k ││l ││; ││' ││m ││Enter  │
└─────┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└───────┘
┌───────┐┌──┐ ┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐┌──┐
│shift  ││z │ │x ││c ││v ││b ││n ││m ││< ││> ││/ ││sh││up││fn│
└───────┘└──┘ └──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘└──┘
┌───┐┌───┐┌───┐┌───────────────────────┐┌───┐┌──┐┌──┐ ┌──┐┌──┐
│ctr││sup││alt││space                  ││alt││ct││ri│ │do││le│
└───┘└───┘└───┘└───────────────────────┘└───┘└──┘└──┘ └──┘└──┘

Ok now lets move on to the bindings 
 
Fn + q + b : puts the keyboard into bootloader mode 
Fn + q + c : reinitializes the keyboard's EEPROM
Fn + q + a : toggles autocorrect
Fn + q + super: toggles super key

personally my favorite mode the mouse mode 
this activates when you hold that "m" key next to the enter key when you hold this you can control your cursor as if you were using a mouse 
using your keyboard 

```
           q w e
  capslock a s d f
```
these are the keys used to navigate

wasd are pretty self explanatory 
q is for scroll up 
e is for scroll down 
capslock is for button 1 
f is for button 2 
