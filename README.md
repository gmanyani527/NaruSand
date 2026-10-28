Jujutsu Kaisen-Inspired Quake 4 Mod
A fan-made action combat mod for Quake 4, inspired by Jujutsu Kaisen. The project expands Quake 4's combat with cursed techniques, high-speed movement, close-range attacks, and a cursed energy resource system.
Project status: In development. This README documents the design proposed for the mod; listed features are not necessarily implemented or complete.

Project Overview
The goal is to turn Quake 4 into a faster, ability-focused combat experience. Players will be able to combine movement abilities such as teleportation and dashing with spatial attacks, melee strikes, and powerful special moves.
Planned Features
Cursed Technique: Blue
A spatial attack that pulls nearby enemies toward a point.
- Based on the grenade launcher.
- Throw a projectile that travels to a target location.
- Keep the effect active for approximately 2–3 seconds rather than exploding immediately.
- Pull nearby enemies inward before the effect disappears.
Cursed Technique: Red
An explosive repulsion attack that pushes enemies away from its impact point.
- Based on the rocket launcher.
- Fire a forward-moving projectile.
- On impact with an enemy or surface, generate a blast.
- Detect entities within a radius, apply outward knockback, and deal damage.
Teleportation
- Teleport a short distance in the direction the player is looking.
- Allow upward teleportation when aiming into the air.
- Limit maximum teleport distance to prevent crossing entire maps.
- Explore a flash or distortion effect for feedback.
- Enable aerial setups, such as teleporting above an enemy before attacking.
Dash
- Rapidly move in the player's chosen movement or look direction.
- Explore directional dashes: forward, backward, left, and right.
- Consider a brief field-of-view (FOV) increase for speed feedback.
- Extend the system to midair dashes.
Cursed Energy System
Abilities consume a regenerating resource, with a proposed maximum of 100 cursed energy. A HUD meter will eventually display the current amount.
Ability	Proposed energy cost
Basic Punch	0
Dash	5
Teleport	10
Blue	20
Red	25
Reverse Cursed Technique	30
Domain Expansion	100


These are initial balancing targets and may change during development.
Reverse Cursed Technique
- Spend cursed energy to restore player health.
- Add a visual or audio effect while healing.
- Use a cooldown to prevent repeated healing without limitation.
Punch and Melee Combat
Introduce short-range attacks that detect enemies in front of the player, deal damage, and apply knockback. The proposed melee variations include:
Attack	Intended behavior
Normal Punch	Fast attack with standard damage
Heavy Punch	Slower strike with more damage and knockback
Uppercut	Launches an enemy upward
Air Punch	Allows melee combat while airborne


Additional goals include impact effects, punch sounds, basic combos, and movement-to-melee combinations using dash or teleport. The melee system will also provide the foundation for Black Flash.
Black Flash
A powerful close-range strike built on top of the melee system.
- Detect an enemy at short range in front of the player.
- Deliver increased damage and strong knockback.
- Emphasize impact with red/black flashes, particles, sound, brief screen shake, and possible FOV effects.
- Consider an energy cost, cooldown, and future timing-based activation.
- Explore combo interactions and bonuses after a successful hit.
Domain Expansion
An ultimate ability that transports the player into a separate supernatural combat space.

Activation and environment
- Activate with a dedicated key and consume substantial cursed energy.
- Use screen shake, distortion, and a fade to black as transitions.
- Load a custom arena with dark lighting, fog, particles, and potentially Blender-created models.
Inside the Domain
- Temporarily enhance attacks and movement techniques.
- Explore faster or unlimited energy regeneration and shorter cooldowns.
- Include enemies or a stronger boss encounter.
- End after a time limit or the defeat of a boss, then return to the normal map.
Development Roadmap
The following phases organize the proposal into an implementation sequence. They are planning stages, not claims of completed work.

Core movement: teleportation, dash, movement limits, and feedback effects.
Energy management: cursed energy values, regeneration, ability costs, and HUD display.
Spatial techniques: Blue's pull behavior and Red's blast/knockback behavior.
Combat systems: basic melee, punch variants, Black Flash, hit effects, and cooldowns.

Technology
- Game: Quake 4
- Modding: Quake 4 game code and engine systems
- Potential custom assets: Blender (for Domain arena models)
Notes
This is a fan-made, non-official project inspired by Jujutsu Kaisen. It is not affiliated with or endorsed by the creators or rights holders of Jujutsu Kaisen or Quake 4.
Installation and Controls
Installation steps, keybindings, and build instructions will be added once the release setup is finalized.
