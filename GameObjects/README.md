# **Game Objects**

A core type that the engine uses to represent things in the game world.

## Breakdown

|Feature|Summary|Unity|UE4|Godot|GMS2
|-------|-------|-----|---|-----|----
|Supported|Does the engine support this feature?|✔️|✔️|✔️|️✔️

## Additional Notes

### Unity

`GameObject`:
- 3D transform
- Array of **Components** called `MonoBehaviours`. May not have multiples of the same type.
- Array of unique **Tags**.

### Unreal Engine 4

`Actor`:
- Tree of **Components** called `ActorComponents`.
    - `SceneComponent`, a derived `ActorComponent`, has a 3D transform. If the root of an `Actor`, the entire tree of **Components** exist relative to that transform.

### Godot Engine

`Node`:
- Array of `Nodes` which serve either as **GameObjects** or **Components**.
    - `Node2D` and `Spatial`, derived `Nodes`, have 2D and 3D transforms for 2D and 3D worlds respectively.

### Game Maker Studio 2
