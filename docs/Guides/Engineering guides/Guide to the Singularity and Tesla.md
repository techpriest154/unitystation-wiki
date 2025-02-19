# Guide to the singularity and tesla engines
Note: while both the singularity and the tesla are simpler than the [nuclear reactor](Guide-to-the-nuclear-reactor.md), the cost for failure is much higher. Because of this you should be familiar with [engineering](Engineer.md)
BEFORE touching it, unless, of course, you intend to make the engine fail from the getgo.
 
## overview
The singularity and the tesla are very similar to eachother, to the extent that a single guide can comfortably cover both. While they differ in some aspects, such as power generation,
they can generally be treated the same way. This guide will cover the specifics of both, how to start them, and how to run them.

## Background
It is important to know just how the singularity and tesla reactors work before setting them up.

### The particle accelerator
The particle accelerator, commonly reffered to as the "pa" is a multi-part machine that draws a large amount of power in order to create streams of high energy (damaging)
particles. a particle accelerator forms a T shape, with the upper part of the "T" made from the 3 emitter sections. A console is attached to one side of the particle accelerator, from where
it is controlled.

In the console, the particle accelerator can be turned on or off, and its power level can be changed. Higher power levels will result in greater growth of the
singularity and tesla, possibly to a dangerous extent. Each power level will take an increasing amount of power being fed into the PA to be sustained or activated.

The particles emitted by the PA are able to pass through shields (but not the shield emitters!), and upon repetedly hitting the singularity and tesla generators will cause them to form a singularity or tesla ball.
They will also "feed" both the singularity and tesla once they are generated.

### The shield generators (and emitters)
The shield generators serve to keep the very dangerous objects inside them contained. To do this, they must first be wrenched down. The shield emitters DO NOT recive power from wires,
and must instead be powered by being shot at by an emitter. Emitters periodically shoot a green beam in a straight line, which deals high damage if it hits a player. Once a shield generator
is charged, it can be turned on by hand, at which point it will spread its shields and (to an extent) its power among the other shield emitters. The general shield generator setup, which works for
both the singularity and tesla is a 5x5 square, with the generators in the corners, a space of three empty tiles between them.

Keep in mind, that having too many shields and not enough emitters may mean that the shields drain power faster than the emitters can supply, and will lead to the shields eventually failing.

### singularity and singularity specific machines
The singularity will destroy objects and players/mobs that fall into it, and will suck loose items, people, and creatures towards it. Touching the singularity is a gaurenteed death sentence,
and a loose singularity is often enough reason to call the shuttle. The singularity will wander around, even when contained, but cannot destroy or pass shield generators unless sufficiently large.

The singularity can grow by absorbing mass (ie: you and the rest of the station), which can be provided with some safety using the particle accelerator. The singularity will slowly decline in mass,
converting it into radiation, but the rate of mass conversion is low enough that a loose singularity will generally not "starve". 

Radiation collectors are how you get power from the singularity. They will convert the radiation the singularity produces into electricity, which can be used in turn to power the station.
You will want to place these as close as you can to the shield field, but not between the shield generators or within the bound of the singularitys containment zone. Then, wire them back into the station.
After being placed and secured, the radiation collectors can then be deployed by being clicked. They will only function in their deployed state.
Funnily enough, there is no distinction in the raditaion produced by a singularity and a nuclear reactor, so these can also be used aboard stations without a singularity to enhance
power output.

To create the singularity itself, you will need a singularity generator. The singularity generator should be placed in the center of the shield square, where it can be hit by a PA.
It does not need to be wired to anything. When shot with the PA repetedly (prefferably after the shield generators are on), it will create a stage one singularity, which takes up a single tile.
Due to the nature of the singularity, the generator is destroyed in the process.

The singularity can then grow more and more as it is fed. A stage two singularity will generate more power, and take up 4 tiles, but require more mass to sustain itself (this trend of later stages converting mass faster continues)
It can provide power to most stations without much difficulty.

The largest stations may require a stage 3 singularity. While containable in the same way as the earlier stages, it takes up 9 tiles. It requires a large amount of incoming mass to sustain itself, but be careful
to not over-feed it, as it becomes far more difficult to contain later stages.

Stage 4 and 5 singularities will tear apart walls and ordinary machinery, even through shield generators. While a stage 4 singularity can be THEORETICALLY contained (does not rip out shield generators), a stage 5 singularity
will flat out consume anything containing it, and is gaurenteed to get loose. Generally, you will only see a stage 4 and 5 singularity when a singularity has already broken loose and ate enough
of the station to grow to such a size.

There is a fifth type of singularity, a supermatter singularity, which can only occur if a sufficiently large singularity eats a supermatter crystal. it takes up an enormous area, has a massive pull, and you are
generally fucked if one happens to exist. Dont bother trying to contain it, it will set you on fire and turn you into an atom-thin noodle. 



### tesla and tesla specific machines

In comparison to the singularity, the Tesla has both numerous upsides and downsides. Like the singularity, the core of the tesla will wander aimlessly. It will emit periodic electric arc blasts.
The strengh (and power generation) of these blasts is proportionate to the number of orbs orbiting the tesla itself. Upon reaching a machine or player, the arcs will do enormous damage or explode the machine (oftentimes with
enough power to cause breaches). The damage from being hit by an arc is oftentimes enough to instantly kill a player, and insulated gloves will not save you. These arcs make the tesla far more dangerous
when it is loose than a singularity.

Unlike the singularity however once the tesla has been set up it does not require babysitting and is easy to contain. The tesla cannot break the machinery around itself from within
if the machinery is set up correctly, even if the tesla is at its maximum size.

The teslas arcs will prioratize hitting grounding rods and tesla coils over everything else. Grounding rods serve to stop the arcs from damaging the coils or shield generators, and the coils
convert the arcs into power. A tesla coil or a shield generator hit by an arc without any grounding WILL be damaged, which can cause the containment to fail if set up incorrectly.

The tesla and the singularity are generated through near identical means, though the tesla instead uses the "tesla generator". Hit the tesla generator and the tesla it creates with
PA blasts to create the tesla core and grow orbs around it. Unlike the singularity however, the tesla does not break loose when it is too large, so feel free to hit the PA to the maximum and leave it on.

## Setting up the generators

0: In both cases you will want to find a 5x5 (or larger) empty region, along with space for the emitters, wiring, and the PA. Gather the appropriate material, which is the PA parts, wires, machines specific to the generator you
want to create, shield generators, and emitters. The region should also have good access to the stations power grid.

1: Place the shield generators in the corners of the 5x5 (or larger) square. there should be a space of 3 tiles between them if you are using a 5x5 region. Wrench the generators down. The generators do not have to be wired to anything.

2: Place emitters facing the generators. Typically, a one tile gap is left, but this is optional. The emitters should be wired to the stations power grid or otherwise supplied with power.
   As emitters are dangerous and consume large amounts of power, dont turn these on yet. Remember to wrench them down one they are facing the proper direction and then weld them to the ground.
   
3: Move your chosen type of generator (singularity or tesla) into the very center of the construct. It should be equidistant to all of the shield generators where it can be easily
   hit by the PA. Wrench or weld it down if possible.

4: Build the PA. The similar looking rectangular regions with what look like red coils ontop of them should form the top of a T shape (if you aim your PA up). They are labelled as to which
side they should be placed on. These, and all other parts, should be wrenched down when they are placed.

Directly behind them, set up the part that looks like an exposed coil or magnet tube. The red part of it should face the regions you just placed.

Behind this, set up the console interfacing part. It is rather clearly asymmetrical. If the PA is facing up, the flat region should face the right.
In the adjacent region to the flat part, you should place the console itself

And, to cap it all off, use the part which looks bullet like.

Wire the console or any part of the PA to a power source. The PA demands very large amounts of power, so a plasma generator, the station grid, or existing reactor is reccomended. Test fire the PA (FOR ONE BLAST!)
at the construct to see if it works.

There should be nothing in the path of the PA. Floors and glass are fine, as are tables, but grilles, emitters, shield generators, and walls will block the particles. Notably, the energy barrier put up by shield generators
will not block the particles.

4.5 A: If you are making a singularity: place radiation collectors along the outside of where the shield field will be generated. wrench them down. they should not block the PA particle's paths. Deploy them by clicking them. Wire them to a transformer and
other electrical converters

4.5 B: If you are making a tesla: Place one tesla coil at each side of the construct except for the one facing the PA. At the same time, place one or two grounding rods on each side. Wire the tesla coils to a transformer or other
electrical devices and be sure that they are wrenched in place.

5: turn on the emitters. If they were set up correctly this should be as simple as clicking on them. otherwise, check that they are secured and powered.

6: Wait for the emitters to power the shield generators. This is represented by a bar on the shield generator that will slowly fill up with a light blue color as the generator gets more power

7: When the generators are full, turn them on. This will create the shield field.

8: Return to the PA and turn it on. This will create a contained singularity or tesla which will begin creating power. Be sure to keep it fed, but not too large. If your tesla coils
or radiation collectors were properly wired to the station (see [guide to electricity](Guide-To-Electricity.md)), you will be providing power.


