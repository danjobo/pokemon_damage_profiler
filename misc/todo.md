## Feature Request


- [??] bulletproof immunities support in calculations everywhere else (weakness overlap window, meta analysis, current match window calculations...)





- [??] collapse headers in text edit window in notes?





- shortcuts on hover

- shortcuts tooltips?

- shortcuts overview button






- basculegion-f grid sprite






- use grid sprites for the match log





- metagame folders for different saved metas and teams






- move/ability search will filter with all possible not just run in meta


- Status ticker per Pokemon (burn/para/…) and have that status be displayed on the listing below the name like the games


%SystemRoot%\System32\SHELL32.dll
## To-Do Stack

- clear pins was never found
- [??] auto switching to match history after clicking win was kind of confusing
- [??] having to clear pins after was kind of confusing
- having to press calculate before saving a team was kind of confusing
- 

### Bug Stack


---
#### Completed

- [XX] bulletproof ability is showing as immune to ice hammer for some reason. should I give you the official list of affected moves?
- [XX] copying to clipboard should only include first ability of each mon
- [XX] mega sol weatherballs should always be fire type like sun is active
- [XX] formatting in notes is sometimes disappearing when closing the editor, I suspect it might be due to the hiding it when not clicked on it. By disappearing I mean, I'll edit something in a note, close it, and in the preview the formatting of text elsewhere like a bolding or a header will just disappear
- [XX] ctrl+x with nothing selected in notes editor should delete the current line
- [XX] tab in the notes editor should insert a tab, and tabs should be supported in the markdown and not get eaten up
- [XX] team changes save automatically + duplicate team button
- [XX] remove the plus and minus buttons next to HP EV slider in team window and move breakdown spread editor
- [XX] tab form changes reflect in match window calcs
- [XX] make the yellow glow in match log listings to be less opacity
- [XX] new team button next to teams dropdown that makes a new blank team with the name "Untitled X" where X starts at 1 and increases up to the next lowest available X (just like with file name duplicates)
- [XX] ctrl+b on unselected text is still not putting the carat right after the two **s
- [XX] reset field effects button should reset both attacker and defender field effects (stat spinner changes and screens). same for when the field effects reset on match completion
- [XX] copy team to clipboard should not include more than the first 4 moves of each tab
- [XX] changing forms of tab that is selected in match window game dehighlights it's yellow highlight. it only goes back when you change its form back. i want it to be yellow regardless the form
- [XX] when I control+b in notes at the end of a word, it auto moves my cursor to the beginning of the note, I just want it to move to the end of the current word after the **'s or *'s
- [XX] underline support
- [XX] sprite support [[ITEM_NAME]] [[POKEMON_NAME]], maybe shortcut. what are some usable shortcut keys in chrome?
- [XX] weather + terrain dropdown text option of "None"'s colors are being changed to last option selected when they should always be white
- [XX] ctrl+c with nothing clicked on the page will copy the current tabs to clipboard
- [XX] little message popup to show that cliboard was copied
- [XX] show exact OHKO percent in printing calcs
- [XX] sometimes like in groudon's case, it's saying OHKO ([object Object]) on the incoming damage percents
- [XX] ctrl+b not bolding whole current unselected word, should also count if you're at the end of a word
- [XX] change ctrl+enter to do new line
- [XX] remove ctrl+enter saving note in notes tab, hitting escape in notes editor saves current note
- [XX] hidden markdown should not have the **'s or ##'s be invisible but present, they should not be present until clicking the bolded text
- [XX] also should unbold current or un italicize
- [XX] electric terrain quark drive and sun protosynthesis buff (on mons without booster energy) works on results listings, but doesn't work when it's your tab that has quark drive or protosynthesis (test case was seeing damage increasing in defending mode, but not your damage increasing in attacking mode)
- [XX] sun should activate protosynthesis on non booster energy pokemon
- [XX] electric terrain should activate quark drive on non booster energy pokemon
- [XX] there's still a gap above sort dropdowns section
- [XX] the gaussian circle glow behind pokemon in match log should be yellow
- [XX] screens/stat boosts should be saved per defending/attacking mode, so there will be separate screens/stat boosts for each mode
- [XX] color the terrain text in the dropdown to match that in the field effects bar
- [XX] color the weather text in the dropdown to match that in the field effects bar
- [XX] ruinous abilities damage
- [XX] print "Calcs document!"
- [XX] meta analysis speed affected by tailwind/trickroom
- [XX] meta analysis affected by tera types in tabs
- [XX] lil triangle on type weakness overlap window to show it's collapsable like the other ones
- [XX] meta analysis "good against" mode
- [XX] temp ev/nature slider in move breakdown
- [XX] palafin zero to hero form switcher
- [XX] pinning the tab of a pokemon with choice scarf seems to have the pinned version get a double buff of choice scarf for some reason
- [XX] show blank ev screen in defender window at the beginning before team load
- [XX] nature + and -s not showing as deselected when there's it's opposite already selected. one thing to note is that even though it's showing as not deselected, their logic seems to be acting as if they are so I like the logic just the appearance
- [XX] right click match window pokemon switches from attacking to defending graphic?
- [XX] WATER DOESNT RESIST GROUND DUMMY
- [XX] with the resist keyword filter, also include immunities
- [XX] with the hits: keyword, when doing multiple of them, have the results be filtered with and logic not or logic
- [XX] singles / doubles damage switcher to remove spread debuffs
- [XX] flesh out EV window in team paste with move text boxes that have suggestive autocomplete same as the search bar but with legal moves for that pokemon
- [XX] scarf double up bug is soooo annoying
- [XX] the add button doesn't work on listings that were previously tabs that became pinned
- [XX] if I have a pinned terapagos-terastal, then I terastalize it, it becomes terapagos-stellar which removes it from the pinned pokemon, and also the current match window doesn't reflect it's form change (important to note, it was a starred pokemon, so I think it should also have a star on the end of the stellar form when it changes) also it loses its yellow highlight
- [XX] change "clear defenders" to "clear tabs"
- [XX] refreshing tab item sprites and listing sprites all the time, a little too much
- [XX] current match defensive sorting is reversed?
- [XX] assault vest 1.5x spdef boost?
- [XX] there is no Thunder Clap, only Thunderclap
- [XX] starred pins are being kept in results if they're loaded from a match log
- [XX] renaming saved team clears their replays
- [XX] grid icons on results listings below the paste #
- [XX] split and connect the max HP/max stats buttons into one like a pill
- [XX] wicked blow and surging strikes are always critical hits too
- [XX] min rolls button should be brighter, like white outline and text
- [XX] light screen/reflect/aurora veil should be three buttons pilled together that can all be turned on
- [XX] better way to handle failed icon sprite calls in tab window?
- [XX] defending/attacking buttons should be blue and red
- [XX] shadow shield support (multiscale) also change text of tera shell
- [XX] signature moves in json imports not being imported right "Surgingstrikes", "Wickedblow", "Glaciallance", "Astralbarrage"
- [XX] some abilities still too "Psychicsurge", "Grassysurge", "Friendguard", "Vessel of Ruin"
- [XX] import meta json button
- [XX] ivy cudgel fix, not just tera, but it's based on form
- [XX] Tera Shell support
- [XX] if there's a link in a match log notes tab, add it as a button on the match listing below the load button as replay that will open the link in a new tab
- [XX] move clear defenders to right side, clear pins to right side, pin tabs to right side of tabs, and max rolls to left side
- [XX] show total match history somehow (per format)
- [XX] terapagos-terastal tera starstorm is single target
- [XX] tera type support in scarlet & violet
- [XX] electric terrain boosts electric by 30%
    - [XX] doubles rising voltage's base power
- [XX] psychic terrain boosts psychic by 30%
- [XX] misty terrain halves dragon type moves
- [XX] grassy terrain boosts grass by 30%
    - [XX] bulldoze, earthquake, magnitude halved
- [XX] band/specs boost button
    - [XX] button there, no worky
- [XX] life orb button
    - [XX] button there, no worky
- [XX] booster energy support?
    - [XX] button there, but no visible function?
- [XX] item icon on bottom right of tab sprite
- [XX] abilities getting chopped together in paste from json "Sandforce" instead of "Sand Force"
- [XX] items as well "Charizarditey" vs "Charizardite Y"
- [XX] sand force should buff damage in sandstorm
- [XX] icicle spear not being recognized??
- [XX] toggle show md preview in text edit window in notes?
- [XX] have highlighed enemy pokemon in match window also highlight the pinned results listings they correspond to yellow kinda like how the tabs highlight yellow
- [XX] KNOCK OFF DAMAGE ISN'T INCREASING IF THEY HAVE AN ITEM!!!
- [XX] notes link recognition and compatibility
- [XX] notes text editor ctrl+b and ctrl+i bolds and italicizes current section or current word playhead is on.
- [XX] ev checkmarck green tag on saved teams with full evs
- [XX] sacred sword not being powered up by sharpness
- [XX] Have default text window size be like 3x as long if there's already a bunch of text inside it
- [XX] no mega buttons in scarlet & violet
- [XX] orgepon-cornerstone sprite is tatsugiri?
- [XX] match screen floette-mega default to floette-eternal sprite
- [XX] match screen/match log sprites now not loading the mega-scovillain defaults to scovillain and mega-hawlucha defaults to hawlucha anymore
- [XX] with match window open, highlight/unhighlight your tabs in yellow that are selected in the match window.
- [XX] late drive save gives popup error
Drive save failed: {
    "error: {
        "code: 401,
        "message": "Requiest had invalid authentication credentials.
        Expected OAuth 2 access token, login cookie or other valid
        authentication credential. See https://developers.google.com/
        identity/sign-in/web/devconsole-project.",
        "errors":[
            {
                "message": "Invalid Credentials",
                "domain": "global",
                "reason": "authError",
                "location": "Authorization",
                "locationType": "header"
            }
        ],
        "status": "UNAUTHENTICATED"
    }
}
- [XX] use the same code for the pokemon sprites in the saved teams dropdown to display those grid sprites onto the tabs themselves
- [XX] with that, make all buttons in the tab windows text show just the first letter of it "Mega > M, Shield > S, Blade > B..."
- [XX] paldean tauros raging bull type change support
- [XX] paldean tauros team dropdown sprite not showing
- [XX] change "calculate damage" to "add to tab(s)"
- [XX] non-mega golurk default sprite not working in match screen, type synergies, match log, but maybe working in meta analysis? i got glimmora-mega to work
- [XX] ctrl+enter in search bar starts match
- [XX] shift+enter adds the top to a tab
- [XX] enter in search bar will pin top, but if you press it again, it will unpin the one you just pinned, essentially toggling between pinned and unpin everytime you press it
- [XX] fix pin functionality
- [XX] make pins of tabs also work
- [XX] have type synergies have a cap of 1 mega only
- [XX] in the type synergies weighing, just like we have immunities worth more, have 1/4 resistances be more than 1/2 but not as much as immunities. Also have covering for 4x weaknesses be worth more than 2x weaknesses.
- [XX] have the results listing meta load on meta load, just have the listings show no damage.
- [XX] in type synergies window, the "X threats" text in yellow is now back to turning into an expandable triangle
- [XX] feraligatr-mega sprite still not loading right away in the type synergies window
- [XX] have buttons in the synergies window to switch from pairs of two to three to four
- [XX] for the type synergies window, add a mode where you can see synergies combinations with the pinned pokemon and the rest of the mons in the meta
- [XX] in search bar, pressing enter just a pokemons name will tab the top result
- [XX] in search bar, pressing ctrl+x with nothign selected will clear the bar
- [XX] the keyword filter "hits:___" should not take into account extra moves, only main ones
- [XX] the keyword filter "hits:___" is not working when I type in "hits:tyranitar-mega" when there are pokemon that can hit him super-effectively.
- [XX] using multiple "hits:__" keyword filters seems to not be doing anything, when I would like it to select pokemon that can hit either type all of them
- [XX] in the meta analysis tab, the offensive threats sorting method should heavily weigh towards hitting pokemon that they can outspeed. so if they hit 3 of your team for supereffective, but they're slower than all of them, that should be a major decrease in it's weight. but if it can outpseed all of the 3 it hits or 1 or 2, it should weigh that accordingly. with that being said, the speeds should be affected by the current field effects. so if I have no speed effects, it doesn't outspeed the mons it hits supereffectively, it should be weighed low, but if I have tailwind for the attackers or trick room up and it does outspeed, then it should auto update to take that into account.
- [XX] the scarf button is not recognizing my basculegion being scarfed and updating it's speed in the result listing properly
-  [XX] maybe remove the auto saving popup window with that I have to click ok on that pops up every time
- [XX] fairy aura on tabbed pokemon attacking damage not showing in move breakdown text, not sure if it's applying to daamage
- [XX] have abilities that boost speed in weather affects affect results listings speeds (setting sand with a sand rush excadrill will double it's speed. there's also chlorophyll, slush rush, swift swim)
- [XX] I like the brighter gaussian blurred circle, but I don't like the border outline that was added to it
- [XX] since weather ball shows as a normal type move even when weather is up, ghost types show immunity to it, so it's not showing up in the move breakdowns
- [XX] in the match log, the gaussian blurred circle behind the first two selected pokemon on each team is not noticeable enough. maybe make it brighter
- [XX] Add a multiscale toggle to pokemon that have it in the tabs
- [XX] for weather ball, it looks like type boosting items like mystic water are not being applied to weather ball when it changes it's type in weather. for example, if i have a mystic water pelipper with weather ball, if I set it to rain, it doesn't add the mystic water damage to it and it doesn't show the mystic water text in the move breakdown.
- [XX] aegislash is not able to be hit by psychic moves even though he's only steel ghost and not dark type
- [XX] results listings with black glasses/damage boosting items are applying their damage correctly, but if i press the +-item x1.2 button, it will increase it by an additional 1.2 instead of recognizing it has black glasses already and decreasing it
- [XX] have levitate ground immunity affect pip graphics in current match window hover windows, in the type weakness overlap window, and the meta analysis hover windows. and if it's not already, also have it affect the damage calculation for each of those.
- [XX] you can get rid of the text below the team paste dropdown. (the one that says the name in bold | types: _ | level 50 ...)
- [XX] unclicking the mega button on a mega results listing shows the wrong ability on first unclick (unclick dragonite-mega it shows innerfocus until i click and unclick again it shows multiscale)
- [XX] make a show more text
- [XX] less indentation on unordered/ordered lists now
- [XX] pokemon with change to KO, put odds to KO in smaller text below the percent text in the results listing
- [XX] add a button in move breakdown to show the nature and spread of the meta list (similar to “?” button)
- [XX] star entries to pin them to top
- [XX] Add a button in meta analysis to switch from team view to tab view, where team analyses whole team together while tab only view selected tab
- [XX] add a notebook tab next to the right of match log button that switches the results screen area with a notebook section. this will have listing of note entries you've made with date and time on the left and when you click them, they will expand to show the full entry (maybe have a "show more"/"show less" text on it somewhere). When they're minimized, they should just show the text of the first line (thus newline characters should be supported). if you click them, a text box will open where you can type and change the text of the note. they should also read markdown formatting style and display it in the expanded entry (but not in the text editing window). at the top of the notes entry list, there will always be a plus button that lets you create a new note entry. this buttton should have the same size as a note entry (width and height), but should just have a plus in the middle of it, and new entries will appear below it. each note entry will have an x button on it's right to delete it. these notes will be saved per team in each team's save file.
- [XX] within each listing, collapsable headers (each header text will collapse following text of lower heading rank)
- [XX] let the plus and minus buttons be clickable when there's none clicked.
- [XX] make the actual stat value text in the slider window be white
- [XX] triple axel damage is not uniform per hit, it goes base power 20 for first, 40 for second, 60 for third
- [XX] in the slider window, make the whole X / 66 text turn green only when it says "66 / 66"
- [XX] add a turtle or lightning icon on the results listings to show if you're outsped or not matching the move breakdown's outsped line
- [XX] EV investment sliders + nature dropdown swicher in team paste window that live update the tab's text and the damage calcs as they change
- [XX] item boost are working in the results display damage calcs, but I'm only seeing it in blue text in defending mode, not attacking mode when some of the tabs are using damage boosting items (it is applying the item boost damage, just not showing the blue text)
- [XX] have clicking trickroom in drop down affect the speed and threat calculation in the meta analysis window
- [XX] on match completion (clicking the win/loss button), can you have it keep the window in the results window, not auto switch to the match log?
- [XX] for the buttons attached to the search bar, just switch the positions of the x button and the pin to top button
- [XX] on match completion, clear the current pinned mons
- [XX] add a speed timeline with same implementation from meta analysis into current match screen in the hover windows for each pokemon, except it will compare each hovered pokemon the other team it's facing
- [XX] move the pin tabs button to on top of the clear pins button
- [XX] have the tab bar section stick to the bottom of the control bar when it scrolls down
- [XX] have reporting a match in the match screen as win or loss reset the field effects
- [XX] remove the tailwind (both) option from the speed condition dropdown
- [XX] move pin tabs button to in the section with the meta analysis button and copy to clipboard. maybe have the meta analysis button stuck to the left of the match log button and the copy to clipboard on the right with pin tabs button on it's right.
- [XX] load current team into pins with exact stats and moves
- [XX] have the meta analysis damage calculation be affected by field conditions in the control bar (rain set up will make water do more damage and turn weather ball into water type and fire moves do half damage, etc...) we already have that logic for the results listings so maybe try and use that somehow
- [XX] add mega toggle buttons on the tabs which will affect the stats of them in damage calculation
- [XX] in the match log listings, have a little notebook button below the date and time that when you click it, it will open a little text box that you can type into and will save that text in the listing data. then when you hover the notebook button, it'll show that text in the hover window.
- [XX] it's highlighting the user's first 2 pokemon, but not the enemy's. I want it to highlight the first 2 of the user's team, and the first 2 of the enemy's team. also i'm not seeing any glowing of them in the match log
- [XX] have first 2 pokemon clicked in current match be differnt color highlight then second 2, and if they're unclicked it will pass down to the next one clicked (so just have a queue). have the same feature for clicking sprites in match history, except the first 2 will just have like a soft gaussian glowing orb behind them while the other 2 won't. same appearance otherwise
- [XX] when sorting by HP, have it use the same system appearance as the the other sorting by stats where it shows the value of the stat next to the name. try to use the same appearance if you can.
- [XX] swap clear pins with copy to clipboard position
- [XX] more color damage thresholds
- [XX] get rid of A-Z sort, add HP sort
- [XX] load match in match history also pins opponents pokemon
- [XX] Water bubble not workin
- [XX] heavy slam damage
- [XX] change the percent text next to the bar in match listing headings that are over 130% to instead say 130%+ OHKO
- [XX] Move the attacking/defending button to the tab section at the left end
- [XX] add a small button on each match history listing below the LOSS/WIN text to load match which will open a new match screen with the current team vs the opponent's pokemon will also replace the current pinned pokemon with the opponent pokemon from the match
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