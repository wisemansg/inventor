# 🚀 AUTODESK INVENTOR

# Flanged Conical Support Pedestal

## 📖 Overview
This project models a flanged conical support pedestal with square base and central cylindrical protrusion, fully created in Autodesk Inventor. The component demonstrates key Inventor workflows: sketch-based extrusion, revolve for cylindrical and conical features, patterned holes, large fillet transitions, and precise dimension-driven modeling from an engineering drawing.

## 🎯 Objective
Accurately recreate the support pedestal from the provided technical drawing while ensuring clean, parametric, manufacture-ready geometry suitable for machining, casting or 3D printing. Commonly used as an elevated base for pipes, shafts, rods or machinery components.

## ⚙️ Specifications & Commands

| **Design Specifications**          | **Autodesk Inventor Commands / Features Demonstrated** |
|------------------------------------|--------------------------------------------------------|
| Base: 80 × 80 mm                   | Sketch → Extrude                                       |
| Mounting holes: 4 × Ø12 mm         | Hole → Circular Pattern                                |
| Central boss Ø: 34 mm outer / 18 mm inner | Revolve                                         |
| Overall height: 40 mm              | Extrude / Revolve                                      |
| Base thickness: 10 mm              | Extrude                                                |
| Taper height: 37 mm                | Fillet (R20 mm)                                        |
| Large fillet: R20 mm               | Fillet tool                                            |
| Units: Millimeters (mm)            | Parametric dimensions & constraints                    |

## ✨ Design Features
- Square base with four corner mounting holes  
- Conical tapered transition body  
- Central cylindrical boss with through bore  
- Large R20 mm rounded base transitions  
- Uniform geometry suitable for casting/machining  

## 📐 Technical Drawing Source
Model built directly from the provided 2D drawing:  
- Top view: 80 mm square, Ø34/Ø18 mm central features, four Ø12 mm holes  
- Front view: 40 mm height, 10 mm base, 37 mm taper, 5 mm top step  
- All dimensions and fillet callouts in mm  

## 📸 Models / Screenshots

![Drawing View](FS0.jpeg)  
![3D Model View](FS1.png)  
![3D Model View](FS2.png)  
![3D Model View](FS3.png)

## 📥 CAD Downloads

[Download archive](./Flanged%20Support.zip)  


## 🏭Manufacturing Considerations

Recommended methods:
- CNC machining (aluminum/steel)  
- Sand/investment casting + finish machining  
- 3D printing (prototypes)  

Supports:  
- M10–M12 bolts through Ø12 mm holes  
- Large R20 fillets for stress relief & deburring  

## 🌐 Applications
- Pipe/tube support stands  
- Shaft/rod pedestals  
- Machinery alignment bases  
- Equipment mounting supports  

## 💭 Reflection
This Inventor project demonstrated:

- Interpreting multiview drawings  
- Revolve & extrusion for cylindrical/conical geometry  
- Fully constrained parametric sketches  
- Large fillets for production-ready parts  
- Clean model for drawings/assemblies/CAM  

Possible enhancements:  
- Add bolt features  
- Create annotated drawing sheet  
- Assign material & mass  
- Basic stress simulation  
- Small assembly with sample component  

Feedback welcome! 💬



# Sheet Metal Concentric Ventilation Cover

## 📖 Overview
This project models a square sheet metal cover featuring a radial concentric ventilation / louver pattern and four folded side flanges. Built entirely in **Autodesk Inventor Sheet Metal**, it demonstrates core workflows: base face creation, multi-side flanging, circular patterning for cutouts, bend management, and clean folded/flat states, ideal for enclosure panels, fan guards, or breather covers.

## 🎯 Objective
Create a parametric, production-ready sheet metal part with precise bends and a visually appealing functional ventilation pattern, suitable for laser cutting + bending or CNC punching.

## ⚙️ Specifications & Commands

| **Design Specifications**              | **Autodesk Inventor Commands / Features Demonstrated** |
|----------------------------------------|--------------------------------------------------------|
| Square central panel                   | Sheet Metal Defaults → Face                            |
| Four equal side flanges                | Flange (applied to four edges)                         |
| Concentric circular ventilation slots  | 2D Sketch → Circular Pattern → Cut                     |
| Uniform bend radius & relief           | Automatic / rule-based bend allowance                  |
| Folded model with clean appearance     | Folded Model + Flat Pattern view                       |
| Units: Millimeters (mm)                | Parametric dimensions & constraints                    |

## ✨ Design Features
- Square base with radial/concentric slot pattern for airflow  
- Four symmetric mounting flanges (ready for hole addition)  
- Smooth, consistent bends suitable for press brake  
- Fully unfoldable flat pattern for DXF export / fabrication  
- Organized feature tree with multiple sketches for pattern control  

## 📐 Modeling Approach
1. Set up **Sheet Metal Defaults** (thickness, bend radius, etc.)  
2. Created base **Face** from square sketch  
3. Added **Flange** features on all four sides  
4. Sketched concentric circles/arcs on face (or in flat state)  
5. Applied **Circular Pattern** to create repeating slots  
6. Used **Cut** to remove material for ventilation  
7. Verified flat pattern and bend lines  

## 📸 Models / Screenshots

![Primary Top View](SM1.png)  
*Folded model – top view showing concentric ventilation pattern*

![Isometric Folded View](SM2.png)  
*Isometric view of the complete folded part with side flanges*

![Additional / Detail View](SM3.png)  
*Alternate angle or flat pattern preview (depending on SM3.png content)*

## 📥 CAD Download

[Download complete Inventor project (part file + sheets)](./Sheet%20Metal.zip)

## 🏭 Manufacturing Considerations

Recommended methods:
- Laser cut or turret punch flat pattern → CNC press brake bending  
- Material: steel (0.8–2 mm), stainless, or aluminium  
- Finish: powder coat, zinc plate, or passivation  

Mounting: flanges designed for screws/bolts (add holes in production variant)  
Ventilation: provides good airflow + finger/object protection  

## 🌐 Applications
- Fan / blower guards  
- Electrical cabinet vents  
- Equipment enclosure breathers  
- Audio speaker grilles  
- Protective panels for machinery  

## 💭 Reflection
This project highlighted:
- Clean **Face + Flange** workflow for boxed sheet metal parts  
- Effective use of **Circular Pattern** in sheet metal context  
- Managing folded vs. flat representations  
- Parametric control for easy design updates  
- Production-oriented modeling (bend-aware geometry)  

Possible enhancements:  
- Add mounting holes to flanges  
- Generate flat pattern drawing with bend notes  
- Assign material → calculate mass / cost estimate  
- Export flat DXF for direct fabrication  
- Add ribs or hems for added stiffness  

Feel free to use, modify or reference for similar sheet metal enclosure / guard designs!

