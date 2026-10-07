# 2D to 3D visualization prompt

```
<task>

Build a single-file HTML application that converts the provided 2D architectural
floor plan into an editable 2D floor-plan editor and a synchronized 3D interior
visualization.

The uploaded image is the source of truth for the initial layout.

Do not merely create a visual approximation. Extract the available dimensions,
walls, openings, rooms and spatial relationships from the plan and represent them
as editable geometry.

</task>


<input_interpretation>

First analyze the provided 2D plan and identify:

- Overall dimensions and scale
- Exterior and interior walls
- Load-bearing vs non-load-bearing walls when distinguishable
- Rooms and room boundaries
- Doors, door swing direction and openings
- Windows and openings
- Columns, structural elements and other permanent elements
- Dimension annotations
- Floor levels or other relevant architectural information
- Furniture or fixtures already shown in the plan

Use millimeters as the canonical measurement unit.

Do not invent dimensions that are explicitly available in the image.

If information is ambiguous or missing, preserve the visible geometry and use
reasonable assumptions only where necessary. Clearly mark assumed dimensions or
properties in the UI/data model.

Maintain the original proportions and spatial relationships of the source plan.
</input_interpretation>


<2d_editor>

Create an interactive 2D floor-plan editor.

Recreate:

- Exterior walls
- Interior walls
- Load-bearing walls
- Non-load-bearing walls
- Doors and door swings
- Windows
- Rooms
- Columns/permanent structural elements
- Dimensions
- Furniture and fixtures

Use different visual styles for load-bearing and regular walls.

Display dimension labels around relevant walls and room boundaries.

Automatically calculate and display:

- Room dimensions
- Room area in m²
- Total usable floor area

Provide:

- Zoom and pan
- Grid
- Snap-to-grid
- Snap-to-wall
- Object selection
- Drag and drop
- Rotation
- Resize
- Measurement tool

Maintain accurate geometry when objects are moved or resized.
</2d_editor>


<furniture>

Provide a reusable furniture library containing common objects such as:

- Sofa
- Bed
- Table
- Chair
- Dining table
- Wardrobe
- Kitchen counter
- Refrigerator
- TV
- Desk
- Cabinet
- Toilet
- Wash basin
- Bathtub/shower
- Other common interior objects

Furniture should use realistic real-world dimensions.

Each object must support:

- Dragging
- Rotation
- Resizing
- Duplication
- Deletion
- Positioning against walls
- Automatic snapping when near walls or other appropriate surfaces

When exact dimensions are unavailable, use sensible standard dimensions and
treat them as editable assumptions.


<editing>

Support:

- Add/remove furniture
- Modify non-load-bearing walls
- Move doors/windows where structurally valid
- Change room boundaries
- Replace floor materials
- Change wall/floor finishes
- Undo/redo
- Reset to source layout
- Save/load project state using localStorage
- Export the 2D design as an image

Do not allow destructive modification of load-bearing or structural elements
without an explicit confirmation/warning.


<shared_model>

Use one canonical scene/data model as the source of truth for both 2D and 3D.

Represent important objects with properties such as:

- id
- type
- position
- dimensions
- rotation
- material
- structural type
- room association
- visibility

The 2D and 3D views must never maintain independent versions of the design.

Any change made in 2D must immediately update 3D, and any supported change made
in 3D must update the underlying model and 2D representation.


<3d_visualization>

Use Three.js to generate a real-time 3D representation of the same floor plan.

Generate actual 3D geometry for:

- Walls
- Floors
- Doors
- Windows
- Rooms
- Columns
- Furniture
- Fixtures

Use the dimensions from the 2D model to determine the corresponding 3D
dimensions.

Use sensible default architectural values only when the source plan does not
provide required information, such as wall height.

Provide:

- Bird's-eye/top view
- Perspective view
- First-person walkthrough
- Orbit controls
- Zoom
- Pan
- Object selection
- Basic lighting and shadows
- Realistic materials
- Floor and wall material selection

Doors and windows should appear as actual openings/architectural elements in
the 3D scene rather than flat textures wherever practical.


<view_switching>

Provide a clear 2D / 3D switch.

Switching views must:

- Preserve the current design state
- Synchronize all geometry and properties
- Maintain selected objects where possible
- Use a smooth transition
- Never duplicate or reset scene data

The user should feel that 2D and 3D are two views of the same design,
not two separate applications.


<measurements>

Provide a measurement tool that allows the user to select two points or objects
and display the real-world distance in mm/cm/m.

All calculations must use the canonical millimeter coordinate system.

Conversions:

1000 mm = 1 m

Room area must be calculated from actual editable geometry rather than
hard-coded values.


<materials>

Provide a small material library for:

- Wood
- Marble
- Tile
- Concrete
- Carpet
- Vinyl
- Ceramic
- Painted wall
- Glass
- Basic furniture materials

Allow floor material replacement from the UI and reflect the change in both
2D and 3D where appropriate.


<rendering_and_performance>

Keep the application lightweight and responsive.

Use Three.js efficiently and avoid unnecessary geometry or rendering work.

The application must work as a standalone HTML file.

Use CDN-hosted libraries only when necessary.

Do not introduce a build system unless absolutely required.

The final output should be directly runnable by opening the HTML file in a
modern browser.


<ui>

Create a clean architectural/design-tool interface.

Suggested layout:

- Left: tools and furniture/material library
- Center: active 2D/3D workspace
- Right: selected object properties and dimensions
- Top: project controls, undo/redo, save, export and 2D/3D switch

Keep the UI professional and unobtrusive so the floor plan remains the focus.

Show dimensions and properties clearly without cluttering the workspace.


<accuracy_rules>

The uploaded plan is the primary reference.

Follow these rules:

1. Prefer explicit dimensions over visual estimation.
2. Preserve the relative geometry of the original plan.
3. Never silently invent important structural dimensions.
4. Clearly distinguish inferred values from source values.
5. Do not move structural elements merely to make the design visually cleaner.
6. Maintain door/window locations and room relationships.
7. Keep 2D and 3D geometry mathematically consistent.
8. When the source image contains insufficient information for exact 3D
   reconstruction, make the minimum reasonable assumption and expose it as
   an editable property.


<deliverables>

Produce:

1. A single self-contained HTML file.
2. Functional 2D floor-plan editor.
3. Functional Three.js 3D visualization.
4. Shared synchronized scene/data model.
5. Furniture and material library.
6. Measurement and editing tools.
7. Undo/redo.
8. localStorage persistence.
9. Image export.
10. 2D/3D switching with real-time synchronization.

Do not provide only a mockup, static visualization or conceptual implementation.

Implement the core functionality so the resulting HTML can actually be opened
and used as an interactive floor-plan and 3D interior design tool.

</deliverables>


<validation>

Before finishing, verify:

- The initial 2D layout corresponds to the source plan.
- Dimensions use millimeters consistently.
- Room areas are calculated correctly.
- Doors and windows are positioned correctly.
- Load-bearing and regular walls are distinguishable.
- Furniture dimensions and transformations work.
- Moving an object in 2D updates 3D.
- Changing supported properties in 3D updates the shared model and 2D.
- Undo/redo works.
- localStorage save/load works.
- Floor/material changes propagate correctly.
- 2D/3D switching does not reset the scene.
- The application works when opened as a standalone HTML file.

If the source image contains information that cannot be reliably interpreted,
do not fabricate precision. Preserve the visible structure and expose the
uncertainty as an editable assumption.

</validation>

</prompt>
```
