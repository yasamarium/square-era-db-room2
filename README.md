# Square Era Database - Room 2: Survival Frontier

Persistent world modifications, player profiles, and session state for Square Era 3D Voxel Sandbox Room 2.

## Room Overview
- Room ID: 2
- Room Name: Survival Frontier
- Game Mode: SURVIVAL
- Description: Hardcore Survival Frontier, shared mining shafts, mob defense, and resource cooperation.
- Server Repository: [yasamarium/square-era-server-room2](https://github.com/yasamarium/square-era-server-room2)

## Schema & Files
- `data/world.json`: JSON map of persistent chunk modifications `[ ["x,y,z", blockId], ... ]`.
- `data/players.json`: Registered player profiles and session records.
- `data/chat.json`: Persistent in-room chat history.
- `data/sessions.json`: 5-hour runner cycle timestamps and synchronization checkpoints.

Zero external databases required. Backed 100% by GitHub Git persistence.
