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
