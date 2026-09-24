# Balancing + QoL
Version: 1.2.0
Date: 20 Jul 2026
Image: 123384908315879

### Content
- No more slacking off at work
  - AFK players are now sent somewhere else...
- Added refueling quests for Transporters and Factory Directors
- Added a free rewards giftbox within the vehicle shop
  - Like 👍 the game and join the group for free rewards!
- Added ore weights on capacity
  - Rarer ores will now weight more on your capacity as a Hauler
  - Ore weights are now displayed under the prompt for Haulers / Factory Director
  - Be mindful of your choices! Sometimes, more cargo is better...
- Lamps now light on and off, providing better visibility at night
- Added new secret leaderboard next to the statue
- Added quick upgrade mechanic
  - Allows you to upgrade your vehicle while you're driving

### Bug Fixes
- Shipment fixes
  - To be earn a paycheck you now need to do tasks more than once
  - Your level now influences how much cash you receive within your paycheck
  - Veteran players earn more than newbies
- Refinery fixes
  - Increased arms speed
  - Packager processes bars better, no longer fills up
  - Ores stuck in front of the conveyor now get teleported into the pool
  - Performance fixes related to many ores sitting within the pool
- Hauler Chain Pickup fixes
  - Each time you grab an ore, your pick up duration becomes faster while Chain Pickup is active
  - Chain Pickup lasts for 4 seconds or until a certain amount of picked up ores is reached
- Vehicle shop fixes
  - On open, selected vehicle is either the one you last drove, the best you own or the first of your team (in order)
  - Miner vehicles now have the Durability stat visible
  - Vehicle upgrade level now shows on its card
  - Orange bar now indicates which stat the next upgrade changes
  - Upgrade button re-colored to orange to match the stat bar preview
  - Mine Area stat now shows the correct value
- Fixed issue with getting stuck in MegaHauler when leaving the vehicle
- Fixed time-based "Play as..." quests not working when quests refresh
- Fixed issues with fetching quests
- Fixed packages bringing Transporter vehicles down
- Fixed prompts showing as blank sometimes
- Fixed cash balance and upgrade cost being rounded in the vehicle shop UI
- Fixed upgrade failure telling you the price instead of the difference needed
- Fixed "Most Played" leaderboard icon
- Fixed being able to equip items in Vehicle Shop
- Fixed being able to pick up fuel packages when they're at the drop-off zone
- Fixed Factory Director being able to see prompts they shouldn't see
- Fixed tutorials after the first one not completing

### Other
- Slowed down Mega Hauler a little bit

# Deeper Operations
Version: 1.1.0
Date: 11 Jul 2026
Image: 123384908315879

### Content
- Look for a hidden code around the map!
- Mine rework
  - More layers present, with different durability stages, requiring you to upgrade your vehicle
  - Mine terrain has received a little shake, should feel more like a mine now
  - 2 new Legendary ores
  - 1 new Mythical ore
  - Legendary & Mythical ores now are more visible thanks to custom VFX
  - Entrance lights up at night!
- Vehicle  & Economy balancing
  - New vehicle upgrading system
  - 2 new Hauler vehicles
  - 2 new Miner vehicles
  - Increased task cash rewards
  - Reduced shipment paycheck cash rewards
  - Check out the shop for hints of next vehicle drops
- Team UI changes
  - Select teams by clicking the whole card now instead of the button
  - Better console selection support
  - Initial team selection now fades out full teams, hiding the button
  - New players get auto-teamed when only one team is available
- Prospector Bonus
  - Joined the game for the first time? Enjoy a little bonus to ease your journey!
- Added a next vehicle tracker UI
- Added Pick Up Chain mechanic to Hauler vehicles
  - Allows you to pick up ores instantly within a certain timeframe from the last action
- All Cash Packs have been increased by 2.5x

### Changes
- Parking slots are now team-based, spawning closer to your target
- Increased max distance to location waypoints
- Increased pickaxe range 2 blocks -> 5 blocks
- Increased collapse penalty max from 5,000 to 1,000,000
- Reduced loading screen time
- Reduced atmosphere density
- Reduced MegaHauler size, now fits within the max mineable height provided by cash-bought vehicles
- MegaHauler now specifies that it may not always fit in the mine, tunnels depend on other Miners.
  - In the future, this vehicle will be able to act as middle-man for smaller vehicles so they don't have to get to the Refinery so often

### Bug Fixes
- Fixed getting cash with the Factory Director multiplier on other teams
- Fixed existing memory leaks + minor issues
- Fixed ores colliding with stairs
- Fixed vehicle lateral grip issues
- Fixed gantry flinging other packages when picking them up
- Fixed fuel packages and ore packages colliding with each other
- Fixed ore packages that have been submitted not getting cleared within the fuel conveyor area
- Fixed vehicle console keybinds not working sometimes
- Fixed teleporting out of the mine leaving ores in your cargo
- Fixed teleporting out of the mine causing a vehicle respawn

# Fixes & QoL
Version: 1.0.2
Date: 4 Jul 2026
Image: 123384908315879

### Changes
- Expanded tutorials
  - Checkpoints & Restoring (if you ever get stuck, resetting will bring you back to the last checkpoint)
  - Vehicle controls are now highlighted specifically
  - Dialogue will be redrawn to remind you of the task if you idle
  - Miner tutorial is now more straightforward and avoids mine-related softlocks
  - Transporter tutorial will not select the closest package, not forcing you to take on the tutorial one
  - Several other UX improvements
- Refinery Storage & Transporting fixes
  - All surplus packages will now get stored separately from the conveyor after a while ("Backup Storage")
  - Packages that failed to get shipped will now be removed after a while
  - Increased drop distance and added more wall protections on the shipment conveyor
  - Fuel will be teleported to the drop-off zone after a while
  - Fuel that failed to get delivered no longer locks out ships from bringing more
- Added setting to disable collapse shaking
- Added haptics when drilling, dropping things or taking them up as cargo
- Added a fuel location waypoint
- Renamed Stacker -> Lifter

### Fixes
- Fixed unloading sometimes not working
- Fixed Transporters dropping packages in air upon leaving
- Fixed console issues with Topbar Plus when opening your Index
- Fixed mobile prompt being small
- Fixed popup button strokes
- Fixed packages losing pieces when loaded onto the ship
- Fixed console issues with the Daily Rewards UI
- Fixed mine-related ratelimits
- Fixed ores sticking to the sides of the conveyor
- Fixed size of packager conveyor, packages shouldn't get stuck at the top anymore
- Fixed ores getting deleted in the Refinery during collapse
- Fixed leaving the vehicle not teleporting you out
- Fixed not being able to get out of the vehicle
- Fixed turning off drill not stopping drilling right away
- Fixed Team UI related issues
- Barrier fixes
- Fixed automatic translations not showing entirely in dialogues
- Fixed ores colliding with your camera when dropping them off
- Replication issues caused by tutorial assets (could have looked like exploiters)

### Other
- Dynamite no longer kills you in the shop or while on starter team
- Reduced Factory Director x 2X Cash bonus, miscalculated

# Fixes & QoL
Version: 1.0.1
Date: 1 Jul 2026
Image: 123384908315879

### Content
- Reworked vehicles!!!
  - Low-end devices should now run them fine
- Fuel Tank tool render
- Added cue signs to relevant areas (generator, mailbox)
- Mine Collapse additions
  - Changed Penalty from $100 to 5% of your cash [min $250 - max $5000]
  - Reduced required mined out % to cause a collapse
  - Collapse will now also happen when close to the % and no one has mined for a while
- Added new Bugs & Feedback UI
  - Replaces Roblox's one at the mailbox

### Changes & Fixes
- Waypoints now appear as soon as the dialogue starts
- Rebalanced turning radius and wheel rotation in all vehicles
- Increased night soundtrack volume
- Transporter tutorial now allows you to refill generator even when almost full
- Fixed packages spawning in the middle of the map
- Fixed issues with tutorial assets disappearing
- Fixed leaderboard perks assignment issues
- Fixed vehicle capacity UI not appearing on mobile
- Fixed toolbar slots breaking occasionally
- Fixed vehicle cleanup issues
- Fixed team leaderboard ordering
- Fixed doors breaking
- Fixed mine not regenerating, breaking the entire gameplay loop
- Fixed not being able to teleport out of the mine while not in a vehicle
- Fixed issues with badge awarding
- Fixed not being able to pick up other packages after the Transporter tutorial
- Fixed Haulback having an offset when picking up ores
- Fixed issues with the quest system
- Fixed pickaxe mining failure bug
- Fixed leftover velocity on vehicles, causing vehicle parts to become conveyors
- Fixed Team UI not tracking properly team changes
- Fixed Miner vehicles still drilling when out of the vehicle
- Fixed drop off beam arrows distance issues
- Fixed dialogue starting during vehicle fading screen
- Fixed not being able to see Waypoints when placed
- Removed invisible block next to leaderboards
- Reduced dialogue skip cooldown
