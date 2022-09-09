# Riizu's Guide to Foundry VTT Modules - The v10 Edition

Hey there! Welcome to the wonderful world of FoundryVTT. If you're anything like me, you've probably gotten overwhelmed looking at modules. I'd bet you've opened so many tabs you can't tell up from down, and all the favicons are blurring together.

I get it. Its okay. You can put down the axe. Please, don't roll initiative.

My hope with this repo is to help would-be FoundryVTT DMs parse that absolutely massive backlog of modules, pick out the winners, and eventually, give you all the neat configs that set it up. That said, configuration is a very personal thing, so I beg you: Don't think this is the end-all-be-all of guides. Play with it. Install some, don't install others. Read. the. Docs. This can be a daunting hill to climb, but it can be fun too.

It can also lead to spending 3 days writing a doc like this, mad-dash updating your Foundry instance so your wonderful wife and DM can play on the shiny new V10 edition. They totally ~~told me not to worry about it~~ need it by the end of the week.

I've tried to make this document parseable. I've used a lot of humor. Some of it's probably only funny to me, but I hope it helps break up that massive deluge of modules into fun, bite-sized pieces.

## Don't Like Something?

File an issue! Seriously. I want to make something that reflects the cumulative effort of us server owners. Maybe you would prefer a different module. Lets chat about it! Worse off, we end up with a new branch, or you fork the repo, or something equally awesome. Im an engineer, but I'm no Foundry expert. All I ask is a friendly demeanor and a positive attitude.

## Legend

For now, its pretty simple. We'll see how long that lasts.

- 🚧 : Out-of-date but working
- 🚨 : Broken in v10

# Tier -1: Pre-Game Setup
Before we get started, I want to draw special attention to this section of modules. Unless actively being used, these can be safely disabled - especially during gameplay.

### [DF Curvy Walls🚨](https://github.com/flamewave000/dragonflagon-fvtt/tree/master/df-curvy-walls)

Drawing curves in the Wall Tool is a pain. Truly. This fixes it.

### [Forien's Copy Environment](https://github.com/League-of-Foundry-Developers/foundryvtt-forien-copy-environment)

The foremost mantra one should keep in mind when designing systems is reproducibility. FoundryVTT is no exception. This lets us export and import settings easily, allowing for quick transition between worlds when necessary.

### [Module Compatibility Checker🚧]()

A fantastic tool for early on in a version upgrade, though really just a fancy interface for a spreadsheet. Its been extremely useful for quick sanity checks.

# Tier 0: Batteries Not Included
Foundry VTT out of the box is great, but there are a few areas that are sorely lacking. Tier 0 is intended to be the absolute required modules that, if missing or out of date, would require a replacement, new process, or might otherwise postpone a major version upgrade.

### [Compendium Folders](https://github.com/earlSt1/vtt-compendium-folders)

Yo dawg, I heard you like compendiums. So I put your compendium in a compendium folder. So you can... organize while compendium'ing.

Jokes aside, an easy gotcha here is that Compendium Folders will not export existing folder structures within your world. You'll need to replicate that when making new compendia.

### [DF Manual Rolls🚧](https://github.com/flamewave000/dragonflagon-fvtt/tree/master/df-manual-rolls)

My players like dice. They hoard the clicky clackies like the fiendish goblins they are. As they brood, whispering sweet nothings in the metaphorical ears of their dice hoard, I worry. I worry that I will have to tell them to put them away, because VTT things.

Or, I can tell them to just click the little purple D20 on the left side of their screen and input the roll.

This works fantastic in practice and is by far my favorite DF module.

### [Dice Tray](https://gitlab.com/asacolips-projects/foundry-mods/foundry-vtt-dice-calculator)

Out of the box Foundry does not support any form of click-and-drag dice rolling, instead relying on triggerable actions within sheets or text commands sent via chat. Most of the time, Dice Tray solves this. When I want to ask for a quick off-the-cuff roll, its super easy. It also enables easy dice calculator functionality.

### [Module Management+🚧](https://github.com/mouse0270/module-credits)

A godsend of a module that I discovered while making the transition to v10. Before this, my flow for implementing new modules often meant countless back-forth between the FoundryVTT setup screen and the world. Now I get to quick reference stuff, while also scrubbing out a bunch of other modules.

Replaces:
- [Force Client Controls🚨](https://gitlab.com/kimitsu_desu/force-client-controls)
- [Force Client Settings🚨](https://gitlab.com/kimitsu_desu/force-client-settings)
- [DF Settings Clarity🚧](https://github.com/flamewave000/dragonflagon-fvtt/tree/master/df-settings-clarity)
- [Changelogs & Conflicts](https://github.com/theripper93/libChangelogs)

### [Monk's Player Settings](https://github.com/ironmonk88/monks-player-settings)

For when you need to see exactly why Timmy can't find that one setting you swear exists. Its right there Timmy. Yes, toggle that. No? Okay, i'll do it. It's cool, I've been there too.

## Extra Credit

### [Remote Highlight UI](https://github.com/shemetz/remote-highlight-ui)

Sometimes Timmy is a baller, but just doesn't know where to look. Remote Highlight lets you light up various sections of the UI, automagically.

### [Monk's Common Display](https://github.com/ironmonk88/monks-common-display)

One day the scourge of the Plague will end. I will once again get to play in person. When that day comes, i'll also totally invest in TV that I inset into the table, because my god has FoundryVTT spoiled me when it comes to digital maps. I'll control that awesomeness via this.

### [PopOut!](https://github.com/League-of-Foundry-Developers/fvtt-module-popout)

Exactly what it says on the tin. Pop that window out. Move it. Shake it. Pull it. BOP IT.

# Tier 0.5: Rough Edges
The one Wierd Tier on this list. Tier 0.5 is comprised of core, fundamental improvements that I would feel equally block a version update but aren't necessarily something that makes Foundry unusable when missing. Just... less pleasant. Many of these are technically optional depending on the table in question, so I've omitted the concept of Extra Credit here. Consider this tier piecemeal additions to your setup.

### [Autocomplete Inline Properties](https://github.com/ghost-fvtt/FVTT-Autocomplete-Inline-Properties)

Eventually, you'll find yourself delving into the inner workings of various "items" in Foundry - namely spells, feats, etc. You may need to reference one of the fields on these, and not know what it is. Autocomplete Inline Properties will at least tell you if your guess is wrong, which saves a LOT of time.

### [Autocomplete Whisper](https://github.com/orcnog/autocomplete-whisper/)

I'm lazy. I want to roll dice, giggle like a manic Harengon, and whisper dumb things to my tablemates. This makes sure I can do it in as few keystrokes as possible.

### [Chat Portrait🚧](https://github.com/ShoyuVanilla/FoundryVTT-Chat-Portrait)

Pictures are neat. They immerse us. They remind of us of things. Sometimes they make us facepalm, but at least you'll always be reminded who made you facepalm.

### [DF Chat Enhancements🚧](https://github.com/flamewave000/dragonflagon-fvtt/tree/master/df-chat-enhance)

Chat archival, scroll to bottom, and partial loading. Oh, and big pretty buttons for different roll modes.

### [Drag Ruler🚨](https://github.com/manuelVo/foundryvtt-drag-ruler)

Have you ever had to ask yourself, "Yeah, but what about if I move *this* way?" If so, you'll appreciate Drag Ruler. Quick, easy display of exactly how far you can and can't move. It even supports more advanced features via extension modules.

### [Health Estimate](https://github.com/mclemente/healthEstimate)

Nothing ruins the mood more than a player knowing they were exactly 1 point away from killing an enemy, except not knowing how close they are. Consider this a tool to help negate the need for that question, while also reminding us as DMs what level of carnage we should describe for a given hit.

### [Hidden Initiative🚧](https://github.com/sfuqua/fvtt-hidden-initiative)

Similar ambience addition to Health Estimate. I like to make my players squirm in Round 1, and I love letting them find out they go first.

### [Illandril's Chat Enhancements](https://github.com/illandril/FoundryVTT-chat-enhancements)

Little tweaks for chat. See who's typing as who, who you'll send a message as, etc.

### [Less Fog](https://github.com/trdischat/lessfog)

Fog is great. Not being able to see the map because you keep accidentally clicking on the half-orc barbarian isn't. This makes fog have controllable opacity.

### [Monk's Enhanced Journal](https://github.com/ironmonk88/monks-enhanced-journal)

Because the v10 Journal improvements made you want more. More of what? More.

### [Monk's Little Details](https://github.com/ironmonk88/monks-little-details)

My god yes, I can finally tell what all the status icons are. Oh, and I can save monster noises. Oh and I can...

### [Monk's Scene Navigation](https://github.com/ironmonk88/monks-scene-navigation)

I know how much you like folders, so I put folders in your navigation bar...

### [Monk's Sound Enhancements](https://github.com/ironmonk88/monks-sound-enhancements)

Audio preview of compendium'd playlists.

### [Monk's Wall Enhancement](https://github.com/ironmonk88/monks-wall-enhancement)

Tons of awesome tweaks to the Wall tool to make it easier to use day-to-day.

### [Ownership Viewer](https://github.com/Malekal4699/fvtt-module-permission-viewer)

'Memba how I mentioned I was lazy? Pepperidge Farm remembers. I don't want to right click to change permissions, but I especially don't want to forget to right click and find out 30 mins later that poor Timmy couldn't see the map for that entire time. Sorry Timmy.

### [Quick Insert - Search Widget](https://gitlab.com/fvtt-modules-lab/quick-insert)

"How do I add X to Y?" Press `ctrl+space`. Sometimes click a button. "What is Z?" `ctrl+space`. While a bit of a resource hog, Quick Insert is a dream come true while DM'ing.

### [Quick Status Select](https://github.com/jeremiahverba/qss)

The only thing that could make status selection better after Monk's Little Details - filtering.

### [Smart Target](https://github.com/theripper93/Smart-Target)

The default target reticle is awful. Targeting is frustrating. Smart Target fixes both.

## Systems: 5e

###  [DnD5e Drag Ruler Integration🚨](https://github.com/PepijnMC/ElevationDragRuler)

Hey, now that nifty new Ruler can pay attention to 5e movement! Oh, I... can't make that jump. Damn.

# Tier 1: The Basics
After Tier 0, our Foundry setup is feeling pretty slick. We've got great ways to help solve technical issues, manage settings, and more. Portions of our tool suite are easier to use like Walls, and we've added just a touch of QoL with a few larger additions. Now its time to grab those tools that really help minute-to-minute gameplay.

### [Argon Combat HUD](https://github.com/theripper93/enhancedcombathud) (alt: [Token Action HUD](https://github.com/Drental/fvtt-tokenactionhud))

Opening windows sucks. Action Bars are cool. Players will love Argon, while DMs will love the ease of Token Action HUD.

### [Forien's Unidentified Items🚨](https://github.com/League-of-Foundry-Developers/foundryvtt-forien-unidentified-items)

For when you want to mark that crazy mcguffin as a rock, but not forget its more than rock later. This thing is awesome, but be forewarned - it has trouble syncing to stuff like DDB.

### [Item Piles🚨](https://github.com/fantasycalendar/FoundryVTT-ItemPiles)

So the rogue knows what to steal from everyone before they get there. For real though, this actually lets you do so many cool things with items within a scene.

### [Moulinette](https://github.com/SvenWerlen/moulinette-core)

The $$$ option on the list. I like to use it for Tabletop Audio, but Moulinette really is just the App Store of Foundry content. It works great though, so more than happy to toss a few bucks their way.

### [Polyglot](https://github.com/League-of-Foundry-Developers/fvtt-module-polyglot)

Remembering languages is a royal pain in person - you probably are gonna text that poor elven ranger at the end of the table something, you'll both giggle, and everyone will wonder what just happened.

Now you get to do it while spamming everyone else with wingdings.

### [Quick Encounters](https://github.com/spetzel2020/quick-encounters)

Many a DM knows the tale of triumphantly slamming a giant dragon miniature down on the table. Even more know the pain of pulling out 10 goblins, setting the last one down, and knocking over the first 9. Quick Encounters saves you the pain of managing all of that. Just click a button and, automagically, your encounter is ready! The microwave of encounters.

### [Token Mold](https://github.com/Moerill/token-mold)

Do you remember first discovering the joy of a stamp? The fun of slamming a date, or for those more affluent, cute animals, all over a piece of paper? Now you can do that with goblins - and those goblins will be Randy, have random HP, and possibly darkvision. You won't know until you cover the scene in them.

## Systems: 5e
### [D&D Beyond Importer](https://github.com/mrprimate/ddb-importer)

It imports things. From D&D Beyond. It costs money. Id pay that ten times over for the amount of suffering its saved me. Please WotC, don't ever break this thing. Thanks Mr.Primate!

### [LootsheetNPC5e🚨](https://github.com/jopeek/fvtt-loot-sheet-npc-5e)

Trading, shops, auto-generated gold. Everything that might have once made a DM say, "yeah uh, nothing was on that goblin. Yes, it was the 30th one with nothing, these goblins are suffering from a recession, okay?" Not anymore.

### [Magic Items🚨](https://gitlab.com/riccisi/foundryvtt-magic-items)

An excellent way to shove features and spells onto that random horn that goblin dropped 5 minutes ago, that LootSheetNPC5e gave it randomly due to a lucky 2% roll chance.

### [Tidy5e Sheet](https://github.com/sdenec/tidy5e-sheet)

We all wanted to be that cool kid who showed up to school everyday driving an expensive car. That shit costs money. Covering your character sheet in sweet, automagical buttons and cool slide-out effects however, is priceless.

### [Torch](https://github.com/League-of-Foundry-Developers/torch)

Click on. Click off. The ~~Clapper~~ Torch! Yeah, yeah, thats how it goes!

### [Combat Utility Belt](https://github.com/death-save/combat-utility-belt)

The on ramp for most starting to dip their toe into automation. I mostly use it for Triggler and hiding combatant names.

## Extra Credit

### [Dice So Nice!](https://gitlab.com/riccisi/foundryvtt-dice-so-nice)

You want my ~~kidney~~ actual dice? Sure, yeah. You can now throw 100 3D dice... actually please don't. You'll crash foundry. I forgot to back things up before session. Please. Oh no. What have I done..


# Tier 2: Adding a Heart
Our games run well, but our scenes aren't particularly lively - things sort of just sit there. Tier 2 aims to change that, while also addressing any glaring functionality missing in your system of choice. These modules should eliminate tedium, support advanced features, and create reactive areas within your scenes.

### [Advanced Macros](https://github.com/League-of-Foundry-Developers/fvtt-advanced-macros)

Slam a macro button on that sheet. Bitches love macro buttons.

There's some other neat stuff too, but i'll leave that to the actual useful documentation.

### [Automated Evocations - Companion Manager](https://github.com/theripper93/automated-evocations)

And YOU get a tressym! And you get a tressym!

### [Danger Zone](https://github.com/napolitanod/Danger-Zone)

Rockslides. The floor. Its lava. Yes, that IS a hypothermia zone. I told you not to throw 300 digital dice, Timmy.

### [Item Macro](https://github.com/Kekilla0/Item-Macro)

Yo dawg, I heard you like Macros, so I put M- you get the idea.

*I'm 50 mods in, goin' strong!*

### [Monk's Active Tile Triggers](https://github.com/ironmonk88/monks-active-tiles)

For when Timmy says, "but what if I just walked over there first?" in the middle of your explanation. Or you can do actual cool stuff, like trigger neat effects. The active tile is your oyster, I just stepped on it.

### [Simple Calendar](https://github.com/vigoren/foundryvtt-simple-calendar)

They still will forget what day the game is on, but at least now you'll have record of it.

You'll also be able to have stuff build off time, which is WAY cooler than it sounds.

### [SmallTime](https://github.com/unsoluble/smalltime)

Because you'll forget that, yes, it is still 12:01am and has been for the last 6 sessions. You can control things like lighting via time too!

### [Token Attacher🚨](https://github.com/KayelGee/token-attacher)

I told you not to stick your arm into that ooze, Timmy. Now its your best friend. It will follow you. Forever.

### [Warp Gate](https://github.com/trioderegion/warpgate)

*Let's do the time warp again* - Oh wait, no dumb time jokes here. Quick, I need a warping reference.

Beam them down Timmy - Yes, all of them. OH GOD THE SLIME IS HERE TOO.


## Systems: 5e
*A foreward on Automation: I gotta take off the goofy joke hat for a minute. To be honest, automation for 5e is a giant pain in the neck, depending on your stance regarding how much VTTs should manage for you. Please, read the documentation on all of these. TL;DR: MidiQoL does a LOT, and all of these support that in some way, while also adding a tremendous amount of functionality themselves.*

### [About Time](https://gitlab.com/tposney/about-time)

So now, that cool clock. What if it could auto-advance? [Hell, its about time.](https://www.youtube.com/watch?v=rnSlg-I03oQ)

### [Active-Auras🚨](https://github.com/kandashi/Active-Auras)

Cooties do exist, and its called Auras. Spread it to your friends. They got too close on purpose.

### [DFreds Convenient Effects](https://github.com/DFreds/dfreds-convenient-effects)

What if we took all those neato effects we're about to set up, and attached them to easy, one-click buffs? That'd be convenient.

### [DFreds Effects Panel](https://github.com/DFreds/dfreds-effects-panel)

I need the little boxes too. They make me feel good. Gotta see how many I can click too.

Or as a DM, I can easily remember to click them off, and watch all the associated effects go away too.

### [DnD5e Helpers🚨](https://github.com/trioderegion/dnd5e-helpers)

Ever forget about Wild Magic Surge? These are some helpers for that and more.

### [Dynamic effects using Active Effects](https://gitlab.com/tposney/dae)

Powerhouse module #1. Lots of additional functionality for FoundryVTT's built-in Effects.

### [Midi QOL](https://gitlab.com/tposney/midi-qol)

Powerhouse module #2. If you ever wondered why the official 5e system didn't do something for you, Midi probably can enable it. This and DAE deserve **several** documentation read-throughs.

### [Times Up](https://gitlab.com/tposney/times-up)

Remembering to remove that aura off Timmy, so you don't have to.

## Extra Credit

### [Patrol](https://github.com/theripper93/Patrol)

Again, wouldn't it be awesome if Foundry could remind you that, yes, those goblins DID move in the last 3 hours? Now it can.

# Tier 3: Thinking in Three Dimensions
At this point, our games run smooth, our tooling makes life easy, and we even have a few elements that help bring attention to the benefits of a VTT over traditional pen-and-paper. We can Go Deeper though. And Higher. These all help add depth to your scenes, allowing for true three-dimensional gameplay for those willing to spend the time building it.

### [Better Roofs](https://github.com/theripper93/Better-Roofs)

Massive overhauls to overhead tiles. Your worries are over. Over and out.

### [Elevation Ruler](https://github.com/caewok/fvtt-elevation-ruler)

Now that we are thinking with portals, we need to make sure we know exactly what the distance from point A -> point B is, without relying on a protractor and 8th grade Trigonometry.

### [Enhanced Terrain Layer](https://github.com/ironmonk88/enhanced-terrain-layer)

Lets make that ruler extra smart. Lets make it know just how much that quicksand sucks.

### [Levels](https://github.com/theripper93/Levels)

If you're like me, you had a friend who showed you transparent, grid stands. They put some neato minis on top of it, and you were blown away. You delicately placed each mini on your own stand, were extra careful not to tip it over, and slowly counted each and every cube.

Levels removes all that pain, keeps the awesome, and makes it infinite. With stairs.

### [Wall Height](https://github.com/theripper93/wall-height)

Yes Timmy, your head WAS peeking over that Better Roof. Now its possibly on the floor. Whats your max HP again?

# Tier 5: The Light Show
Oh man, not enough modules eh? Well, if you're hitting this point then you probably have a machine (and hopefully, so do your players), that is far more powerful than the household toaster. Lets flex a bit and add beautiful animations to our scenes and effects.

### [Automated Animations](https://github.com/otigon/automated-jb2a-animations)

Back to the Lazy 2 - Animation edition. Jules and Ben did all that awesome work giving us some free animations, getting us hooked on that beautiful eye candy. This will make sure it works for quite a few things you already have.

TL;DR: Lazers.

### [Active Token Effects🚨](https://github.com/kandashi/Active-Token-Lighting)

Lets make tokens do weird, beautiful things, automagically, via Effects.

### [DF Active Lights🚨](https://github.com/flamewave000/dragonflagon-fvtt/tree/master/df-active-lights)

DISCO RAVE PARTY - But really, a light house that moves.

### [FXMaster](https://github.com/ghost-fvtt/fxmaster)

Actual weather effects across your screen. Its wonderful. Except for Timmy, poor dude is on a toaster. We'll walk him through lowering his graphics settings later.

### [JB2A - Jules and Ben's Animated Assets - Free Content](https://www.patreon.com/JB2A)

Thanks again, Jules and Ben! All the content for our Automated Animations.

### [Sequencer](https://github.com/fantasycalendar/FoundryVTT-Sequencer)

Trigger things, in sequence. What it says on the box, but that box is very deep.

### [Token Magic FX🚨](https://github.com/Feu-Secret/Tokenmagic)

We made our Tokens do neat stuff with Active Token Effects, now we need to make that neat stuff flashy.

# Tier 37: Pieces of Flair
These modules are, simply put, entirely unnecessary. They let players fire off confetti, spam memes, and lots more. Why? It's fun! For those allergic to fun, or otherwise may not want the added overhead, feel free to omit this section entirely.

### [Chat Images🚧](https://github.com/bmarian/chat-images)

Because sometimes, you can't NOT link that dumb meme.

### [Confetti🚧](https://github.com/ElfFriend-DnD/foundryvtt-confetti)

On good days, Confetti is an opportunity for players to shower each other in praise after a great RP moment. The rest of the time, they can, and will, spam the button 30 times because you unintentionally made an innuendo-filled reference.

### [Splatter](https://github.com/theripper93/Splatter)

When that goblin beats Timmy's face in, Timmy deserves to get to see the fruits of his labor in overcoming that trial. Those fruits just happen to be on the floor... the walls... my god, the ceiling too... Timmy, who hurt you?

### [Entice with Dice so Nice](https://github.com/telmo-correa/foundryvtt-entice-with-dice-so-nice)

The first of the ~~Four~~ Three Horseman of the Dicepocalypse.

### [Lordu's Custom Dice for Dice So Nice](https://github.com/LorduFreeman/foundry-lordudice)

The second of the ~~Four~~ Three Horseman of the Dicepocalypse.

### [Nice More Dice](https://github.com/LyncsCwtsh/fvtt-module-Nice-more-Dice)

The third of the ~~Four~~ Three Horseman of the Dicepocalypse.

# For Your Consideration
New modules come out all the time or are otherwise discovered sporadically. Sometimes they provide similar functionality or we discover we don't use them as much as we might have hoped. Maybe they seem important, but you can't determine why. While we research, we keep our notes here.

## Out of Date

### [Mobile Improvements🚨](https://gitlab.com/fvtt-modules-lab/mobile-improvements/-/tree/master)

### [DF Template Enhancements🚨](https://github.com/flamewave000/dragonflagon-fvtt/tree/master/df-templates)

### [TouchVTT🚨](https://github.com/Oromis/touch-vtt)

## In Review

### [Monk's TokenBar](https://github.com/ironmonk88/monks-tokenbar) vs [Let Me Roll That For You 🚨](https://github.com/League-of-Foundry-Developers/fvtt-module-lmrtfy)

## Phased Out

### [PnP - Pointer and Pings](https://github.com/Moerill/fvtt-pointer)


## Management
### [Mana’s Compendium Importer](https://gitlab.com/mkahvi/fvtt-compendium-importer)
### [Potato or Not](https://github.com/fantasycalendar/FoundryVTT-PotatoOrNot)
### [Commander](https://github.com/ccjmk/commander)


## Integrations
### [Beyond20](https://beyond20.here-for-more.info)
### [DDB Game Log](https://github.com/IamWarHead/ddb-game-log)
https://github.com/moo-man/FVTT-DD-Import

## Tools
### [Lock View](https://github.com/CDeenen/LockView)
### [Mass Edit](https://github.com/Aedif/multi-token-edit)
### [Background Volume](https://github.com/mtvjr/background-volume)
### [Keyboard Layout](https://github.com/ghost-fvtt/keyboard-layout)
### [Pin Cushion](https://github.com/p4535992/foundryvtt-pin-cushion/)
### [SimpleFog](https://github.com/League-of-Foundry-Developers/simplefog)
Drag Upload (Get Over Here)
https://github.com/dev7355608/advanced-drawing-tools
Arius Planeswalkers Stylish Journal for Monks
https://gitlab.com/n3dst4/louder-whispers

## Features
### [Burger Time](https://github.com/scottburton11/burger-time)
### [Shared Vision](https://github.com/CDeenen/SharedVision)
### [Weather Control](https://gitlab.com/jstebenne/foundryvtt-weather-control)
### [Proximity Text Chat](https://github.com/jessev14/proximity-text-chat)
DFreds Pocket Change
Spellbook Master v1.0.4
https://gitlab.com/tposney/itemcollection

## UI
### [Obsidian Character Sheet](https://bitbucket.org/Fyorl/obsidian/src/master/)
### [Macro Folders](https://github.com/earlSt1/vtt-macro-folders)
### [Sticky Sidebar](https://github.com/mouse0270/sticky-sidebar)
### [Damage Log](https://github.com/cs96and/FoundryVTT-damage-log)
### [Alpha HUD](https://github.com/averrin/alpha-hud)
https://github.com/jopeek/fvtt-token-info-icons

## Combat
### [MARS 5e](https://github.com/Moerill/fvtt-mars-5e)
### [Better Rolls](https://github.com/RedReign/FoundryVTT-BetterRolls5e)

## Content

### [Sane Magical Item Prices Compendium](https://gitlab.com/fohswe/smip-compendium)
### [Foundry VTT Tables](https://github.com/foundry-vtt-community/tables)
### [Foundry VTT Macros](https://github.com/foundry-vtt-community/macros)

## Fluff
https://github.com/Aedif/TokenVariants

–Token Animation Tools v1.2.1.0

https://github.com/Vauryx/AdvancedSpellEffects

https://github.com/jackkerouac/animated-spell-effects

https://github.com/Eriku33/Foundry-VTT-Image-Hover

## Cutting Room Floor
Modules that, at this time, may be unnecessary, superfluous, or otherwise outdated. Perhaps they aren't maintained actively anymore. Some of these may work better for your purposes though, or might otherwise need to be remembered. So they go in the closet, stashed behind all the other things.

### [Compendium Browser](https://github.com/League-of-Foundry-Developers/compendium-browser)

### [DFreds Droppables](https://github.com/DFreds/dfreds-droppables)

### [DF Quality of Life](https://github.com/flamewave000/dragonflagon-fvtt/tree/master/df-qol)

### [Ensemble - drag and drop your sound files](https://github.com/janckoch/Ensemble)

### [Parallaxia](https://gitlab.com/reichler/parallaxia)

### [Break Time](https://github.com/ironmonk88/breaktime)
  - known bug: Breaks smalltime docking to player list

### [Grid Scaler🚨](https://github.com/jbhaywood/scaleGrid/)

### [GM Screen🚨](https://github.com/ElfFriend-DnD/foundryvtt-gmScreen)

### [DF Architect🚨](https://github.com/flamewave000/dragonflagon-arch)
