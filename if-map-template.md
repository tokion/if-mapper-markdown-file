# YOUR STORY: ___ | YOUR NAME: _____ | DATE: ___ | 
## INTERACTIVE FICTION AND TEXTADVENTURE AND INFOCOM MAPPING SHEET*
* *Use this sheet in your favourite text editor, with this settings:*
* *1. Wordwrap Off 2. Overwrite mode on (VIM example: ":set nowrap" AND "R" for Replace-mode)*
* *Works for mobile too! (Suggestion for Android: "DroidEdit" App with Drive Sync)*
* *This is basically a modified version of the ifm config file (http://ifm.readthedocs.io/)*
* *Works great with smaller IF with a clear and static map structure - Works for me - maybe not for you
* *Have fun!*

## THIS IS A MAP EXAMPLE (5-Letter-Room-Names)

    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .ROOM2.     .     .     .     .     .     .     .     .
    .............................................|...............................................................
    .     .     .     .     .     .     .     .ROOM1.     .     .     .     .     .     .     .     .     .
    .............................................|..............................................................
    .     .     .     .     .     .     .     .START-ROOM3.     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................

## ROOM-DESCRIPTION AND ITEMS

 * *** START ROOM: ____
 * 

## TODOS-LIST

 * ___

## LOG OF SOLUTION-STEPS

 * ____

# HELP SECTION

## RULES FOR MAPPING
It is a grid of spaces surrounded by periods initially. 

 * Spaces are grid squares where a room can be. 
 * The periods are places for room connectors. 
 * All rooms should be connected somehow.
 * Rules for lines:
   * *-* = connect rooms west-east
   * *|* = connect rooms north-south
   * *\* = connect rooms northwest-southeast
   * */* = connect rooms northeast-southwest
   * *X* = connect two pairs of rooms nw-se and ne-sw
   * *^* = connect two rooms in-out, laid out north-south
   * *V* = connect two rooms out-in, laid out south-north
   * *<* = connect two rooms in-out, laid out west-east
   * *>* = connect two rooms out-in, laid out east-west

## EXAMPLE IF COMMANDS (Each game has differences, but these commands are the most common):

  * FIRST COMMANDS AFTER EXERY STARTUP: 1. Help, 2. X self, 3. Inventory
  * FILE commands: Save, Restore, Quit, About, Info, Help, Undo
  * Directions: N/E/S/W/NE/SE/NW/SW: GO
  * Most used cmd with Shortcuts: (L)ook, e(X)amine, (I)nventory, (Z):wait, a(G)ain
  * Also most used commands: TAKE or GET it, PUSH it, PULL it, TURN it, FEEL DROP it, 
    OPEN it, PUT it IN something, EAT it, CLIMB it, WAVE it, WEAR it, TAKE it OFF, 
    TURN it ON, DIG IN it, ENTER it, SEARCH it, DRINKit, FILL it, SMELL it, LISTEN TO it, 
    BREAK it, BURN it, LOOK UNDER it, UNLOCK it WITH something, 
  * Or: LISTEN, SLEEP, WAKE UP, JUMP, PRAY, CURSE, SING
  * NPC-Interaction: TALK TO name, ASK name ABOUT something, TELL name ABOUT something, GIVE something TO name, SHOW something TO name

# ALTERNATIVE MAP LAYOUT TEMPLATES 

 * (TO USE: JUST COPY & PASTE, PASTE, PASTE,....):
 * VIM Example: 1. go to beginning of first line of map 2. copy 2 lines = "2yy" 3. Paste 15x with "15P"

## DEFAULT MAP LAYOUT: 5-LETTER-ROOM LAYOUT
    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................

## ALTERNATIVE MAP LAYOUT: 4-LETTER-ROOM LAYOUT
    ...........................................................................................
    .    .    .    .    .    .    .    .    .    .    .    .    .    .    .    .    .    .    .
    ...........................................................................................

## ALTERNATIVE MAP LAYOUT: 3 LETTER ROOMS
    .............................................................................
    .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .
    .............................................................................

## ALTERNATIVE MAP LAYOUT: 3 LETTER ROOMS, DOUBLE LENGTH
    .........................................................................................................................................................
    .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .
    .........................................................................................................................................................

    .............................................................................................................
    .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .     .
    .............................................................................................................
    
## 4th ALTERNATIVE MAP LAYOUT: 6-LETTER-ROOM LAYOUT
    ...............................................................................................................................
    .      .      .      .      .      .      .      .      .      .      .      .      .      .      .      .      .      .      .
    ...............................................................................................................................

