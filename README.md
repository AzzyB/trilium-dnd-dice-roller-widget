## D&D Dice Roller Widget for [Trilium Notes](https://github.com/zadam/trilium)

### Description: 
Alongside other things, I use my trilium notes to organize my ttrpg games (mainly D&D). Sometimes I go into my d&d notes to organize game notes or pull them up to play and sometimes don't have my bulky bag of dice on me. So I scrapped together a script that could do it right inside my notes. It also just works as a general dice roller for any purpose. 



### Features:
* D20 dice system; d4, d6, d8, d10, d20
* Select multiple die
* Record and display roll of each die selected
* Record and display total from all dice rolled
* Disable/Enable widget via promoted attibute
 
### Implementation:
1) Copy/paste this script into a "js frontend" code note.
2) Add the ```#widget``` to the "Owned Attributes" to enable the widget.
3) Add ```#label:diceRollerWidgetDisabled="promoted,alias=Disable Dice Roller Widget,single,boolean"``` to the "Owned Attributes" enabling toggle to enable/disable the widget.
4) Reload Trilium
