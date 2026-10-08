# Data Class Creature Collection

## Basic Premise

Create a Python program that uses a **data class** to store information about creatures in a video game.

Every creature should follow the same structure, but each creature object will store its own values. The goal is to practice creating a data class, defining fields with type annotations, creating multiple instances, accessing fields with dot notation, and changing fields after an object has been created.

## Basic File Structure

```text
basic/
└── main.py
```

## Basic Requirements

* [ ] Import `dataclass` and create a data class named `Creature` using the `@dataclass` decorator.
* [ ] Give `Creature` the fields `name: str`, `species: str`, `level: int`, and `health: float`.
* [ ] Create at least **3 different `Creature` objects**, giving each one different values.
* [ ] Use **dot notation** to display the name, species, level, and health of each creature.
* [ ] Change the `level` and `health` of one creature using dot notation, then display its updated information.
* [ ] Make sure changing one creature does not change the values stored in the other creature objects.

> Fully completing the Basic Requirements earns **16/20 marks, or 80%**.

## Basic Assessment — 16 Marks

| Assessment Item | Criteria | Marks |
|---|---|---:|
| Data Class Definition | Correctly imports `dataclass`, uses `@dataclass`, and creates the `Creature` class. | 3 |
| Fields and Types | Defines all four required fields with the appropriate type annotations. | 3 |
| Creature Instances | Creates at least three separate `Creature` objects containing different data. | 3 |
| Accessing Fields | Uses dot notation to access and display the fields of the created creatures. | 3 |
| Changing Fields | Correctly changes the level and health of one creature using dot notation. | 3 |
| Independent Objects | Demonstrates that changing one creature does not change the other creature objects. | 1 |
|  | **Total** | **16** |

## Advanced Premise

Extend the Basic program so that the user can create their own creature.

Keep the `Creature` data class and the creatures you created for the Basic activity. After displaying those creatures, ask the user for the information needed to create one additional `Creature` object.

The new creature should follow exactly the same structure as every other creature.

## Advanced File Structure

```text
advanced/
└── main.py
```

You can begin by copying your completed Basic `main.py` into the Advanced folder.

## Advanced Requirements

* [ ] Keep the `Creature` data class and all functionality from the Basic activity.
* [ ] Use `input()` to ask the user for a creature's name, species, level, and health.
* [ ] Use the entered values to create a new `Creature` object and display its fields using dot notation.
* [ ] Validate the level so that it must be a valid whole number and validate health so that it must be a valid number.
* [ ] Use error handling so incorrect numeric input does not crash the program.
* [ ] If invalid information is entered, explain the problem and allow the user to try again.

## Advanced Assessment — 4 Marks

| Assessment Item | Criteria | Marks |
|---|---|---:|
| User-Created Instance | Collects user input and correctly creates a new `Creature` object. | 1 |
| Data Class Usage | Stores and displays the user-created creature using the same data class fields and dot notation as the Basic activity. | 1 |
| Input Validation | Ensures level and health contain appropriate numeric values. | 1 |
| Error Handling | Handles invalid numeric input without crashing and allows the user to correct it. | 1 |
|  | **Total** | **4** |
