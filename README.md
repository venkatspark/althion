# Althion Internship Files
Project files for internship at Althion, a med-tech company specialised in designing RO water and dialysis systems.

> **Internal use only — Althion.** Not for public distribution.
> Access to files will be provided upon request.

## Component Designs
The designs for the following components are available
1. Contractor Box
2. Control Panel
3. Display Panel
4. Structural Frame (Designs for the above components are included in the RO Frame CAD File)
6. Prototype of Tablet Dispenser for Urea Clearence Monitor
7. Prototype for Conductivity Sensor Housing
8. Venturi for RO water systems

## File Types
|Extension|Description|
|---| ---|
|`.f3d` | A single Fusion 360 design file exported/archived from the cloud. Contains the full design + timeline history.|
|`.f3z` | A Fusion 360 archive file — a zipped package that can include the design plus linked/referenced components. Used for sharing complete assemblies with all dependencies.|
|`.step` | Neutral CAD exchange format — geometry only (no timeline/history), openable in almost any CAD software|
|`.stl` | Mesh format for 3D printing or quick visualization — no editable features|

> **Note:** Only select designs are provided in `.stl` format — **Tablet Dispenser**, **Conductivity Sensor** and **Venturi**. These were exported for 3D printing/visualization purposes; the rest are available as `.f3d`/`.f3z`/`.step` only.

## How to Open Files
### `.f3d`/`.f3z` (native Fusion 360 files)
1. Download the file from this repo.
2. Open Fusion 360 → File → Open (or Upload if using the cloud-based Data Panel).
3. Select the downloaded file — Fusion imports it into your local hub/project with full editable timeline/history.
4. For `.f3z` archives, Fusion automatically unpacks all linked components into your working project.

### `.step` (neutral CAD exchange format)
1. Opens in almost any CAD software — Fusion 360, SolidWorks, FreeCAD, Onshape, etc.
2. In Fusion 360: File → Open → select the `.step` file (or drag-and-drop into the canvas). Imports as geometry only — no feature timeline, just the solid body.
3. In case you don't have a CAD software, free options like FreeCAD or an online viewer (e.g., Autodesk's free online viewer) can open it without installing a full suite

### `.stl` (mesh format)
1. No editable features — just a triangulated surface mesh, so any 3D viewer or slicer works.
2. Quick view: Windows 3D Viewer (built into Windows) or Mac's Preview/Quick Look — just drag-and-drop.
3. For 3D printing: open directly in your slicer (Cura, PrusaSlicer, Bambu Studio, etc.).
4. In Fusion 360: File → Insert → Insert Mesh — stays a mesh unless you use Fusion's mesh-to-BRep conversion tools.
