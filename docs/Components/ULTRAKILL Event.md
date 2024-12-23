# ULTRAKILL Event
---

ULTRAKILL Events are a list of Game Objects to activate or deactivate and events to run on Activate and on Deactivate.

They are not a seperate component, but they are used by other components to run custom events when something happens.

![ULTRAKILL Event](assets/ultrakill-event-component.png)

## To Activate Objects, To Dis Activate Objects
When this ULTRAKILL Event is triggered, the objects in the first list will become active, while Game Objects in the other list become inactive.

## OnActivate()
Here, you can create custom behaviours by running methods on already existing components.

First, you have to click on the `➕` icon to create a new entry.

You then have to select a Game Object that has your desired function you want to use. (You can use the same Game Object your ULTRAKILL Event is on.)

Finally, it will let you select a function to run when the ULTRAKILL Event is triggered.

![Object Activator Example](assets/ultrakill-event-example.png)

This is an example where the Player gets teleported when the [Object Activator](/components/object-activator)'s ULTRAKILL Event is triggered.

## On Dis Activate()
This part of ULTRAKILL Event is rarely used.

Components that have a "deactivation part" (for example leaving an ObjectActivator's trigger with Disable On Exit set to true) runs these events.

In a case where `On Dis Activate()` runs, it also reverts the `To Activate Objects`, `To Dis Activate Objects` states. Objects in `To Activate Objects` become **in**active, and objects in `To Dis Activate Objects` become **active**.

Notably used in:
* Component Events
- [Object Activator](/components/object-activator)
- Variable Watchers

> [!TIP]
> Tip! Lists and Unity Events allow you to Drag and Drop Objects!

![Drag and Drop](assets/ultrakill-event-drag-drop.gif)


---
*Taken from the [Tundra Docs](https://docs.tundra.pitr.dev/components/ultrakill-event/)*
