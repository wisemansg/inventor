# 🚀 SIEMENS NX

# Dual-Radius Pipe Support Clamp — Siemens NX CAD Model

## 📖 Overview
This project models a pipe support clamp with integrated base plate, fully created in Siemens NX. The component demonstrates key NX workflows including sketch-based extrusion, revolve for cylindrical features, swept cut for slot creation, edge blending (fillets), and precise dimension-driven modeling from an engineering drawing.

## 🎯 Objective
Accurately recreate the pipe clamp/support component from the provided technical drawing while ensuring clean, manufacture-ready geometry suitable for machining or casting. This type of part is commonly used to secure pipes, tubes or hoses in industrial, automotive, marine, and machinery applications.

## ⚙️ Specifications & Commands

| **Design Specifications**          | **Siemens NX Commands / Features Demonstrated** |
|------------------------------------|-------------------------------------------------|
| Total length: 118 mm               | Sketch → Extrude                                |
| Base width: 48 mm                  | Revolve                                         |
| Clamp inner diameters: Ø20 mm & Ø12 mm | Swept Cut (for elongated slot)              |
| Base slot: 44 × 16 mm rounded rectangle | Pattern (rectangular if needed)             |
| Height (clamp top): 40 mm          | Edge Blend (fillet R2)                          |
| Material thickness (main body): 16 mm | Datum features / Constraints                 |
| Fillet radius: R2 mm               | Synchronous / Ordered modeling                  |
| Units: Millimeters (mm)            | 2D Sketching with dimensions & relations        |

## ✨ Design Features
- Dual semi-circular clamp sections for different pipe diameters  
- Elongated mounting slot in base for positional adjustment  
- Reinforced transition geometry between clamp and base  
- Uniform wall thickness suitable for casting or machining  
- Rounded edges (R2) for safety and improved manufacturability  

## 📐 Technical Drawing Source
Model was built directly from the following 2D information visible in the isometric view:
- All principal linear dimensions  
- Cylinder diameters and heights  
- Slot length, width and fillet radii  
- Centerline references  
- Fillet callouts (R2)  

## 📸 Models / Screenshots

![Isometric view of completed part](NX_Render_Isometric.png)  
![Side orthographic view with key dimensions](NX_Side_View.png)  
![Top view showing slot and clamp layout](NX_Top_View.png)  
![Detail of clamp radii and fillet application](NX_Detail_R2.png)

*(Replace placeholder image names with your actual screenshot/export files)*

## 📥 CAD Downloads

- Siemens NX Part file (`.prt`)  
  `Pipe_Support_Clamp.prt`  
- Neutral formats  
  `Pipe_Support_Clamp.step`  
  `Pipe_Support_Clamp.parasolid.x_t`  
  `Pipe_Support_Clamp.stl` (for 3D printing / visualization)  
- Drawing export (if created)  
  `Pipe_Support_Clamp.dwg` / `Pipe_Support_Clamp.pdf`

Download all files here:  
[Download Pipe Support Clamp archive](./Pipe_Support_Clamp_NX.zip)

## 🏭🔩 Manufacturing Considerations
Recommended production methods:

- CNC machining from aluminum or steel block (most common)  
- Casting (sand or investment) + light machining of mating surfaces  
- Plasma / laser cutting of base plate + welded clamp sections (fabrication alternative)  

Design supports:
- Standard M10–M12 bolts through elongated slot  
- Easy deburring thanks to R2 external fillets  
- Good fixturing surfaces for machining  

## 🌐 Applications
Typical real-world use cases:

- Industrial pipe and tube routing systems  
- Hydraulic & pneumatic line clamping  
- Automotive chassis / engine bay supports  
- Marine & offshore equipment  
- HVAC installations  
- Machinery frames & conveyor systems  

## 💭 Reflection
This Siemens NX project helped demonstrate:

- Reading and interpreting complex isometric drawings with many dimensions  
- Effective use of revolve and sweep features for curved geometry  
- Maintaining design intent through fully dimensioned sketches  
- Application of edge blending for realistic engineering parts  
- Clean model structure suitable for downstream manufacturing or assembly use  

Possible future enhancements:

- Add threaded holes or clearance holes for specific bolt sizes  
- Apply GD&T (datums, position, profile tolerances)  
- Create proper 2D drawing sheet inside NX with views & annotations  
- Add material and mass properties  
- Perform basic FEA (stress on clamp under load)  
- Create a small assembly with sample pipe + bolts  

Feedback and suggestions welcome! 💬
