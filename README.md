# SquareCruiser
Mod that adds the Square Cruiser to the game FTL: Faster than Light.

Requires the [Hyperspace mod](https://github.com/FTL-Hyperspace/FTL-Hyperspace) for the multi-page ship list, as it does not replace any vanilla ship. Hyperspace also has a fix for the “WEAPONS” and “AUTOFIRE” graphics overlapping for ships with 2 or less max weapons, applicable for Square B.

The release SquareCruiser.zip contains folders "data", "img" and "mod-appendix". Change the file extension from .zip to .ftl to use as a mod with the [Slipstream Mod Manager](https://github.com/Vhati/Slipstream-Mod-Manager).

If what you see in-game does not match the advertised description, please submit an issue, or contact me on Reddit (CommunistMountain) or Discord (CommunistMountain#0463).
<hr>
Pros (all layouts):
<ol>
	<li>Non-human crew.</li>
	<li>Short distance between Systems.</li>
	<li>Central Medbay/Clonebay, allowing crew to heal/revive and get back to stations fast.</li>
	<li>All rooms except Medbay/Clonebay can be vented, which makes extinguishing fires, suffocating intruders and funneling intruders into the Medbay (A and B) easy.</li>
</ol>

Cons (all layouts):
<ol>
	<li>Low starting crew, system levels and/or reactor.</li>
	<li>Compact design means it is more likely for enemy beams to hit multiple rooms.</li>
	<li>Less systemless rooms means it is more likely for the enemy to damage an important room.</li>
	<li>If the Medbay/Clonebay is hacked, crew are isolated from each other.</li>
</ol>

Lore: The Federation is strapped on cash, thus ships are compact and poorly-equipped, not even enough for proper textures.

[Square A in Hangar](https://raw.githubusercontent.com/CommunistMountain/SquareCruiser/main/preview-images/SquareA%20Promo.png)

Square A (The Hip): Weapon focus. "Making the most of a limited budget, this ship is designed to minimise distance between systems and funnel intruders towards the Medbay."
<table>
	<tr>
		<td>Crew</td>
		<td>1 Rock, 1 Engi</td>
	</tr>
	<tr>
		<td>Systems by Level</td>
		<td>1: Engines, Oxygen, Medbay, Piloting, Sensors, Doors; 2: Shields, Weapons</td>
	</tr>
	<tr>
		<td>Weapons/Drones Max Slots</td>
		<td>4 Weapons, 2 Drones</td>
	</tr>
	<tr>
		<td>Starting Resources, Reactor, Weapons/Drones</td>
		<td>16 Fuel, 0 Missiles, 0 Drone Parts, 7 Reactor, 1 Burst Laser 2</td>
	</tr>
	<tr>
		<td>Augmentations</td>
		<td>None</td>
	</tr>
</table>

[Square B in Hangar](https://raw.githubusercontent.com/CommunistMountain/SquareCruiser/main/preview-images/SquareB%20Promo.png)

Square B (Reg Forgone): Drone focus. "This ship was designed by a drone fanatic, capable of controlling up to 4 drones at once, and starting with a Drone Recovery Arm."
<table>
	<tr>
		<td>Crew</td>
		<td>1 Zoltan</td>
	</tr>
	<tr>
		<td>Systems by Level</td>
		<td>1: Engines, Oxygen, Weapons, Medbay, Piloting, Doors; 2: Shields, 4: Drones</td>
	</tr>
	<tr>
		<td>Weapons/Drones Max Slots</td>
		<td>2 Weapons, 4 Drones</td>
	</tr>
	<tr>
		<td>Starting Resources, Reactor, Weapons/Drones</td>
		<td>16 Fuel, 0 Missiles, 2 Drone Parts, 6 Reactor, 1 Combat Drone 1, 1 Beam Drone 1</td>
	</tr>
	<tr>
		<td>Augmentations</td>
		<td>Drone Recovery Arm</td>
	</tr>
</table>

[Square C in Hangar](https://raw.githubusercontent.com/CommunistMountain/SquareCruiser/main/preview-images/SquareC%20Promo.png)

Square C (Fang Xing): Boarding focus. "This ship goes all-in with the boarding strategy, having more crew, a Crew Teleporter, and the ability to bypass supershields."
<table>
	<tr>
		<td>Crew</td>
		<td>1 Slug, 1 Crystal, 1 Mantis</td>
	</tr>
	<tr>
		<td>Systems by Level</td>
		<td>1: Oxygen, Weapons, Teleporter, Clonebay, Piloting, Doors; 2: Shields, Engines</td>
	</tr>
	<tr>
		<td>Weapons/Drones Max Slots</td>
		<td>3 Weapons, 3 Drones</td>
	</tr>
	<tr>
		<td>Starting Resources, Reactor, Weapons/Drones</td>
		<td>16 Fuel, 0 Missiles, 0 Drone Parts, 5 Reactor</td>
	</tr>
	<tr>
		<td>Augmentations</td>
		<td>Zoltan Shield Bypass</td>
	</tr>
</table>

[All systems and weapon mount locations (white/red: available/not available at start).](https://raw.githubusercontent.com/CommunistMountain/SquareCruiser/main/preview-images/Square%20Layouts.png)

For modders: Internally they are called PLAYER_SHIP_SQUARE_CM (_2, _3). Only enough weapon mounts for Weapons Control for each ship, add more if you wish.
