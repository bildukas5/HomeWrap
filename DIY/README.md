# How the Designs Were Made

This document explains the process used to create the protective film cutout designs.
It's a low-tech but effective approach that anyone can replicate without special equipment.

---

## Overview

The core idea is simple: use masking tape applied directly to the frame to capture the exact shape of each area, then transfer those shapes into CAD.

---

## Step 1 — Apply Masking Tape to the Frame

Apply masking tape directly onto the bicycle frame, covering the area you want to protect.
Layer tape on top of tape to build up a shape that holds together when removed.

**Tape choice matters.** A professional-grade masking tape makes this significantly easier:
- It has enough **stretch** to conform to curved and compound surfaces without wrinkling
- It leaves **no adhesive residue** on the frame
- It can be **repositioned and reapplied** multiple times while you refine the shape

In this project, **TESA Pro** masking tape was used and worked very well. Any high-quality automotive or professional masking tape with similar properties should work.

> ⚠️ Avoid cheap masking tape — it tears easily, leaves residue, and doesn't stretch around curves.

![frame1](DIY/frame1.jpg)
---

## Step 2 — Trim the Shape

While the tape is still on the frame, carefully trim it to the exact edge of the area you want to cover. Precision scissors work well for this.

Take your time — the accuracy of this step directly affects how well the final film fits.

---

## Step 3 — Remove and Flatten

Carefully peel the tape shape off the frame and lay it flat on a cutting board or other flat surface.
Smooth it out as much as possible — the tape's flexibility means it will lie reasonably flat even for curved pieces.

---

## Step 4 — Measure

With the tape shape flat on the cutting board, take manual measurements of all key dimensions:
- Overall length and width
- Curves and radii where possible
- Any cutouts or notches

---

## Step 5 — Recreate in FreeCAD

Using the measurements taken in the previous step, recreate each shape as a 2D sketch in [FreeCAD](https://www.freecad.org/).

- Use the **Sketcher workbench** to draw and constrain the shapes
- Add dimensions as constraints to match your measurements
- Export finished sketches as **DXF or SVG** for cutting

FreeCAD is free and open source, which fits the spirit of this project.

---

## Alternative: Direct Transfer for Small or Complex Areas

Some areas of the frame are small, heavily curved, or have such an irregular shape that accurately measuring and recreating them in CAD is impractical. For these, the masking tape shape was used as a direct cutting template — skipping the CAD step entirely.

The process is straightforward:
1. Remove the tape shape from the frame as usual and flatten it on the cutting board
2. Place it directly onto the protective film
3. Trace around it with a marker or cut directly along its edge
4. Apply the resulting piece to the frame

This is less precise than a CAD-derived cut but works well for small patches where slight imperfections are less noticeable. It's also much faster for one-off pieces you don't need to reproduce exactly.

---

## Tips & Lessons Learned

- **Label each tape piece** before removing it from the frame so you don't mix them up
- **Photograph the tape on the frame** before removing — useful reference if a measurement is unclear later
- **Test with paper before film** — print or cut a paper version first to verify fit before using real PPF or vinyl

---

## Tools Used

| Tool | Purpose |
|---|---|
| TESA Pro masking tape | Capturing frame shapes |
| Precision scissors | Trimming tape on the frame |
| Cutting board | Flat surface for measuring |
| Ruler + calipers | Taking measurements |
| [FreeCAD](https://www.freecad.org/) | Creating CAD designs from measurements |
