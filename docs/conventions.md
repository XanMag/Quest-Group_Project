
Quest Group Project Conventions
-------------------------------


_NOTE:_ This is currently a suggestion, and not a directive!


Anything Specific To Your Zone
------------------------------

All objects (and rooms) created in your zone must start with your unique identifier, which must be at least 2 letters long. This is to avoid two authors using the same name for something; Quest will not give any warning, but will quietly remove one from the game, and Murphy's law says it will be yours!

This also applies to functions, exits (if named), commands (if named), turn scripts, etc. Exits and commands without names are fine. Also any attribute for the player object that is specific to your zone. There should be no attributes set on the game object.


Anything General
----------------


Functions, objects (such as spells), verbs, commands that apply to all zones should be added to the library.

Attributes of the player object must be listed below. Names should be lowercase with no spaces, and succint but meaningful. They should be recorded in this document, with the type and any notes, which should include a note from any author intending to change it, and any restriction (eg health can be from 0 to 100).


Player attrributes
------------------

```
Attribute    Type     Notes
alias        String   Set during character creation
isfemale     Boolean  True indicates female
                      Set during character creation
race         String   Therace name in lower case, eg "human"
                      Set during character creation
```

---

Change log RH
---

|Action taken|Notes|Date|
|--|-|-|
|Added SHOWME command to library.|For testing purposes; displays ALL CHILD ITEMS of current room|07/23/2017|
|Added line of text explaining you can enter TRAVEL in hub room script|To let us know what to do|07/23/2017|

----
These are the attributes I've added in so far. 
RH
07/24/2017

---
RH_gateway_visited

Use:
player.RH_gateway_visited

This tells me if you've been to my dimension the first time, for greeting messages and other funky stuff.


---
RH_left_in_room

USE:
RH_hoe.RH_left_in_room

This tells me where the hoe should be if you drop it in a room before leaving my dimension. It will be in that room upon your return.


---


---
RE: Display / Theme
I tend towards a uniform scheme, but just change the status bar. I think that will make it feel like different parts within a single whole.
-Pixie

----

