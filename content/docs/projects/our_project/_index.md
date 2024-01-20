---
title: Bottle Spinner
type: docs
---

# Bottle Spinner

## Abstract

The Bottle Spinner is a device tackling the issue of commercially available bottles holding shampoo, soap or even honey and glue.
Often times the consumer cannot empty the bottle whole, as the last few scraps will always get stuck on the bottom of the bottle.
This device solves this issue by using centrifugal force to bring all the contents of these bottles to the opening of these bottles.

## Introduction

The bottle spinner is a device that looks impressive, does what it should do, but is very much over the top. It should spin a
bottle until all the remaining contents stuck at the bottom of the bottle should be forced to the front. The concept we stuck 
with was to use a motor which would spin the bottle at high speed to create enough centrifugal force.

The first few concepts used a wheel, but it was rather quickly discarded, as the construction
of a whole wheel would be more complicated and add unnecessary weight on the motor to spin. The original plan also was for the
device to be mounted to a wall and have the rotation vertical, but that idea was quickly scrapped as well, as a horizontal rotation
would put much less strain on the motor.

{{< figure src="images/Concept.gif" caption="**Figure 1. 3D animated concept of the wheel concept.**" width="50%">}}

Instead, the approach was reduced to a single beam which allows the bottle to be attached. The device should be mounted on the
floor or table, so the device can rotate horizontally.

Due to the high spinning frequencies we intend to implement in our prototype, all aspects of safety must be precisely considered.
For the safety of industrial robots, the European harmonized standards EN ISO 10218-1 and EN ISO 10218-2 apply. The robot 
standards apply to systems with at least three freely programmable axes. Although there is no separate standard for handling 
systems with fewer axes, one can refer to the aforementioned standards. Industrial robots must be surrounded by protective 
devices that prevent people from entering the hazard zone. To conform to these standards, a cabin or fencing for the device
should be installed.

The materials used to build the bottle spinner were scrap electronics like an old drill, a discarded ceiling fan and an unused blender.
The structures that would additionally be added were planned to be out of wood.

## Related work 

### SpinsOut - Bottle Spinner

https://www.youtube.com/watch?v=TqadnMX2nVU

This product solves the same problem but with a handheld device made from cloth which the user has to spin themselves. 
Our product goes one step further in relieving the user of labour.

{{< figure src="images/SpinsOut.png" caption="**Figure 2. SpinsOut Bottle Spinner.**" width="50%">}}
## Implementation 

A detailed description of your prototyping process.
The plan was to use a motor of a broken or discarded item and use that to spin an arm on which the bottle is mounted to. For
that wood would be the preferred medium to build with. A cage to prevent any injuries from malfunctions or proximity to the
device is necessary.

### Iteration №1 - Ceiling Fan

In the first iteration, an old ceiling fan was used and the blades were dismounted. 
The ceiling fan still had a power cable and the rotational speed can be regulated in 2 different 
steps by pulling on a string. All of these components were mounted on a wooden board to keep stable, seen in Figure 3.

#### Complications

After testing the device with a provisionally added t-beam out of cardboard and the shampoo bottle mounted, the device was too
weak to spin at required speed, as seen in Figure 4.

| {{< figure src="images/ceiling fan arms.jpg" caption="*Figure 3. Ceiling fan prototype with cardboard beams and bottles mounted.*">}} | {{< video src="CeilingFan.mp4" autoplay="true" loop="true" muted="true" >}} *Figure 4. Ceiling fan Prototype* |
|:--------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------:|

An attempt was made to deconstruct the device and properly clean it, but after deconstructing the spinning
part of the ceiling fan, it was clear that this approach would overcomplicate things a lot, as the 
ceiling fan was already very old and only collected dust and grime for decades, additionally to that it is 
powered by a magnet ring shown in Figure 5, which would have deviated from the plan of using a motor.

{{< figure src="images/magnet ring.jpg" caption="**Figure 5. Magnet ring inside the ceiling fan**" width="50%">}}

After this, the ceiling fan approach was abandoned.

### Iteration №2 - Drill

The second iteration was started by deconstructing a discarded battery powered drill. The motor and 
the drill chuck was removed from the plastic hull. The battery pack was broken, so the cables connecting
to it inside the hull had to be cut. These were then connected to an unused power adapter using cable connectors.
Between the motor itself and the power adapter, the original trigger switch of the drill was mounted, which served
as the regulator of the rotational speed.

| {{< figure src="images/Drill 1.jpg" caption="*Figure 6. Battery powered drill with open hull.*">}} | {{< figure src="images/Drill 2.png" caption="*Figure 7. Drill without plastic hull*">}} |
|:---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------:|

To test this device, a drill bit was used and provisionally glued to a wooden beam, on which the bottle
was mounted. The device was strong enough to spin the bottle at sufficient speed, but was very unstable, as
the difference of weight on both ends of the wooden beam caused the device to be off balance.

{{< video src="Drill.mp4" autoplay="true" loop="true" muted="true" width="50%" >}}

**Figure 8. Battery powered drill prototype**

Another concern with this prototype was the stabilization and mounting onto an unmoving construction. However, before too
much thought was put into this problem, the third iteration of the project overtook the battery powered drill approach.

### Iteration №3 - Blender

In parallel to the previous iteration, another approach to the matter was built. This approach used a blender.
The upper part of the blender was completely removed and the inner workings were exposed by removing the hull. This
had to be done to enable a ranged operation of the mixer.

Onto the mixer a mount for hydraulic hoses was fitted, in which a wooden beam with a hinged joint was mounted. The wooden
beam has the bottle on the one side, and an adjustable sliding weight on the other. The hinged joint therefore acts as a 
balancing scale to be able to counterbalance the bottle with the weight accordingly. To make it easier to insert the bottle
into the machine, the bottle mounting mechanism also has a hinge joint built in, so one can insert the bottle vertically. The
bottle will then be tilted horizontally using the centrifugal force of the machine.

| {{< figure src="images/balanceWeight.jpeg" caption="*Figure 9. Wooden beam mounting*">}} | {{< figure src="images/BlenderBottleHinge.png" caption="*Figure 10. Bottle compartment*">}} |
|:-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------:|


The mixer handles
the extra weight well and spins at a more than sufficient speed than the iterations before. The second iteration
using the battery powered drill was soon discarded and the mixer was the final iteration of the project.

The rotary control, which originally regulated the speed of the spinning blades inside the mixer, was dismounted and 
connected with a 2.5m intermediate cable. This enables the control of the rotational speed from a safe distance, as the 
mixer was by far the fastest of the three iterations that were built so far. The rotary control initially had
4 different intensity settings, but only setting 1 and 3 are used. The others were covered in insulated tape.
Another addition to the remote control was an emergency button, which would cut the power supply to the blender off, 
in case of any malfunctions. These components were mounted onto a wooden piece, to have all the controls in one place.

Since the blender has a lot of power and carries more weight than usual, it runs hot. To counteract this, a cooling fan
of a discarded beamer has been added to the side of the device. It has centered (directional/radial) cooling and the fins
are directly aligned to the bearing and motor. The fan was connected to the power supply with insulating tape and runs on
12 Volts.

| {{< figure src="images/remoteControl.jpeg" caption="*Figure 11. Remote control*">}} | {{< figure src="images/coolingFan.jpg" caption="*Figure 12. Cooling fan*" >}} |
|:------------------------------------------------------------------------------------|------------------------------------------------------------------------------:|

The motor of the blender is an 800W direct current motor. It is connected from the power cable with 2 wires (brown: -, blue: +), which go through
a surge protector. The blue cable is now continued by a white cable. From there the cables were spliced:
* White (+) goes directly to the motor.
* Black (-) goes to the remote control.
* Yellow (-) is one of the pulse stages of the mixer. It comes from the motor, goes through the emergency button and into the rotary control.
* Red, yellow and brown are the levels of the rotary controller on the mixer.

{{< figure src="images/motor.jpeg" caption="**Figure 13. Motor of the blender**" width="60%">}}

#### Software

Since the Blender mechanism itself doesn't need any software to function, all the arduino code focuses on extras like an
audio warning if it runs too hot and a blinking light if the platform the blender is mounted to starts to shake.

The temperature sensor is mounted near the spinning mechanism of the blender, as this is the part that gets the hottest. It
sends a signal to the Arduino, which in turn sets of a buzzer if the temperature reaches a certain threshold. For the purposes
of the presentation, it has been set to a quite low temperature of 21°C, so the buzzer will be triggered.

```arduino
int buzzer = 8; //Arduino input 8
const long interval = 1000;
unsigned long currentMillis = millis();
temp = sensors.getTempCByIndex(0); 

if (temp > 21.00){
      if (currentMillis - previousMillis >= interval) {
        previousMillis = currentMillis;
        tone(buzzer, 1000); // Sende 1KHz Tonsignal
      }
    } else {
      noTone(buzzer);
    }
```

The motion processing unit (MPU) is mounted to the base of the mixer. When the platform starts moving, it triggers an RGB light, which
starts to flash in the three main colors red, green and blue. It uses the Gyro sensors of the MPU to determine if the platform shakes
more than the threshold. In that case, the LED starts to flash faster.

```python
MPU6050 MPU;
int GyroX , GyroY , GyroZ;
int crtl = 11;

MPU.getRotation(&GyroX, &GyroY, &GyroZ);
  if(GyroX < -1000 || GyroX > 1000 || GyroY > 1000 || 
  GyroY < -1000 || GyroZ > 1000 || GyroZ < -1000 ) {
    digitalWrite(crtl,   HIGH);
  } else {
  digitalWrite(crtl,LOW);
  }
```

#### Finished Prototype

The prototype itself and the arduino components were built separately and only in the end have been combined. After full assembly,
the prototype was tested thoroughly and footage had been recorded both from the outside and from the inside of the prototype.

| {{< video src="BlenderOutside.mp4" autoplay="true" loop="true" muted="true" >}} *Figure 14. Blender prototype* | {{< video src="BlenderInside.mp4" autoplay="true" loop="true" muted="true">}} *Figure 15. Blender prototype inside view* |
|:---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------:|


#### Complications

After a few successful tests, the plastic component of the mounted device spun off of the spinning iron rod in the middle.
As this was shortly before the presentation of the device, the device was provisionally fixed with glue and duct tape, as there
was no time, tools and materials for a more sophisticated fix. This however worked quite well and the device worked
as before.

## Conclusion

To come up with an idea and actually realizing it are two completely different things. There is a lot more work behind creating
prototypes as one initially thinks. An issue to fight with is time management and planning, understanding the components one
works with and properly testing them, to avoid sinking too much time into an idea which would not work. However, in the end
the bottle spinner turned out well and worked exactly as intended.

The prototype will however not be used in the future, and will probably be disassembled over time. It is a fun device, however
it is not very practical and quite bulky, so keeping it would need a lot of storage space.