# Here are issues that are known that have not been fixed in this package

#### R17 Assimilator
* Reaper 17 uses Scrin Assimilator instead of it's own. However in order to implement their own Assimilator, will need to find and edit every structure in the game.

#### NOD Turrets
* Shredder turrets and Laser Cannons have no visual update when upgraded. Need to reuse models and create unique visuals for the Hubs, like Tibcore upgrade

#### Quad Turrets
* Quad Turrets cause Desyncs in online multiplayer. A theory on the cause is the object is given a weapon after having none.
* Models have been worked around but still want to refine it, and create proper damage animations. Still need to create RUBBLE animations

#### Aircraft ammo Counter in unit portrait
* Feature added in TW 1.05. Since KW was built before this version, this feature was not added in. Don't think it is possible to add back in

#### Space Command Uplink Effects
* It is possible the devs intended to add a distortion effect but instead broke everything, removing the smoke. While the smoke has been fixed, the distortion has been removed.

#### EMP
* EMP effects have the tendency to lag online games, most notable with EMP grenade probably due to overlap
 
#### Cultist
* AI are not able to use mind control
 
#### Ravager
* AI are not able to use Tiberium Agitation properly
 
#### Railgun Accelerator Heal
* Objects affected by Railgun Accelerator when healed by repair drone or structure repair will no longer take penalty damage when still under the effect
 
#### Neutral Structures
* ZOCOM and Veteran Snipers cannot spot for bombard in structures
    * Even then, will need to recompile EVERY map for the changes to take effect
* NOD Garrison fix will not take effect until maps are recompiled (non compiled maps already work)
 
#### Redeemer
* Rage Generator effect begins as soon as the ability is activated instead of when the visual effect takes place. Whether or not this was intentional
 
#### Sonic Repulsion Field and Laser Fencing
* If structure was already targeted by a commando or engineer when the special power was added, commandos will still destroy the structure and engineers will still capture
* Your own engineer cannot enter your own structure to repair when Field or Fence is in effect.
 
#### Mechapede
* Mechapede Head does not spawn from the Warp Sphere, instead spawning at the rally point due to the BannerCarrier squad position

#### GDI Foxhole
* An exploit exist where the infantry creating the structure can be crushed by a unit in formation move when garrisoned

#### OCL_Generic_Tree_Crusher
* The intended purpose of this OCL is to remove objects in RubbleState, however this has the side effect of permanently destroying NOD Turrets. Best solution would be to remove it from all weapons
 
#### Force Fire
* Some units cannot Forcefire onto friendly or own objects and more importantly; own husks
