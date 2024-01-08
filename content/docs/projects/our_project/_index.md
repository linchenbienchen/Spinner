---
title: Bottle Spinner
type: docs
---

# Bottle Spinner

## Abstract

The Bottle Spinner is a device tackling the issue of commercially available bottles holding shampoo, soap or even honey and glue.
Often times the consumer cannot empty the bottle whole, as the last few scraps will always get stuck on the bottom of the bottle.
This device solves this issue by using centrifugal force to bring all the contents of these bottles to the opening of these bottles.

The Bottle Spinner uses centrifugal force to bring all the contents of shampoo bottles or even substances like honey or glue to the front of the bottle.
## Introduction

A detailed description of the concept and sketches of the planned implementation.

If a section grows too large or handles a very specific part of the project it can be put into [subpages]({{< ref "subpage_1#how-to-format" >}}).

{{< figure src="get_in.jpg" caption="*A drawing by David Shrigley.*">}}

## Related work 

References to related concepts, projects, books, websites, stories, systems, fruits, etc. and their relation to the project at hand.

## Implementation 

A detailed description of your prototyping process.
The plan was to use a motor of a broken or discarded item and use that to spin an arm on which the bottle is mounted to.

### Iteration №1

In the first iteration, an old ceiling fan was used and the blades were dismounted. 
The ceiling fan still had a power cable and the rotational speed can be regulated in 2 different 
steps by pulling on a string.

All of these components were mounted on a wooden board to keep stable. After testing the device with a
provisionally added t-beam out of cardboard and the shampoo bottle mounted, the device was way too
weak to spin at required speed.

{{<row>}}
{{< figure src="images/ceiling fan arms.jpg" caption="*Ceiling fan prototype with cardboard beams and bottles mounted.*" width="98%">}}
{{< figure src="images/ceiling fan.gif" caption="*Ceiling fan prototype*" width="98%">}}
{{</row>}}

An attempt was made to deconstruct the device and properly clean it, but after deconstructing the spinning
part of the ceiling fan, it was clear that this approach would overcomplicate things a lot, as the 
ceiling fan was already very old and only collected dust for decades, additionally to that it is 
powered by a magnet ring, which would have deviated from the plan of using a motor.

{{< figure src="images/magnet ring.jpg" caption="*Magnet ring inside the ceiling fan*" width="50%">}}

After this, the ceiling fan approach was abandoned.

### Iteration №2

The second iteration was started by deconstructing a discarded battery powered drill. The motor and 
the drill chuck was removed from the plastic hull. The battery pack was broken, so the cables connecting
to it inside the hull had to be cut. These were then connected to an unused power adapter using cable connectors.
Between the motor itself and the power adapter, the original trigger switch of the drill was mounted, which served
as the regulator of the rotational speed.

{{<row>}}
{{< figure src="images/Drill 1.jpg" caption="*Battery powered drill with open hull.*" width="98%">}}
{{< figure src="images/Drill 2.png" caption="*Drill without plastic hull*" width="70%">}}
{{</row>}}

To test this device, a drill bit was used and provisionally glued to a wooden beam, on which the bottle
was mounted. The device was strong enough to spin the bottle at sufficient speed, but was very unstable, as
the difference of weight on both ends of the wooden beam caused the device to be off balance.

{{< figure src="images/Drill.gif" caption="*Battery powered drill prototype*" width="50%">}}

### Iteration №3

In parallel to the previous iteration, another approach to the matter was built. This approach used blender.
The upper part of the blender was completely removed and the inner workings were exposed by removing the hull. This
had to be done to enable a ranged operation of the mixer. The turning knob, which originally regulated the speed
of the spinning blades inside the mixer was dismounted and connected with a longer intermediate cable. This
enables the control of the rotational speed from a safe distance, as the mixer was by far the fastest of
the three iterations that were built so far.

As with the iteration before, a wooden beam was mounted on the mixer instead of the blades. The mixer handles
the extra weight well and spins at a more than sufficient speed than the iterations before. The second iteration
using the battery powered drill was soon discarded and the mixer was the final iteration of the project.

## Conclusion

A reflection on your prototyping process and the project outcome. What happens to the prototype after the project?