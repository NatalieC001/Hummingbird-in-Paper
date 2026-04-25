# Hummingbird in Paper

[A diary. No downloads. Just the process.](https://nataliec001.github.io/Hummingbird-in-Paper/)

---

## What this is

I'm building a realistic hummingbird out of paper. This is where I keep everything – the wins, the failures, the detours, the tools I accidentally built along the way.

<img width="768" height="1024" alt="image" src="https://github.com/user-attachments/assets/486610e8-4770-4060-a81d-79c9c8921eb1" />

 below photo is not retouched in any way I'm quite pleased with the feathers so far 

<img width="620" height="826" alt="image" src="https://github.com/user-attachments/assets/37c4801e-bc5e-4e61-a2c6-2515ebecc72f" />

---

## The current shape of things

**📁 `blender/`**
The 3D model. Still tweaking the beak. Still fighting with wing topology.

**📁 `jointforge/`**
My Blender add-on for splitting large prints. Born out of frustration when I realized the armature needed to be bigger than my printer bed. Works now. More proud of this than I should be.

**📁 `paper_templates/`**
SVGs for cutting. Feather layers. Body segments. Some work. Some are in the trash where they belong.

**📁 `progress_photos/`**
Step by step. The good, the bad, the "why did I think this would work."

**📁 `notes/`**
Measurements. Material tests. Glue disasters. Little discoveries.

---

## Inspirations

- **Calvin Nicholls** – paper sculpture that looks alive. The standard.
- **Johan Scherft** – his bird models taught me what's possible with just paper and patience.
- **Patrick Cabral** – layered paper cutwork. Different style, same obsession.

---

## Recent discoveries

**2026-04-24**
Tried scoring the feather veins with a dull x-acto instead of a sharp one. Counterintuitive but works – gives a soft crease instead of a cut. Write that down.

**2026-04-20**
JointForge boolean failed on a curved split plane. Fixed by manually cleaning non-manifold edges on the source mesh. The mesh was dirty. My fault, not the plugin's.

**2026-04-15**
Discovered that Cricut's "cardstock" setting at double pressure cuts through 65lb paper perfectly but destroys 100lb. Three ruined feather sheets before I learned.

---

## Failures

- The first armature printed at 0.1mm layer height. Beautiful but brittle. Snapped at the neck joint during test assembly.
- Paper wings without internal support flap too much. Not in a good way.
- Tried to rush the tail feathers. Rushed things look rushed.

---

## Solutions that worked

- **Internal armature gets printed at 0.24mm.** Strength over detail when nobody sees it.
- **Paper wings now have a hidden wire spine.** Not traditional papercraft, but the bird needs to hold its pose.
- **JointForge's gap setting at 0.2mm** – tight enough that glue isn't required, loose enough that parts seat without force.

---

## Where it stands right now

Body: complete. Wings: third version, feels close. Tail: not started. Armature: printed and assembled with JointForge keys. Paper layer 1 of 4 is cut.

It looks like something. Not yet a hummingbird. Getting there.

---

## Why GitHub

Because paper notebooks get lost. Because the next time I build a paper bird (there will be a next time), I want to remember what I learned. Because someone else might find the trail useful – even if it's messy.

---

*One bird. Many steps. Still flying.*
