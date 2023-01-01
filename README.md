# crustbots

The idea behind this game is a cross between crobots and an RTS (with a little bit of Rescue Raiders inspiration.)  Rather than giving orders to the units in an RTS, you write programs to automate each unit.

There is some kind of resource accumulation, either automatic or gathered by units ("bots"?)

Units can be created using the accumilated resources at a cost based on the unit's components:

* Engine (power)
* Weapons (range, damage)
* Radar (distance, width - like crobots)
* Compute (speed, memory)
* Communication (range - send messages back to base, fog of war)
* Resource detection
* Resource gathering

Other stuff
* Fog of war - you can only see what units can see & report (communication range)
* Weight (based on the components)
* Speed (calculated based on power & weight)


There should be a "library" of personal code.
There should be a list of pre-defined units.

Programming robots in WASM (wasmi) so you can code in any language and compile/upload WASM.
