# File
### Preferences
#### Full Path and Name for TIE Fighter Program File
This specifies the actual TIE Fighter .exe file. You should enter the entire path, such as "c:\tie\tie.exe".
#### TIE Fighter Directory
This specifies the TIE Fighter directory. For example; c:\tie.
#### TIE Fighter Resource Directory
This specifies the TIE Fighter Resource directory, such as "c:\tie\resource". This directory is where the battlexx.lfd files are kept and must be correct for the Battle Manager to function properly.
#### TIE Fighter Mission Directory
This specifies the TIE Fighter Mission directory, such as "c:\tie\mission". This directory is where the .TIE files are kept and must be entered correctly for the Battle Manager to work correctly.
#### Display FG Names In Breifing
When this box is checked, the names of the flight group will appear next to that flight group's dot in the breifing display. This makes it easier for you to identify which dot is which.
#### Display FG Types In Breifing
When checked, this option displays the ship type of each flight group next to that flight group's dot in the breifing display, making it easier to identify dots.
#### Stop On Breifing Stop Points
When this option is checked, breifing playback will stop when a breifing stop points is reached.
#### Use Short IDs in Message List Box
When checked, this option will display a message's short id in the message list instead of the entire message.
#### Check Mission Errors During Save
When this option is checked, your mission will be checked for serious errors each time it is saved. Such errors include having too many ships in a flight group, or not specifying which flight group the player should fly in.
#### Delete Preferences From Registry
The options listed above are stored in the registry. Clicking this button will delete all preferences from the registry. This option was included to ease uninstallation of the program. To uninstall, click this button, exit the program, and delete all the files in the program's directory.

# Mission 
### End of Mission Messages
#### Primary Mission Success - Messages 1 & 2
These messages are shown on the status bar at the bottom of the TIE Fighter screen when all of the primary goals are completed. You can view the primary goals in the Mission | Mission Goals dialog.
#### Primary Mission Failure - Messages 1 & 2
These messages are shown on the status bar at the bottom of the TIE Fighter screen when the primary goals are failed. You can view the primary goals in the Mission | Mission Goals dialog.
#### Secondary Mission Success - Messages 1 & 2
These messages are shown on the status bar at the bottom of the TIE Fighter screen when the secondary mission goals are completed. You can view the secondary mission goals in the Mission | Mission Goals dialog.

### IFF Codes
The IFF Codes Dialog allows you to specify additional IFF Codes to use in your mission. Each IFF Code has a color and can be assigned a name and an enemy status. Using new IFF Codes allows you to create new races such as "Mugaari" in addition to the default IFFs, "Rebel" and "Imperial."
#### Name
For each IFF, type in the name you wish to assigned to it, such as "Mugaari".
#### Enemy/Hostile IFF
When this box is checked, the IFF will appear to be an enemy. That is, it will be selected when you press the "select nearest enemy" button in TIE Fighter.

### Global Goals
This dialog allows you to specify global mission goals. Such goals include "100% of all X-Wings must be destroyed" or "75% of all imperial craft must be destroyed". Global goals can be specified for the primary, secondary, and bonus goals.
#### Goal Selector
This allows you to pick between the primary, secondary, and bonus global goals.
#### Goals
Set each goal using the four drop-down lists. The first selection specifies what the goal will depend on, such as a flight group or an IFF Code. The next selection sets the percentage that must be affected by the action. The next selection is the parameter. For example, if you selected Flight Group above, you must select a flight group in this box. The last box selects the action, such as destroy, create, identify, etc. You can specify up to two global goals for each goal set (primary, secondary, or bonus). The two goals can be combined with either an AND or an OR operator.

### Player's Flight Group
#### Flight Group
This control selects the flight group that the player will fly in. For TIE Fighter to work properly, this flight group's ship type must be TIE Fighter, TIE Bomber, TIE Interceptor, TIE Advanced, Assault Gunboat, and possibly TIE Defender or Missile Boat if you have the Defender of the Empire add-on.
#### Position
This sets the player's position within the flight group. If set to 1, the player's craft will be the first and lead craft in the flight group. Otherwise, you will be in the nth position in the formation. This value must be between 1 and the number of craft in the flight group.
#### Ejection Results 
This specifies whether or not the player's pilot will be captured or rescued in the event that the player's craft is destroyed and the player successfully ejects.

# Briefing 
### Options
#### Officers Present At Briefing
This specifies which people will be at the briefing. Options are none, Flight Officer, Secret Order Officer, or Both.
#### Briefing Reset Time - Minutes, Seconds, .01 Seconds
This sets the duration of the briefing. After this time, the briefing will loop back to the beginning.
#### Unknown Parameters
Just like it sounds, these parameters are unknown. Leaving them set to zero seems to work fine.

### Briefing Questions
In this dialog, you can specify the questions and answers that are available during the briefing with either the Flight Officer or the Secret Order Officer. Questions that are asked after the mission can be set to only appear when certain conditions are met (i.e. the player failed the mission). There are four question "categories," consisting of the pre-mission officer and secret order questions and the post-mission officer and secret order questions. For each question category, you can specify up to five questions.
#### Question Category
Here, you can select which set of questions to edit. You can select from the pre or post mission officer and secret order questions.
#### Question Number
This selects which of the five questions in the current category to edit.
#### Displays When
For post-mission questions, you can specify a condition that must be met for the question to be displayed.
#### Question Data
This is where you type the actual question and answer. The first line is the question. All following lines are the answer to the question. To highlight text in TIE Fighter, enclose it in brackets ("[" and "]"). To insure that lines are not too long for TIE Fighter, the length of each line should not exceed the width of the box.

# Message Editor
#### Message
This is the actual message that is displayed along the status bar in TIE Fighter when the condition for the display of the message is met.
#### Short Message
This can be used to shorten the message that is displayed in the messages list. It is not used in TIE Fighter.
#### Message Color
The color that the message will appear on the status bar in TIE Fighter.
#### Conditions
The conditions are set using the standard four parameter TIE Fighter condition system. The first parameter is the one that sets what the rest depend on, such as flight group or IFF Code. The next specifies the percent that must complete the condition. The next is the parameter. If IFF Code was selected above, you could pick from Rebel, Imperial, etc. The last is the action, which sets that the group must be destroyed, attacked, identified, etc. You can specify up to two conditions and use either the AND operator or the OR operator.
#### Time Delay
This sets the delay in seconds after the condition is met that the message will be displayed.

# Ship Editor 
## General
#### Flight Group
This specifies the name of the flight group. This is the name that is displayed in TIE Fighter when the flight group is selected in the CMD. The name can be up to 12 characters in length.
#### Pilot
This specifies the name of the flight group's pilot. This value is not currently used by TIE Fighter. The name can be up to 12 characters in length.
#### Cargo
This specifies the flight group's cargo. The cargo is displayed in the CMD when the flight group is selected and it has been inspected. The name can be up to 12 characters in length.
#### Ship Type
This sets the flight group's ship type, such as TIE Fighter, X-Wing, Star Destroyer, etc. Note that the player's flight group must be a TIE Fighter, Bomber, Interceptor, TIE Advanced, TIE Defender, Assault Gunboat, or Missile Boat. Clicking the "..." button next to the ship type list will bring up a dialog box with each ship type split into multiple categories, making it easier to select a ship type.
#### Side/IFF
This property sets which "side" the flight group will be on and what color it will appear to be in the CMD and on the briefing map. Additional IFFs can be specified in the IFF Codes dialog box, which can be accessed from the Mission | IFF Codes... menu command.
#### Pilot Skill
This property sets the skill of the computer pilots who will fly the ship(s) in this flight group. Note that if the pilot skill is set to Top Ace, the flight group will be invincible.
#### Formation
This sets the formation that the flight group will fly in if there are more than one craft in the flight group. Clicking the "..." button next to the formation selector will bring up a dialog box with a list of formations and a picture of how the flight group will be arranged.
#### Markings
This sets the color of the markings that will appear on the side of the craft. This is mainly used for Rebel starfighters, but it effects some other craft as well.
#### Group Obeys Player's Radio Orders
This determines whether or not this flight group will listen to the player's radio orders, such as "attack my target," etc, which are activated in the game by selecting the flight group and pressing SHIFT-A, etc.
#### Special Cargo Name
This will specify the flight group's special cargo. A special cargo will be carried by only one ship in the flight group.
#### Special Ship's Position
This specifies which craft in the flight group will be carrying the special cargo. Numbering starts at zero for the first craft in the flight group and continues upwards. Entering a number greater than the number of craft in the flight group - 1 will cause no ship in the flight group to carry the special cargo. Leaving the value blank will have the same effect.
#### Random Special Ship Position
When checked, this will cause the craft with the special cargo to be randomly picked from one of the craft in the flight group each time the mission is played.
#### Number of Ships in FG
This controls how many craft will be in the flight group.
#### Number of Waves
This specifies the number of waves the flight group will have. Once every ship in the flight group is destroyed, a new "wave" will arrive 'n' more times, depending on the waves value. If set to zero, once the original flight group is destroyed, no more will arrive.
#### Status/Planet Type/Asteroid Size
This controls the general status of the flight group. All craft in the flight group will have the same status. If the current ship type is "Planet", status will be changed to the type of planet to display. If the current ship type is "Asteroid Field", status will be changed to the size of the asteroids to display.
#### Missile
This control which missile/torpedo the flight group will have, if any. Note: some missiles may only be available with particular add-ons to the game.
#### Beam
This control which beam weapon the flight group will have, if any. Note: some beam weapons may only be available with particular add-ons to the game. Note: equipping certain craft with beam weapons when they were not originally designed to be equipped may resort in distortion of the cockpit during game play.

## Win Conditions
#### Primary, Secondary, Secret and Bonus Goals
First select the percentage of the flight group that must meet the condition, then the condition that they must meet. For the bonus goal, specify a number of points that will be added to the player's score if the bonus goal is completed.

## Arrival
#### Flight Group Only Arrives On This Difficulty Level
Use this control to specify what the game's difficulty level must be for this flight group to arrive.
#### Arrival Conditions
Specify the arrival conditions and use the AND or OR operators to combine them.
#### Arrival Delay
Specifies the delay in minutes in seconds after the conditions are met that the flight group will arrive.

## Departure
#### Flight Group Will Stop Its Mission When
This specifies the condition that, when met, will force the flight group to stop attempting its mission.
#### Departure Condition
This specifies the condition that, when met, will cause the flight group to depart the area.

## Arrival and Departure Methods
Specify the normal and alternate arrival and departure for the flight group. The alternate conditions allow you to specify more than one mothership for a craft, or allow you to create craft that will hyperspace out when their mothership is not present. You only need to specify a flight group when the mothership radio button is checked. The flight group is ignored if the hyperspace radio button is checked.

## Orders
#### Order Number
You can specify up to three separate orders for each flight group. This selects which order to use. Orders are attempted in ascending order. Some orders will cause TIE Fighter to ignore all following orders. These orders are noted in the order descriptions.
#### Order
Selects the order that the flight group will attempt. Generally, you should specify orders that apply to the type of ships in the flight group. For example, do not give a group of TIE Fighters the order to board and capture another craft. The "..." button brings up a list of the most commonly used orders and a button for access to descriptions of what all the orders do. Click here to view descriptions of all orders and how they cause ships to function in TIE Fighter.
#### Percent of Full Speed
This selects the percent of full speed that the flight group will fly at when attempting to complete the order.
#### First Parameter & Second Parameter
These specify order-specific parameters. If the parameter is unknown, it is generally ok to leave it set to zero.
#### Targets
Specify the targets for the order. For example, if you have specified the order "attack target," then these targets will be attacked.

## Navigation
**TODO**: Format this better. 

Here, you can specify the flight group's start points, waypoints, briefing point, rendezvous point, and hyperspace point. You can also use the mission map to modify these points in a more visual manner. Putting a one in the first column activates the point, while a zero inactivates it. Specifying more than one start point will cause TIE Fighter to randomly pick one of the points for the flight group to arrive at. If the flight group has orders that required waypoints, you can specify up to eight waypoints. The flight group will circle through the waypoints and return to the first one. Additionally, the flight group will face towards its first waypoint when it arrives. The rendezvous point is used in conjunction with the rendezvous order. If you give a ship the rendezvous order, it will fly to its rendezvous point and await boarding. The briefing point is the point where the flight group appears on the briefing map. If this point is unused, the ship will not appear on the briefing map. The hyperspace point is the point the ship must reach to enter hyperspace. Clicking the "clear all points" button will set all items to "0.00" and uncheck all of the check boxes.

## Unknown
**TODO**: Enter info about the two unknown values.

# Mission Map 
#### Start Points
Each flight group can have up to four start points. One of these start points will be chosen randomly each time the mission is played.
#### Waypoints
Each flight group can also have up to eight waypoints. If the flight group's orders require it, the flight group will travel through the waypoints in order. In addition, the flight group will always start facing its first waypoint.
#### Rendezvous Point
A flight group can also have a rendezvous point, which is used in conjunction with the rendezvous order. When a flight group is given the rendezvous order, it will travel to its rendezvous point and wait to be boarded.
#### Hyperspace Point
When a flight group's order direct it to enter hyperspace, it must first travel to its hyperspace point. If no hyperspace point exists, the flight group will immediately enter hyperspace.
#### Map
The scroll bars on the sides of the map move the focus of the map. The slider below the map controls the zoom of the map. To move a point, click and drag the point around. The current X, Y, and Z values, as well as the current zoom value, are displayed in the status bar below the map. Right clicking on the map will center the map where you right-clicked.
#### Axis
The axis of the map can be one of three values, X/Y, X/Z, and Y/Z. To explain: First, think of a cube, representing the arena in which the game is played. With axis at X/Y, you are looking down at the cube from the top. If you set the axis to X/Z, you are look at the cube from the front. If you set the axis to Y/Z, you are looking at the cube from the side.
#### Show xxx Check Boxes
Check and uncheck these boxes to show or remove certain flight groups from the map. The grid can also be removed from the map.
#### Ship Selection
The ship selection list, at the bottom of the window, shows the selected flight group. When a new flight group is selected, the map will be centered on that flight group's first start point.
#### Show Only Current
When checked, the map will only display the currently selected flight group's points.
#### Show All For Current
When checked, all of the currently selected flight group's points will be shown along with whatever other flight group's points are on the map.
#### Points To Use Button
This button will bring up a dialog box allowing you to edit which points the currently selected flight group will use. If you have just created the flight group, no points will be selected. In this dialog box, you can also type in X, Y, and Z values for the position of each point.
#### Relative Dot Sizing
This option causes the dots of larger craft to appear larger than the dots of smaller craft. This feature is now highly accurate, as ships will point (with the arrow on the box) in the direction they would at the start of the mission. In addition, each ship appears on the map the exact length, width, and height that it is in the game. This feature can help immensly in ensuring that one flight group is not placed on top of another. Note: A display showing more than 256 colors is required for this feature to work. If such a display is not present, or the current video mode has 256 colors or less, the check box will be disabled.
#### Points Sets
The three point set radio buttons allow you to use and switch between three point sets. If the map always showed every one of each flight group's points, the map would be uselessly cluttered. For each point set, you can pick which points to show on the map by clicking that point set's "..." button. You can also name each point set. Then, you can easily switch between point sets and insure that only what you want to see on the map is displayed.
#### Copy Points
This dialog box allows you to copy points from one flight group to many other flight groups.
### Edit Point Set
#### Name
Type the name you wish to give this point set here.
#### Check Boxes
Check or uncheck these boxes to choose which points will be displayed on the map.
### Copy Points Dialog
#### From Flight Group
This selects which flight group points will be copied from.
#### From Point
This selects which point in the "from flight group" will be copied.
#### To Flight Groups
Here, multiple flight groups can be selected that points will be copied to.
#### To Point
This selects which point will be copied to.
#### Overwrite Used Points
When checked, points that are already in use will not be overwritten.
### Visible Points Dialog - Is this the Points to Use Dialog?
#### Check Boxes
Check these boxes if you wish the flight group to use that particular point. When checked, a point will appear on the map (provided that the map's display check boxes are set appropriately) and the point will be used in TIE Fighter. You can also enter actual numbers here representing where to place the point. Be sure to enter numbers (yes, -1.03 is OK)! Not letters, not words, just numbers!

# Briefing Map
#### Map
The scroll bars on the sides of the map move the focus of the map. The slider below the map controls the zoom of the map. To move a point, click and drag the point around. The current X, Y, and Z values, as well as the current zoom value, are displayed in the status bar below the map. Right clicking on the map will center the map where you right-clicked.
#### Show xxx Check Boxes
Check and uncheck these boxes to show or remove certain flight groups from the map. The grid can also be removed from the map.
#### Selected 
The ship selection list, at the bottom of the window, shows the selected flight group. When a new flight group is selected, the map will be centered on that flight group.
#### Show Current Ship in Briefing
When checked, the currently selected flight group will be shown in the briefing and on the briefing map. If unchecked, the flight group will not appear on the briefing or on the map.
#### Inherit Start Points
When clicked, each flight group will appear on the briefing map in the same position as its first start point. However, all current locations on the briefing map will be lost.

# Mission Editor Window
The mission editor window consists of three tabs.
### Ships Tab
This is the flight group editor of the TIE Fighter Mission Builder. Double click on a flight group to edit it. You can press insert and delete to create or destroy flight groups, or you can use the menu command, Ships | New Ships or Ships | Delete Ship. Clicking the new button creates a new flight group, while clicking the delete or duplicate buttons will delete or duplicate the selected flight group. You can also select multiple flight groups and use the cut/copy/paste commands between mission files or in the same mission file.
### Messages Tab
This sheet is the message editor. Double click a message to edit it. Create and delete messages using the menu commands Messages | New Message and Messages | Delete Message or by pressing insert and delete. Clicking the new button creates a new message, while clicking the delete or duplicate buttons will delete or duplicate the selected message. You can also select multiple messages and use the cut/copy/paste commands between mission files or in the same mission file.
### Briefing Tab
Note: It is generally a good idea to maximize both the TIE Fighter Mission Builder window as well as the mission window when working with briefings. This will increase the accuracy of the locations of items displayed on the map.

Briefing Events

TIE Fighter briefings consist of events. Each event can be placed at any time during the briefing. In the TIE Fighter Mission Builder, you use the toolbar on the briefing sheet to insert events at the current time. From left to right on the toolbar, events and their descriptions follow.

Move Map         Repositions the map.
Zoom Map         Zooms the map in or out.
Text Tag         Puts a text tag on the briefing map. The tag will stay on the map until another tag takes its place or until a "clear all text tags" event is reached.
Title Text       Changes the text at the top of the briefing.
Caption Text     Changes the text at the bottom of the briefing
Flight Group Tag         Puts a box around the flight group. The tag will stay on the map until another tag takes its place or until a "clear all flight group tags" event is reached.
Clear All Text Tags      Clears all text tags from the map from the current point in time onward.
Clear All Flight Group Tags      The same as clear all text tags, but for flight group tags.
Stop Point       Inserts a stop point in the briefing. When you click the fast forward button in the TIE Fighter briefing, it skips ahead to the next stop point.

Briefing Display

The briefing display shows the briefing as it would look in TIE Fighter. Use the toolbar to add events to the briefing. Use the play/stop/rewind/ff/step forward and back buttons at the bottom of the window to control briefing playback.

Text Tags

Text tags are snippets of text placed on the briefing to describe nearby objects. You can place text tags anywhere on the map by clicking the add text tag toolbar button, then clicking on the briefing display where you want the tag to appear. You can drag existing tags to move them or double click them to edit their properties.

Flight Group Tags

Flight Group Tags appear as boxes around flight groups. You can create a flight group tag using the Tag Flight Group toolbar button. Double click an existing flight group tag to delete it.

Flight Group Positions

To alter which flight groups are shown on the briefing map and their positions, use the Briefing | Briefing Map dialog box.



# Order Descriptions
The following list of orders is fairly complete and a great amount of effort has been put into making it accurate. However, much is still unknown about how TIE Fighter handles each order, so some descriptions are incomplete.
## Labels
| Label | Description |
| ----------- | ----------- |
| Movement | Identifies how the flight group is flying. If two descriptions are given (i.e. "patrolling waypoints" and "attacking all targets present"), the first action is what the flight group will do if its target has not yet been created in the mission, but will arrive later. The second action is what the flight group will do when its target is present. It is important to realize that if it is not specifically noted that the flight group will "acquire" targets, then the flight group will NOT deviate from its flight plan. This means that non-turreted ships will not turn to attack their attackers or attack their targets.  |
| Defense | Identifies how the flight group will respond to attacks made on it outside of mission parameters (i.e. obviously a flight group which has orders to attack its target will attack its targets, but what does the flight group do when it is patrolling its waypoints before its target arrives, and the player attacks it?) This applies to ALL ships that fire upon this ship, no matter what IFF, type, etc. |
| Value 1 | This refers to the left-hand multi-functional adjustable value below the selected order in TFW. |
| Value 2 | This refers to the right-hand multi-functional adjustable value below the selected order in TFW. |
| Targets | Identifies the targets that the flight group will take its action upon (selected in the target designator at the bottom of the order selection screen in TFW). |
| Action when complete | Identifies what the flight group will do once the current order has been successfully completed. |
| Notes | Whatever didn't fit into another category. |
## Orders
### Hold Station
| Label | Description |
| --- | --- |
| Movement | Stationary. | 
| Defense | Turreted ships will return fire if fired upon. Non turreted ships will ignore all attacks. | 
| Value 1| Meaningless. | 
| Value 2| Meaningless. | 
| Targets | No effect. | 
| Action when complete | This order is never considered completed. | 
| Notes | Hold Station will ONLY work if it is the FIRST order.  If this order is the second or third order, the ship will go to its hyperspace point/mothership instead. | 
### Go Home I
| Label | Description |
| --- | --- |
| Movement | Heads directly to hyperspace point or mothership. | 
| Defense | Ignores all attacks. | 
| Value 1| Meaningless. | 
| Value 2| Meaningless. | 
| Targets | No effect. | 
| Action when complete | Ship will have left mission if this order is successfully completed. | 
| Notes | None. | 
### Circle 
| Label | Description |
| --- | --- |
| Movement | Circles through designated waypoints. | 
| Defense | Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks. | 
| Value 1| If set to 0, ship will head straight to hyperspace point/mothership. Otherwise, this is the number of times ship will circle through waypoints before this order is considered successfully completed. | 
| Value 2| Meaningless. | 
| Targets | No effect. | 
| Action when complete | Ship will go to hyperspace point/mothership. | 
| Notes | None. | 
### Circle and Evade 
| Label | Description |
| --- | --- |
| Movement | Circles through designated waypoints, making evasive maneuvers if fired upon. | 
| Defense | Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks. | 
| Value 1| If set to 0, ship will head straight to hyperspace point/mothership. Otherwise, this is the number of times ship will circle through waypoints before this order is considered successfully completed. | 
| Value 2| Meaningless. | 
| Targets | No effect. | 
| Action when complete | Ship will go to hyperspace point/mothership. | 
| Notes | None. | 
### Rendezvous 
| Label | Description |
| --- | --- |
| Movement | Flies directly to designated rendezvous waypoint, then waits for boarding. | 
| Defense | Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks. | 
| Value 1| If set to 0, ship will head to its rendezvous point, and then straight to hyperspace point/mothership. Otherwise, this is the number of times ship must be docked with before this order is considered successfully completed. | 
| Value 2| Meaningless. | 
| Targets | No effect. | 
| Action when complete | Ship will go to hyperspace point/mothership. | 
| Notes | None. | 
### Awaiting Boarding (Disabled) I & II
| Label | Description |
| --- | --- |
| Movement | Stationary (systems at 0%). | 
| Defense | Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks. | 
| Value 1| If set to 0, this order will never be successfully completed. Otherwise, this is the number of times this ship must be docked with for this order to be considered successfully completed. | 
| Value 2| Meaningless. | 
| Targets | No effect. | 
| Action when complete | Ship will go to hyperspace point/mothership (systems at 100%). | 
| Notes | Awaiting Boarding (Disabled) I & II appear to function identically. | 

Attack Target    Movement: Patrols designated waypoints, or acquires and attacks all targets present.
         Defense: unsure, will test soon...
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Ship will attack any and all targets designated here. If the mission has NO targets of this type at any time, or if all the designated targets have been destroyed, this order is considered successfully completed.
         Action when order completed: Ship will go to next order.
         Notes: None

Attack Escorters         Movement: Patrols designated waypoints, or acquires and attacks all targets with escort orders present.
         Defense: unsure, will test soon...
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Ship will attack any and all targets designated here IF THEY HAVE ESCORT ORDERS. If the mission has NO targets of this type at any time, or if all the designated targets have been destroyed, this order is considered successfully completed.
         Action when order completed: Ship will go to next order.
         Notes: If a ship with this order has been patrolling its waypoints, and then a ship of the designated target type arrives, with or without escort orders, the patrolling ship will then move to its next order WITHOUT attacking the designated targets. Use two of these orders one right after the other to solve this problem, and I'm still trying to figure this out.

Protect  Movement: Patrols designated waypoints, or acquires and attacks all ships attacking its designated targets.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Ship will attack any and all ships that are ATTACKING the targets designated here.
         Action when order completed: This order is never considered completed (I think).
         Notes: It is my humble opinion that you should use this order instead of Escort whenever possible, as it seems to work better.

Escort   Movement: Flies alongside designated targets, or acquires and attacks ships attacking targets.
         Defense: unsure, will test soon...
         Value 1: Meaningless.
         Value 2: Designates this ship to attack PLAYER CRAFT by default, at almost all times.
         Targets Designated: Ship will attack any and all ships that are ATTACKING the targets designated here, EXCEPT if the attacker is the PLAYERS CRAFT, in which case s/he will be ignored. Use Value 2 to solve this problem.
         Action when order completed: This order is never considered completed.
         Notes: Protect seems to work much better than this order.

Disable Target   Movement: Patrols designated waypoints, or acquires and attacks with intent to disable designated targets.
         Defense: unsure, will test soon...
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Ship will attack, with intent to disable, all ships designated here. It will use its missiles to lower shields, but will NOT fire their normal blasters. Ships without ion cannons will set up for attack runs, but will not fire their normal blasters.
         Action when order completed: Ship will go to next order.
         Notes: None

Board and Give/Take/Exg/Capt/Con         Movement: Stationary, or flies to designated targets.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Time (x5) in seconds that will be required to complete a successful boarding.
         Value 2: Number of times to dock, I think... unsure exactly what it does, still.
         Targets Designated: Ship will fly to all ships designated here and dock with them, so long as they are stationary (NOT Wait). If the target does not exist at all in the mission, or upon the successful completion of all boarding operations, this order is considered successfully completed.
         Action when order completed: Ship will go to next order.
         Notes: Experiment with this order somewhat, it isn't too hard to get to work properly but sometimes takes a little meddling. Ships that HAVE BEEN boarded act as follows:
         If it was holding station, it will continue to do so indefinitely.
         If it was Awaiting Boarding (Disabled), it will either go to its hyperspace point/mothership, or remain disabled, depending on the number of boardings required as set in the orders for that ship. It does NOT go to its next order.
         If it was disabled in combat, it will then automatically go to its hyperspace point/mothership. It does NOT go to its next order.

Pick Up Craft    Movement: Stationary, or flies to designated targets.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Time (x5) in seconds that will be required to complete a successful docking.
         Value 2: Meaningless.
         Targets Designated: Ship will fly to all ships designated here and dock with them, so long as they are stationary (NOT Wait). If the target does not exist at all in the mission, or upon successful completion of the docking, this order is considered successfully completed. Target craft will be physically attached to this ship for the remainder of the mission.
         Action when order completed: Ship will go to next order.
         Notes: The target craft will be physically attached to this ship for the remainder of the mission, and will be towed about wherever this ship goes. It's probably a good idea to set the targets mothership and arrival/departure methods via this ship. As with Boarding, mess around with this to get best results.

Drop Off Craft   Movement: Flies to first designated waypoint.
         Defense: Non-turreted ships ignore all attacks. Turreted ships return fire if fired upon.
         Value 1: Meaningless (for now)
         Value 2: Number of the flight group being dropped off (first FG is zero)
         Designated Target: No effect
         Action when order is completed: Ship will go to next order.
         Notes: In order to get this to work properly, then the "arrival" conditions of the flight group BEING DROPPED OFF should be set to "arrives when flight group (x) is dropped off" with 0 time delay, where (x) is the number of the flight group BEING DROPPED OFF. For integrity's sake, you may want to set the arrival/departure methods as "Mothership" and set the mothership to the flight group DOING THE DROPPING OFF. It may ALSO work (though I haven't tested it this way but it shows up this way in some TIE missions) if you set "arrive when flight group (x) is dropped off", and set (x) to the flight group DOING THE DROPPING OFF. There may be more ways to use it than this, but these should work adequately. (I'm still trying to figure out how to get the craft being dropped off to exist but be attached to the craft doing the dropping off... ie, having a heavy lifter hyperspace in-system towing a container, rather than the above-mentioned system in which the container will just "appear" when the heavy-lifter does its thing at the first waypoint).

Wait I   Movement: Stationary.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Time (x5) in seconds before order is considered completed.
         Value 2: Meaningless.
         Targets Designated: No effect.
         Action when order completed: Ship will go to next order.
         Notes: None

Wait II  Appears to be identical to Wait I.

Patrol Loop      Movement: Patrols designated waypoints.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: This is the number of times to circle through all designated waypoints before this order is considered successfully completed.
         Value 2: Meaningless.
         Targets Designated: Turreted ships will open fire on all designated targets as soon as they are in range - Non turreted ships will take no action on designated targets.
         Action when order completed: Ship will go to next order.
         Notes: Fairly useless for non turreted ships.

Await Return     Movement: Stationary.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Turreted ships will open fire on all designated targets as soon as they are in range - Non turreted ships will take no action on designated targets.
         Action when order completed: Ship will go to next order.
         Notes: This order will be considered successfully completed when all ships in the mission with this ship as their mothership have been destroyed or have returned to its hangar.

Await Launch     Movement: Stationary.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Turreted ships will open fire on all designated targets as soon as they are in range - Non turreted ships will take no action on designated targets.
         Action when order completed: Ship will go to next order.
         Notes: This order will be considered successfully completed when all ships in the mission with this ship as their mothership have been created/launched.

Patrol and Protect I     Movement: Patrols designated waypoints and attacks (but does not acquire) attackers of designated target.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Turreted ships will open fire on all designated targets as soon as they are in range - Non turreted ships will take no action on designated targets.
         Action when order completed: This order is never considered completed.
         Notes: Fairly useless for non turreted ships.

Patrol and Protect II    Appears to be identical to Patrol and Protect I.

Patrol and Attack        Movement: Patrols designated waypoints and attacks (but does not acquire) designated targets.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Turreted ships will open fire on all designated targets as soon as they are in range - Non turreted ships will take no action on designated targets. If all the targets have been destroyed, or if no targets of the designated type exist at all in the mission, this order will be considered completed.
         Action when order completed: Ship will go to next order
         Notes: Fairly useless for non turreted ships.

Patrol and Disable       Movement: Patrols designated waypoints and disables (but does not acquire) designated targets.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: Turreted ships will open fire, with intent to disable, on all designated targets as soon as they are in range - Non turreted ships will take no action on designated targets. If all the targets have been destroyed, or if no targets of the designated type exist at all in the mission, this order will be considered completed.
         Action when order completed: Ship will go to next order
         Notes: Fairly useless for non turreted ships.

Hold Steady I    Movement: Stationary.
         Defense: Ignores all attacks.
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: No effect.
         Action when order completed: This order is never considered completed.
         Notes: Similar to Hold Station, but I think this one can be used at any point and the ship won't zip off into hyperspace on you.

Go Home II       Movement: Heads directly to hyperspace point or mothership.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Meaningless.
         Value 2: Meaningless.
         Targets Designated: No effect.
         Action when order completed: Ship will have left mission if this order is successfully completed.
         Notes: None

Hold Steady II   Appears to be identical to Hold Steady I.

Board I  Movement: Stationary, or flies to designated targets.
         Defense: Turreted ships will return fire if fired upon - Non turreted ships will ignore all attacks.
         Value 1: Time (x5) in seconds that will be required to complete a successful boarding.
         Value 2: Number of times to dock, I think... unsure exactly what it does, still.
         Targets Designated: Ship will fly to all ships designated here and dock with them, so long as they are stationary (NOT Wait). If the target does not exist at all in the mission, or upon the successful completion of all boarding operations, this order is considered successfully completed.
         Action when order completed: Ship will go to next order.
         Notes: I'm not sure what makes this different from the other five Board and --- commands, but I'll keep working on it. Experiment with this order somewhat, it isn't too hard to get to work properly but sometimes takes a little meddling. Ships that HAVE BEEN boarded act as follows:
         If it was holding station, it will continue to do so indefinitely.
         If it was Awaiting Boarding (Disabled), it will either go to its hyperspace point/mothership, or remain disabled, depending on the number of boardings required as set in the orders for that ship. It does NOT go to its next order.
         If it was disabled in combat, it will then automatically go to its hyperspace point/mothership. It does NOT go to its next order.

Board II         Appears to be identical to Board I.

Hold Steady III  Appears to be identical to Hold Steady II.

Hold Steady IV   Appears to be identical to Hold Steady III.

Go Home III      Appears to be identical to Go Home II.

Evade Waypoint I         Currently unknown...

Evade Waypoint II        Appears to be identical to Evade Waypoint I.

Rendezvous II    Hmmmm...

Awaiting Boarding (Disabled) III         Appears to be identical to Awaiting Boarding (Disabled) II.

#Battle Manager
The TFW Battle Manager allows you to swap entire battles in and out of TIE Fighter. Since TIE Fighter can only have 20 battles installed concurrently, the Battle Manager allows you to import and export battles to move out battles that you have completed and insert new ones.

Battles List

This list box lists all 20 battles currently installed in TIE Fighter. If a battle is installed in the current slot, the name of the battle will be displayed. If a slot is not occupied by a battle, the text "empty" is displayed.

Export Button

This button exports the currently selected battle. The export button copies the .LFD file and all related .TIE files for the current battle into a separate directory. Once the button is clicked, a dialog box appears where you enter the name and directory of the LFD file to be created. Be sure to include the .LFD extension. This specifies the name of the file that will contain the battlexx.lfd data. In addition, all the .TIE files for the current battle will be copied to the same directory that the .LFD file was created in. Note that NO files in any TIE directory are deleted.

Import Button

The import button allows you to import a battle into TIE Fighter. The currently selected slot must be empty. When you click the button, a dialog box appears. Enter the name of the .LFD file (battle file) that you wish to import into TIE Fighter. All .TIE files for the battle MUST be in the same directory as the .LFD file. The Battle Manager will import the battle into TIE Fighter. You will now be able to play the new battle in TIE Fighter. Note: some battles will only become available in TIE Fighter after previous ones are beaten. If you are having problems with this, try either completing more battles or importing into a lower slot.

Delete Button

This button will ask for confirmation, then delete ALL files related to the currently selected battle. The battlexx.lfd file and ALL .TIE files WILL BE DELETED. Use this command with caution.


#Battle Editor
The battle editor allows you to create and edit .LFD files containing TIE Fighter battles. Original TIE Fighter battles can be found in the TIE Fighter directory named battlexx.lfd, where xx is the battle number.

Note: Battle files cannot be given long file names!!! Information within each .lfd file must match the name of the file, and only 8 characters are allowed.

General Sheet

Battle Name

This specifies the name of the battle as it will appear in TIE Fighter and the battle manager dialog. In most of the original TIE Fighter battles, the entire string is capitalized, although this is not required.

Cutscene Name

This specifies the name of the cutscene as it will appear in TIE Fighter. In most of the original TIE Fighter battles, this is also capitalized, although doing so is not required.

Battle Titles

These two lines specify the description of the battle in TIE Fighter.

Cutscene Titles

These two lines specify the name of the cutscene in TIE Fighter. Since battles that aren't part of the original game do not have a corresponding cutscene, it is a good idea to write a message here, warning the user that viewing the cutscene will crash TIE Fighter (and it will).

System Name

This is the name of the system where the battle takes place. The name is written below the box when the battle is first highlighted.

Missions Sheet

This sheet allows you to add and delete missions from the battle, and to write the description of each mission. When a mission is selected, its description is displayed in the right-hand panel. You can type a new description or edit what exists. Missions are played from the top to the bottom of the list, regardless of their names. In addition, the mission file names need not follow any naming convention, although this is often done.

Add Button

Clicking this button allows you to add a mission to the list. For the battle to be used by the battle manager, the mission file (.TIE file) must be in the same directory as the battle (.LFD) file. In addition, mission files with long file names will cause TIE Fighter to crash.

Delete Button

This button removes the currently selected mission from the battle. It does not delete any files, it merely removes the mission's filename from the list.

Move Up Button

This button moves the selected mission up one space. Since the missions listed are played in order from top to bottom, this allows you to change the order in which the missions are played.

Move Down Button

This button moves the selected mission down one space. Since the missions listed are played in order from top to bottom, this allows you to change the order in which the missions are played.

Battle Bitmap

This bitmap is shown on the left side of the galaxy display once the user has selected the battle in the New Battle/Change Battle room of the concourse. The bitmap is encoded using a proprietary TIE Fighter run-length encoding format. The bitmap must be 91x75x256, and must use the standard palette. The clear button will replace the current image with an entirely white background. The save and load buttons allow you to change the bitmap used. It is possible to copy bitmaps from one battle to another by saving the bitmap of one battle and loading it into another.

Galaxy Bitmap

The galaxy bitmap is displayed on the large screen in the center of the New Battle/Change Battle room on the main TIE Fighter concourse. When the currently selected battle is changed, a small rectangle of the galaxy is highlighted and enlarged to show the "battle bitmap." You can move and resize the red rectangle in TFW to change where the rectangle appears in TIE Fighter and how large it will be.






# About
TIE Fighter Workshop
Copyright 1996 Evan Sabatelli
All Rights Reserved.

The TIE Fighter Workshop is a mission, battle, and pilot editor for the LucasArts game TIE Fighter. The TIE Fighter Workshop currently supports almost all features of the original game, the Defender of the Empire add-on, and the CD version. The program allows you to create from scratch anything that you can edit. Features include a graphical waypoint editor, and WYSIWYG briefing editor, complete battle editor, and a pilot editor.

         Creating a new mission   Learn to create a new mission from scratch through those nifty Windows 95 stay-on-top procedural help dialogs. Click Contents, then open the Step-by-Step Procedures heading, click Creating a new mission. The program will guide you through the creation of a simple mission.
         Creating a new battle    Learn to create a new battle as described above.
         Credits and Special Thanks       All the people that helped out.

NOTE: In the event that something does not work, assume that it is because I have been too lazy to implement it just yet. They will be implemented sometime :)

Disclaimer

THIS SOFTWARE AND ALL ACCOMPANYING FILES ARE PROVIDED "AS IS" WITHOUT ANY WARRANTY, EXPRESS OR IMPLIED. THIS INCLUDES, BUT IS NOT LIMITED TO IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.

IN NO EVENT SHALL EVAN SABATELLI BE LIABLE FOR ANY DAMAGES WHATSOEVER ARISING OUT OF THE USE OR INABILITY TO USE THIS PRODUCT.

Legal Stuff

TIE Fighter is a registered trademark by LucasArts Entertainment Company and is Copyright (C) 1994. LucasArts is a trademark of the LucasArts entertainment company. Windows and Windows 95 are trademarks of the Microsoft Corporation. All other trademarks are acknowledged as the property of their respective owners.
#Credits and Special Thanks

Thanks to Alexei Novikov (anoviko@emory.edu) for help with LFD files and the DELT resources! The battle editor could not have been completed without the help!

Thanks to Jason Blackston (jakor@execpc.com) for the info on pilot files, as well as numerous suggestions!

Extra thanks to Keith Howe (rikhowe@sisna.com) for the amazing amount of work on everything and all the suggestions! This program would be without formation pictures, descriptions of orders, and many other features.

Thanks to everyone who e-mailed suggestions and encouragements. This project would not have come this far without you!
#Creating a TIE Fighter Mission

Coming soon! At least you know I'm thinking about it :)

