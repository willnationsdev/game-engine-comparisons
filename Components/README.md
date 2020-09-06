# **Components**

A fundamental building block for creating things.

The engine must support a mechanism for statically defining combinations of **Components** into new structures (must be able to "build" things) with the use of scripting.

## Breakdown

|Feature|Summary|Unity|UE4|Godot|GMS2
|-------|-------|-----|---|-----|----
|Supported|Does the engine support this feature?|✔️|✔️|✔️|
|Supports Data|Can it grant data to other things?|✔️|✔️|✔️|
|Supports Behavior|Can it grant behavior to other things?|✔️|✔️|✔️|
|Aggregation|Can it be independent of a **GameObject**?|||✔️
|System Tracked|Is there a system for tracking **Component** references by type?|✔️||✔️📓||
|GameObject Tracked|Is there a system for tracking which **GameObjects** have which **Components**?|✔️||✔️📓||
|Systems|Are there macro behaviors for querying and operating on combinations of **Components**?|✔️|️|️|️

## Additional Notes

### Unity

### Unreal Engine 4

### Godot Engine

Godot has two things that could be considered "Components": Nodes and Resources. 

System Tracked: While nodes are not globally tracked by type Resources
GameObject Tracked: 

### Game Maker Studio 2
