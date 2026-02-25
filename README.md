# The skill tests of light-gun shooters

***warning: screen flashing on practically all video links***

Documenting and defining the skills that light-gun games routinely test, and demonstrating the concepts with timestamped video examples. It may be updated as I get more familiar with the genre and play more games, and serve as a basis for other game design posts, and as kind of a glossary for light-gun game concepts. If you're designing a game of this genre, I hope this can help you decide what kind of game you want to make, and maybe give you new enemy/level/encounter design ideas.


## The list

* **Precision / Accuracy**: getting as many shots as possible on some target(s) and missing few.
  * *Example:* any game with an "accuracy" bonus, or combo/chaining scoring system. For survival, [this attack from The Fool](https://youtu.be/kAhBcAaT5Vg?si=7VSvlykTj24dPbJf&t=701)
  
* **Rapid firing**: firing as many shots at a target, trading precision for raw fire-rate.
  * *Example:* [this attack from The Sun, House of the Dead 3](https://youtu.be/kAhBcAaT5Vg?si=wpTyuLU6tEvvTBO1&t=972)
  
* **Quick reacting**: From the moment a target is shown on screen, identifying and shooting the target as quickly as possible.
  * *Example:* [shoot the birds, Point Blank 3](https://youtu.be/DK4jxtGhLLk?si=WlImRulUKni08Ap5&t=133)
  * note: hard to find examples that aren't mixed with either Target IDing or routing
  
* **Quick aiming** (may need better name): getting one or multiple accurate shot-s on a moving target.
  * *Example:* [this attack from The Wheel of Fate, House of the Dead 3](https://youtu.be/hAAwtTDEw7s?si=fsy1dTs8X65FhS_o&t=674)
  
* **Shot counting**: reloading only when clip is empty, pulling trigger only when clip is not empty.
  * *Example:* any game with limited ammo clip, so like 99% of light-gun games
  
* **Quick reloading**: minimizing reloading time.
  * *Example:* any game with a "shoot outside the screen" reload system (eg: HotD 1\&2), you can find this in a lot of video links here
  
* **Hit counting**: shooting the strictly required amount of bullets to take out a target, or get maximum points.
  * *Example:* *everything*, but more notably games with "3-point shot" like the Virtua Cop series and [Time Crisis 2-4](https://youtu.be/gPo9DL73xdQ?si=9nCHkVQHwe6SdwuU&t=88)
  
* **Memorization**: in light-gun game context, pre-emptively aim and shoot at targets you know are going to appear.
  * *Example:* any game in which threats spawn at a constant, pre-determined coordinate
  * note: this concept applies to many, *many* video games, but light-gun staples like Time Crisis and House of the Dead have entirely static enemy spawns and movement patterns
  
* **Use of environment**: killing enemies with explosive things from the environment.
  * *Example:* explosive barrels or [vehicles](https://youtu.be/3_N7VfY04Gw?si=wSR4yAnyrsCzcNNI&t=267), shooting a thing to make it [fall on enemies](https://youtu.be/j3H90PxuE08?si=eJ7r1Aa70E90UtQn&t=1836), etc.

* **Threat management**: with two or more enemies on screen, identifying and shooting the most imminent danger.
  * *Example:* games with crowded enemy encounters, such as [Operation Wolf](https://youtu.be/dcIKACxhFRo?si=wzVBAM_xOS2Y6rE2&t=409) or others

* **Target IDing**: in games with shootable hostages/bombs, confirming enemy ID before shooting.
  * *Example:* [Time Crisis 3 rescue mission, stage 3](https://youtu.be/HNJ6R33Yr5Y?si=dx_QwQSWcaTkzM8G&t=400)

* **Sniping / "accurate shot"**: identifying and shooting a small target on screen, either a small or faraway shootable object (enemy/item/destructible env.).
  * *Example:* [Training mission 7, House of the Dead 2](https://youtu.be/FHGLGmdvArQ?si=k2JOvaWyQlEeQGdb&t=6)
  
* **Weapon selecting**: in games with multiple weapons, choosing the best tool for each target.
  * *Example:* [Trauma Center series](https://youtu.be/vhrq180YPtI?si=gJRxNWW_srsCbr6G&t=22), also Time Crisis 3 onwards
  * note: I very strongly believe Trauma Center to be a light-gun game, on the grounds that it tests *the grand majority* of this here list

* **Routing**: planning the use of limited ressources ahead.
  * *Example:* games with limited ammo guns, or limited projectiles like House of the Dead 4 or [Operation Wolf](https://youtu.be/YPkRzS_2P40?si=MIDnJBYm50YNPQZb&t=135)
  note: also a more general principle, especially run-based games like arcade games and the rogue-like genre

* **Multi-killing**: shooting at two or more lined-up targets with a single shot
  * *Example:* [Elemental Gearbolt (large hitbox + piercing shot)](https://youtu.be/EgwANIOpXFs?si=WUA4OeP9FHPJwonC&t=917), House of the Dead 3 (large hitbox shot)
  
* **Rhythm firing**: in games with a limited fire-rate but no auto-fire, firing shots as close to the fire-rate speed as possible.
  * *Example:* [Elemental Gearbolt](https://youtu.be/EgwANIOpXFs?si=DKYJJbnRLIR_MtyK&t=1010) (this is the only game I know of that does that)



## Effects on a game

From a developer's perspective, making a light-gun shooter involves figuring out what kind of game you want to make and which skills and playstyles you want to emphasize.
There are commonly seen design choices that will valorize some aspect while downplaying another, such as:

* A machine gun (fast fire-rate + auto-fire) based game will eliminate the need for rapid firing, and will often be compensated by ramping up the number of enemies per encounter, which may require more threat management.

* Games that don't use "shoot outside the screen to reload" will have a hard-coded, fixed reload time: how long it takes is how important shot counting will be, and how effective rapid-fire can get

* Having to identify target before shooting increases overall reaction time.

* A game may punish hostage killing with either a score penalty, or life penalty. If it is not detrimental to survival, the player's need to ID target is lessened, and hostages become merely a threat management issue.

* Fully static/deterministic games are *very* subsceptible to memorization, which with time will make many strategies here secondary

* Large hitbox bullets will make shooting small and faraway things easier, and can make multi-killing a viable strategy, while small hitbox bullets will make rapid-fire weaker and require stronger precision from the player.

* There may be collectible guns that are straight upgrades, but come with limited ammo: strong precision and hit counting will matter more for survival, as the player will be able to use that weapon for longer.

* It is useful to see precision<->rapid-fire as a strategy gradient; a faraway threat will need more confirming aim, while the closest may be panic-killed with spray-and-pray tactics.

* The inherent shakiness of light-gun technology imposes a limit on how accurate a shot can be expected to be. If you're making a game for actual light-guns and/or infrared-based (aka. not mouse), make sure your targets are not too small to hit.

* Often, threat-management-heavy games involve routing as well, giving the player grenades/bombs that (partially or fully) clear the screen and are strictly limited in uses.

I leave judgment of which paths to take; this is not (*yet*) an opinionated article. As mentioned, make the game you want to make, entice the player to your tastes and beliefs; you're the boss.

---

Note: the broader genre of gallery shooters may or may not involve a light-gun and instead use a mounted gun, or a joystick/some form of directional input with fixed traveling time. They involve other skills that are out of the scope of this post (for now?).
