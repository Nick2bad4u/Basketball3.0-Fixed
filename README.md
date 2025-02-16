# THIS MOD HAS BEEN FIXED BY TYPPI

I TRIED TO REACH OUT TO MURGH MULTIPLE TIMES WITH NO LUCK. IF HE WANTS THIS REMOVED, IT WILL BE REMOVED.

Real-time Basketball 3.0 is here! This is an enhanced version of the good old Basketball mod. It has realistic ball movement (calculated with cubic Bezier curves), a colourful LCD scoreboard, and it's way easier to set it all up than the previous version. Come on and slam and welcome to the jam!

## If this helps you, please support

![Support](https://steamuserimages-a.akamaihd.net/ugc/1826773857050284023/B38E3C7378BC98B0C716BE37AD45EB3BB9ED2A9B/)

## USAGE

1. Research the Psychologist and Education.
2. Place a Basketball Court. The actual court is 1 tile larger (on each side) than the preview shows you: it spawns an indoor room with Concrete Tiles (instead of walls) around the border.
3. Zone a basketball court only within the court lines.
4. Hire the appropriate trainer for the court type and schedule some reform programs.
5. When you put a Basketball court in the centre of your Yard, it's a good idea to set this zone to Access-Only at Deployment, so prisoners don't walk over the court when they cross the yard.

## MOST IMPORTANT

Zone a full court (16x10 tiles) or a half-court (8x10 tiles) only within the court lines! If you make that zone bigger, then prisoners would start to roam outside the court lines during the reform and you don't want that. When placing the court in a larger room, you could mark the surrounding area as Common Room or Yard, so people can go watch a game during FreeTime or Yard time.

## ALTERNATE SETUP

You can also make the basketball court an actual Yard and hire a Basketball Trainer (Yard) instead. Just be sure the Yard is only zoned within the court lines. This results in prisoners playing a game during Yard time without a reform program. When you station Guards in the Yard they will also play.

## BUTTONS

The court comes with various buttons for the Scoreboard and the game itself. Click on the Basketball court or half-court to set the game to your likings:

### SCOREBOARD BUTTONS

- You can change the LCD text, score and clock / countdown colours independently.
- You can also turn off the clock outside reform and toggle the game seconds on/off.

Note: game seconds go way faster than a real second. It will look like the board is showing seconds:milliseconds rather than what you'd expect. A large map and/or using Slow Time mutator will make seconds go a bit slower.

### GAME BUTTONS

- **GAME ON / GAME OFF**: When started, the court will check for players until a minimum amount has been reached to start a game. When stopped, the court goes into deep sleep mode and will use as little cpu as possible. Prisoners are still able to complete the reform programs when the game is off. The only difference will be that no ball will be on the court and prisoners are just roaming around doing their program as usual.
- **BALL**: You can choose whether the ball gets killed or deleted. This happens when a match finishes, or when the ball goes outside the court lines. If you choose to delete the ball, it will simply vaporize in mid-air. If it gets killed, somebody will come to fetch the ball and bring it to a **Basketball Container**. Sometimes there is nothing to fetch, then a big fat blood stain on the floor will be the only thing left... Make sure you have a Basketball Container nearby, or else the dead ball will go to a hearse. By default, 2 containers are spawned next to the Scoreboard, so you should be fine. Prisoners drew a face on it and pretend it's the warden's head, did you know?
- **COURT LIGHTS**: To have the court lights enabled while not having the real-time game running, simply press this button to switch them on or off. Please do not turn on AutoLights nor place lights manually in the room. The basketball court spawns/deletes the court lights when a real-time game starts/ends.
- **LINE TYPE**: You can cycle through 10 different worn fields with this button. Pick whatever you like.
- **FLOOR TYPE**: Last but not least, you can quickly change the floor type, without having to wait for workmen to build a new floor. You can use any floor you want, since the walking speed of floors doesn't matter any more. Cycle through the predefined floors, or manually build one from another mod, it's all fine.

## BASKETBALL RULES

While a real basketball game has many rules, the prisoners won't exactly follow those, since they have difficulties following rules in general. The Basketball Trainer got the prisoners so far to only handle one rule: when a teacher starts the game, the ball needs to be played at least once. From that moment on, whoever moves towards or faces a basket within range will attempt to score. Score outside the arc: 3 points, inside the arc: 2 points, inside the rectangle near the basket: 1 point.

## OBJECTS

- **Basketball Full Court**: Requires 18x12 tiles (horizontally) or 12x18 tiles (vertically)
- **Basketball Half Court**: Requires 10x12 tiles (horizontally) or 12x10 tiles (vertically)
- **Basketball Container**: Required to store dead basketballs if you set the ball to be killed.
- **Scoreboard**: This is OPTIONAL but spawns by default on top of the court. You can sell it if you don't want it at all, or place it somewhere else within 15 tiles of the court. If you are not happy with the placement of the Scoreboard, then simply wipe the Sell Object tool across the Scoreboard to sell all stuff. Place a new Scoreboard where you want it, and it should be picked up by the basketball court after pressing the FIND BOARD button. It will scroll the Court ID (see the tooltip of the basketball court) so you can verify that the Scoreboard has been linked correctly (in case you place several courts close to each other).

## ROOMS

- **Basketball Full Court**: Must be 16x10 tiles (horizontally) or 10x16 tiles (vertically)
- **Basketball Half Court**: Must be 10x8 tiles (horizontally) or 8x10 tiles (vertically)

## STAFF

- **Basketball Trainer (Full Court)**: Does reform on Full Court only
- **Basketball Trainer (Half Court)**: Does reform on Half Court only
- **Basketball Trainer (Yard)**: No reform, only active on courts marked as Yard.

New staff members are roaming around at the court and never get tired. Please check that only 1 trainer is active per court. When you set up several courts, put trainer and schedule the programs all at once, then it can happen that a trainer from court A was selected by the game to do the reform on court B. Not much to do about that, but to sack the idle trainer on court B, or not build everything at once. From the first reform program on, I guess a trainer will be tied to a specific court. But I'm not sure. If you sack an active trainer during reform, the court will spawn a new one (who doesn't have an active 'teaching' tooltip), while the prisoners still do the reform and their counters go up.

## REFORM

You can schedule 1hr, 2hr or 3hr reform programs on each court. The reform programs can be scheduled outside of work and are managed by a Basketball Trainer (full court or half-court). Of course, playing basketball is free of charge.

- The Full Court offers 17 places for prisoners to exercise, but takes quite some space. Needs at least 4 prisoners to start a real-time game.
- The Half-Court program offers 6 places and is good for smaller sectors like PC or SuperMax. Needs at least 2 prisoners to start a real-time game.

This is an updated version of my ancient Basketball mod.

## File List

<p> # Here is a list of files included in this repository:</p>

<ul><h2>LUA</h2>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/scripts/Basketball3.lua" style="color: #86b8b2;">data\scripts\Basketball3.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/scripts/BasketballCourtFull.lua" style="color: #18ea73;">data\scripts\BasketballCourtFull.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/scripts/BasketballCourtHalf.lua" style="color: #c5d228;">data\scripts\BasketballCourtHalf.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/scripts/ScoreBoard3.lua" style="color: #b8e773;">data\scripts\ScoreBoard3.lua</a></li>
<h2></h2>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/.gitignore" style="color: #a23179;">.gitignore</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/.pre-commit-config.yaml" style="color: #fb1d58;">.pre-commit-config.yaml</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/CNAME" style="color: #98dc73;">CNAME</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/generate_file_list.py" style="color: #fb54d8;">generate_file_list.py</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/manifest.txt" style="color: #77509b;">manifest.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/README.md" style="color: #005cf6;">README.md</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/sitemap.xml" style="color: #ff4f2b;">sitemap.xml</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/thumbnail.png" style="color: #1c9cf7;">thumbnail.png</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/_config.yml" style="color: #0bbf56;">_config.yml</a></li>
<h2>data</h2>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/materials.txt" style="color: #a7af8b;">data\materials.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/needs-staff.txt" style="color: #fae5fd;">data\needs-staff.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/needs.txt" style="color: #5ba979;">data\needs.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/production.txt" style="color: #030589;">data\production.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/reform_programs.txt" style="color: #e21075;">data\reform_programs.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/sounds.txt" style="color: #75d3c3;">data\sounds.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/sprites.png" style="color: #8bd503;">data\sprites.png</a></li>
<h2>data\language</h2>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/language/base-language.txt" style="color: #99f92c;">data\language\base-language.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/language/fullgame.txt" style="color: #4d773b;">data\language\fullgame.txt</a></li>
<h2>data\scripts</h2>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/scripts/BasketballCourtFull.lua.bak" style="color: #276910;">data\scripts\BasketballCourtFull.lua.bak</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/data/scripts/BasketballCourtHalf.lua.bak" style="color: #b2927d;">data\scripts\BasketballCourtHalf.lua.bak</a></li>
<h2>.github</h2>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/.github/dependabot.yml" style="color: #ddc3b8;">.github\dependabot.yml</a></li>
<h2>.github\workflows</h2>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/.github/workflows/ActionLint.yml" style="color: #ea20f2;">.github\workflows\ActionLint.yml</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/.github/workflows/dependency-review.yml" style="color: #78172f;">.github\workflows\dependency-review.yml</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/.github/workflows/scorecards.yml" style="color: #73d741;">.github\workflows\scorecards.yml</a></li>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/.github/workflows/sitemap.yml" style="color: #0003a4;">.github\workflows\sitemap.yml</a></li>
<h2>.vscode</h2>
<li><a href="https://github.com/Nick2bad4u/Basketball3.0-Fixed/blob/main/.vscode/settings.json" style="color: #ee3b8d;">.vscode\settings.json</a></li></ul>
