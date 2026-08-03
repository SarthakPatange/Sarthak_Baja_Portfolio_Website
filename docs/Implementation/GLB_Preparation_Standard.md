# GLB Preparation Standard

Purpose

Interactive CAD models are the primary storytelling medium.

Raw CAD should never be uploaded directly.

---

# Source Software

SolidWorks

CATIA

Fusion360

Inventor

Creo

NX

---

# Export Pipeline

Native CAD

↓

STEP

↓

Blender

↓

Cleanup

↓

Material Assignment

↓

Polygon Reduction

↓

GLB

---

# Geometry

Remove hidden components.

Remove duplicate geometry.

Repair normals.

Merge identical materials.

Remove unnecessary sketches.

Delete construction geometry.

---

# Polygon Budget

Vehicle

< 1 million triangles

Subsystem

< 300k

Individual Component

< 100k

---

# Materials

Prefer PBR materials.

Avoid baked lighting.

Avoid unrealistic reflections.

Avoid gaming shaders.

Materials should approximate manufacturing.

---

# Coordinate System

Vehicle

Centered

Ground Plane

Z Up

Consistent orientation

---

# Naming

vehicle.glb

front-suspension.glb

rear-suspension.glb

steering.glb

powertrain.glb

Never

assembly2.glb

new.glb

test.glb

---

# Repository Rules

One subsystem per model.

Consistent scale.

Consistent origin.

Optimized geometry.
