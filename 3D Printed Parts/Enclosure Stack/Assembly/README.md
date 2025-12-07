# 3D Printed Parts – Enclosure Stack / Assembly

**WARNING**: this is a first draft! Only print if you are curious and got filament to spare :D.  
This README provides an overview of the assembly steps for the “stack type” enclosure.


---

## ⚠️ Safety Disclaimer

**Important:** These 3D-printed parts are designed to house components connected to mains voltage (100–240V AC). Please observe the following safety precautions:

- Only place the assembled unit on a **stable, non-flammable surface**.  
- Never leave the unit **powered on and unattended**.  
- Keep out of reach of **children and pets**.  
- Ensure proper **ventilation** around the power supply to avoid overheating. (not bedded into artificial turf)  
- Handle electrical connections **carefully** and only if you are confident with mains electricity.  
- Avoid **cable damage**: do not pinch wires or run them over sharp edges.  
- Use proper **fuses or circuit protection** in the IEC connector.  
- Always verify **correct polarity and connections** before powering on.  
- **Material choice matters**: PLA is flammable; consider PETG or ABS for better heat resistance, ideally UL94 V-0 certified.  
- Ensure **print quality**: no gaps or thin walls that could expose live components.  
- Do not operate the unit in **wet or humid environments**.  
- Keep all small parts **secure and away from children or pets**.  
- Use **appropriate tools** for assembly and avoid sharp edges.  
- Clearly **mark modules and polarity** where relevant to prevent mistakes.
- Take care not to **drop screws or other components** into the power supply during assembly.
- Always install the **LinePower_Cover.stl** to minimize the risk of electric shock.

Failure to follow these precautions can result in **fire, electric shock, or personal injury**. Print and use these parts at your own risk.  

---

## 🧩 Bill Of Material
(to be added)

---

##  Camera Assembly

Tools:
- Cross-head screwdriver  
- 2.5 mm Allen key
- Sandpaper (optional) 

| Number | Part | Qty | Notes |
|--------|---------|---------|--------|
| 1 | IMX296-MPI_Eyeball_6mm | 1 | Remove support material |
| 2 | ISO 4762 M3x6 mm screw | 2 | 6–15 mm; cylindrical head |
| 3 | M2.3x6 mm self-tapping screw| 4 | 6–12 mm |  

1. Remove all support material. 
2. Smooth spherical surfaces if needed.
3. Chamfer/prime the two horizontal holes for **M3×6 mm** using a cross-head screwdriver.
4. Install both **M3×6 mm** screws with the Allen key; ensure straight alignment.
5. Slightly loosen the aperture and focus screws on the **camera**; align them with the slot. The ribbon cable connector must align with the opening.
7. Attach the camera to the **eyeball** using four **M2.3×6 mm self-tapping screws**.


---

##  Eyeball Assembly

Tools:
- 3 mm Allen key for ISO 7380-2 or 4 mm for ISO 4762
- Sandpaper (optional) 
- Superglue (optional) 

| Number | Part | Qty | Notes |
|--------|---------|---------|--------|
| 1 | Camera Assembly | 1 | - |
| 2 | EyeScreen | 1 | - |
| 3 | EyeScreen_Clamp | 1 | - |
| 4 | ISO 4032 M5 nut| 4 | - |
| 5 | ISO 7380-2 M5x20 mm screw| 4 | 20–25 mm; ISO 4762 optional |  

1. Remove support material.
2. Smooth spherical surfaces if needed. 
3. Insert **M5 nuts** into the **EyeScreen_Clamp** pockets (optional: secure with superglue).
4. Insert the **Camera Assembly** into the **EyeScreen**. 
5. Ensure correct orientation: notches must face upwards (toward the ribbon cable).
6. Install the **M5 screws** and tighten only lightly.

Note: ISO 7380-2 button-head screws look nicer and provide more surface contact; ISO 4762 offers better tool access.

---

##  LED Assembly
... coming soon

---

##  Camera Stack Module Assembly

Tools:
- 3 mm Allen key for ISO 7380-2 or 4 mm for ISO 4762

| Number | Part | Qty | Notes |
|--------|---------|---------|--------|
| 1 | Eyeball Assembly | 1 | - |
| 2 | Stack_Module | 1 | - |
| 3 | ISO 7380-2 M5x10 mm screw| 2 | 10–15 mm; ISO 4762 optional | 

 1. Remove support material.
 2. Pre-tap the lower **EyeScreen** holes with a screw.
 3. Mount the **Eyeball Assembly** to the **Stack_Module**. Recommended front-plane distance: 25 mm (same left/right).

---

##  LED Stack Module Assembly

Tools:
- 3 mm Allen key for ISO 7380-2 or 4 mm for ISO 4762

| Number | Part | Qty | Notes |
|--------|---------|---------|--------|
| 1 | LED Assembly | 1 | - |
| 2 | Stack_Module | 1 | - |
| 3 | ISO 7380-2 M5x10 mm screw| 2 | 10–15 mm; ISO 4762 optional | 

 1. Remove support material.
 2. Pre-tap the lower **EyeScreen** holes with a screw.
 3. Mount the **LED Assembly** to the **Stack_Module**. Recommended front-plane distance: xx mm (same left/right).

---

##  Stack Module to Stack Module Assembly

Tools:
- 3 mm or 4 mm Allen key (ball-end preferred)


| Number | Part | Qty | Notes |
|--------|---------|---------|--------|
| 1 | Camera Stack Module Assembly | 2 | - |
| 2 | LED Stack Module Assembly | 1 | - |
| 3 | PSU Stack Module Assembly | 1 | - |
| 4 | ISO 7380-2 M5x10-15 mm screw| 12 | 10–15 mm; ISO 4762 optional | 
| 5 | Spacer | 12 | not designed yet |

**2nd on 1st stack**
1. Pre-tap the upper **Stack_Module** holes.
2. Insert four **spacers** into the outer holes of the **PSU Stack Module** (for alignment).
3. Mount the **Camera Stack Module Assembly** with 4× M5×10 mm screws.
WARNING: Use 10 mm screws only to ensure clearance above the **PSU**.

**3rd on 2nd stack**
1. Pre-tap the upper **Stack_Module** holes.
2. Insert four **spacers** into the outer holes of the **Camera Stack Module** (for alignment).
3. Mount the **LED Stack Module Assembly** with 4× M5×15 mm screws.

**4th on 3rd stack**
1. Pre-tap the upper **Stack_Module** holes.
2. Insert four **spacers** into the outer holes of the **LED Stack Module** (for alignment).
3. Mount the **Camera Stack Module Assembly** with 4× M5×15 mm screws. 

---

##  Electronics
... coming soon

---

##  Cover

Tools:
- 3 mm Allen key for ISO 7380-2 or 4 mm for ISO 4762
- Saw for trimming M5 rod
- File for deburring

| Number | Part | Qty | Notes |
|--------|---------|---------|--------|
| 1 | Stack_Module_Cover | 1 | - |
| 2 | ISO 4032 M5 nut| 4 | - |
| 3 | M5x318 mm rod | 4 | trim to 318 mm |
| 4 | Spacer | 4 | not designed yet |
| 5 | M5 washer | 4 | - |
| 6 | ISO 7380-2 M5x15 mm screw| 4 | 10–15 mm; ISO 4762 optional | 

**Stack_Module_Cover on 4th stack**
1. Pre-tap the upper **Stack_Module** holes.
2. Insert four spacers into the **Camera Stack Module Assembly** (for alignment).
3. Mount the **Stack_Module_Cover** with **4× M5×15 mm screws**.
4. Cut **rods** to 318 mm and deburr.
5. Thread nuts onto the **rods** and insert them from below into the **PSU Stack Module** (nuts must seat in the hex pockets).
6. Ensure the rods are flush with the bottom of the **PSU Stack Module**.
7. Install washers and nuts on the top end at the Stack_Module_Cover.

---

##  Feet

Tools:
- Superglue  

| Number | Part | Qty | Notes |
|--------|---------|---------|--------|
| 1 | Foot | 4 | - |
| 2 | ISO 4032 M5 nut| 4 | - |

1. Glue the nuts into the **feet**.
2. Thread the **feet** onto the M5 rods of the full assembly. Turn them all the way up and adjust as needed.
