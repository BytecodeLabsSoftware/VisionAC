# Vision
Vision is an advanced anti-cheat solution for Minecraft 1.8 servers.

## This repository is made for reporting issues with Vision. No source code is available.

## Features
### Packet Based
Vision is a packet based anticheat, meaning it can send and receive packets. This allows for better checks.

### Lag Compensation Included
Vision also compensates for players with high ping. Doing this ensures there is less risk of false positive.

### Movement Prediction 
The anticheat will also have movement checks that will catch cheaters using prediction. How it works is that once a player sends a movement packet, the anticheat compares it to a list of possible positions. If it doesn't match to any of the positions, the player is likely cheating.
