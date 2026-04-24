## Feature Request








- add a button in move breakdown to show the nature and spread of the meta list (similar to “?” button)





- Water bubble not workin
- body slam damage


- Status ticker per Pokemon (burn/para/…) and have that status be displayed on the listing below the name like the games



- move/ability search will filter with all possible not just run in meta

- add a small button on each match history listing below the LOSS/WIN text to load match which will open a new match screen with the current team vs the opponent's pokemon will also replace the current pinned pokemon with the opponent pokemon from the match


## To-Do Stack


### Bug Stack


---
#### Completed

- [XX] support for ranged multi-hitting moves
- [XX] in damage calculations for the results window, don't have the max stats and max hp buttons apply to the pokemon in the tab, only have it apply to the one in the listing
- [XX] ability usage hover with other potential abilities (extra parsing and data needed)
- [XX] support for fixed multi hit moves (dual wingbeat, dragon darts)
- [XX] item usage hover with other potential items (extra parsing and data needed)
- [XX] click the values in the stat buff spinners to reset them to 0
- [XX] load enemy team paste into pins
- [XX] when you delete an entry in the match history, have it update the overall winrate accordingly
- [XX] in the meta analysis and current match analysis, have it not count damage to pokemon going over 130%. Also have immunities have a little extra weight in calculating defense.
- [XX] change the fitting of the pokemon tabs to either be all 6 pokemon in a line or 2x3, never a 4 on top, 2 on bottom situation
- [XX] pokemon will collapse on unpin
- [XX] change drop downs for stat changes to vertically aligned plus and minus buttons that tick up and down by 1
- [XX] add a meta profile that will give you the top 4 offensive and top 4 defensive threats in a given meta against your current tabbed pokemon (go into more detail about damage and resistance) it should also pin those 6 pokemon.
- [XX] on mega button unclick and click make sure the abilities are updated properly (venusaur clicks into mega button, gets thick fat, golurk unclicks, gets another legal ability like iron fist)
- [XX] Item usage visibility
- [XX] ability listed in breakdown with hover text
- [XX] make the speed value text (not the spe) in the current match window to be white
- [XX] have the max rolls button's text change to Min rolls on deselect
- [XX] make the type weakness table minizable as well
- [XX] in the match history screen, have the pokemon searched only apply to the opponent team
- [XX] the buttons don't seem to be updating the damages in the listing, maybe the stats aren't updated. also, I'd like the name in the listing to change (Aggron-Mega > Aggron, Charizard-Mega-Y > Charizard-Mega-X > Charizard)
- [XX] MEGAS WORK well kind of, regular venusaur has a mega button that can be clicked on which turns it into mega venusaur with correct stats and everything. it's just the already mega ones in the meta that have a problem
- [XX] no mega button on floette-mega
- [XX] unclicking both charizard mega buttons should revert to base charizard
- [XX] make it so the paste windows don't collaps if you click anywhere in the window, only the top of the window
- [XX] sort saved team drop down by last updated (created or winrate adjusted)
- [XX] add bunch more room to buffer at bottom of results tab so an empty screen takes up more space
- [XX] older released mega pokemon have mega buttons, but new ones like golurk and floette don't have buttons
- [XX] the problem with charizard x isn't that it's necessarily duplicating, it's just keeping the pin value for charizard y when you switch to x and pin x. you just have to clear the pinned y when you add an x and vice versa.
- [XX] move tabs section to right above the actual results screen, so below the winrate and the match screen that will appear 
- [XX] charizard y is now adding a second copy of charizard x in the match screen enemy team
- [XX] change attacking button to a toggling button that switches between “attacking”/“defending” text
- [XX] change the min button to a toggling button that switched between “min roll” / “max roll”
- [XX] Give the max investment button a matching style but have its text not switch, it’ll just light up and not light up
- [XX] search any Pokémon and add as temp pin with empty load out for replay image
- [XX] have sprite calls in match history for mega’s that couldnt be found default to their regular form sprites instead
- [XX] max bulk and speed on the button, separate HP button
- [XX] the autocomplete text needs to be updated to match the new starting point of the text with the added pin button
- [XX] non-meta pokemon need to also have sprites in the match screen. also the sprite it's pulling in the match results listings is not the pokeapi pull.
- [XX] little status bar connected to bottom of control bar that shows all active battlefield effects with colors (when cleared will be empty)
- [XX] move clear effects button to left end of that status bar
- [XX] collapsible paste windows that do a little growing and shrinking animation on hover
- [XX] shrinking animation on “load meta” or “load paste”
- [XX] have it auto tick max for defending and untick max for attacking
- [XX] Pin top result button on top of search bar
- [XX] adjust hitbox of ? To only cover the Text and button
- [XX] Get rid of color legend and change thresholds to turn ko thresholds
- [XX] clickable sprites to grey out moms not brought in match listing
- [XX] in window winrate of matches updates to only searched matches
- [XX] allow searching of non meta Pokemon to add as a temporary pin
- [XX] Stance change switch for aegislash (also changes name on listing)
- [XX] non-meta pins don't stick to the top of the results like regular pins do
- [XX] in results, with Pokemon with mega forms, allow you to toggle between forms (just a button with the mega icon symbol that’s highlighted already if it’s already mega, and multiple buttons for multiple mega forms labeled x or y respectively (charizard)) Also changes names on listing
- [XX] Add a calc button in match bar that calculates your and their kings (if pins present, use only pins; else use entire meta but only show top 6)
- [XX] Sort by total damage first, then speed second
- [XX] Offensive and defensive
- [XX] Hover text on start match button will say starts match against pinned opponents
- [XX] Each icon is clickable to give a hover grid like the type weakness
- [XX] Clicking them will light them up showing who was brought, and this will carry over to the replay who was brought
- [XX] List speed values on the king icons
- [XX] put the match results to the right of the start match button
- [XX] change background of hover to be something ligher as to not mistake with immunity
- [XX] the win in the WL record is now white, not green for some reason
- [XX] have the sprites in the match history listings be clickable to ungray them or gray them out and have that also update the saved value when you do.
- [XX] save pins as team matchup in match history with w/l
- [XX] make the control bar text not selectable either (outside of the search bar of course)
- [XX] when switching between loaded teams, the weakness chart doesn't get reordered accordingly
- [XX] have the plus button on the left side, then the collapsable arrow icon, then the pin button so the pin and plus are separated more
- [XX] give the plus button some kind of hover glow or brightening
- [XX] make the pin button a little bit bigger
- [XX] the search term help window is showing up just on click, i want it only when you click the "?", and it's also seeming kind of sticky. i want it to go away when another area in the window is clicked 
- [XX] show the weakness chart with only one pokemon
- [XX] show the stat value next to the name in parentheses for each sort type and maybe grayed out and a bit smaller (sort by attack shows attack, speed shows speed, etc...)
- [XX] Hovering a move will give you it's effect description
- [XX] button in move breakdown to toggle a 1.2x item boost like for black glasses, but for the respective type
- [XX] make the extra move sections more compact or smaller font or something
- [XX] have moves below the line in the breakdown be automatically collapsed but expandable if you click on the line
- [XX] in the move breakdown, add a button to toggle scarf boost if it didn't already have one, or toggle it off if it did have one
- [XX] add more than 4 moves to defenders
- [XX] weather ball not doing enough damage still, could be because it's not getting 1.5x multiplier for rain/sun boost?
- [XX] still doing way too much and adding bonus to pokemon that were already max investment
- [XX] speed message showing faster from wrong perspective
- [XX] aurora veil multiplier should not be .5, but (2732/4096)
- [XX] technician, protean, foul play, body press, psyshock, and liquid voice seem to be working right
- [XX] mega launcher not supposed to apply to water spout
- [XX] mega launcher boosting moves too much in general
- [XX] sylveon with fairy feather pixilate is not doing enough
- [XX] freeze dry not doing enough (could need to be doubled?)
- [XX] switch to attacking mode to see damage numbers (keeping same order as defending)
- [XX] import full team and see type/pokemon weaknesses
- [XX] show speed comparison in move breakdown (scarf compatibility?)
- [XX] have 6 tabs below control bar that can be cli
- [XX] pin button in results to put to top
- [XX] ability and item damage
- [XX] keep original move order
- [?X] switch to attacking mode to see damage numbers (keeping same order as defending)
- [XX] search bar in the results-controls