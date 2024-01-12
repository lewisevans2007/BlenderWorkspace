# Blender workspace

Blender workspace is a repository that contains default startup files that have been customized to my liking

## Installation

Download the repository or download from latest release and open the file `default.blend` in Blender. Then go to `File > Defaults > Save Startup File` to save the file as the default startup file.

## Features

There are many more tabs and panels in the default startup file than the default Blender startup file. 

### Layouts

There are two layout tabs: `Layout` and `Layout 2` Each layout tab has a different layout of panels.

#### Layout

This tab has a similar design to the default Blender layout tab.

#### Layout 2

This tab has three 3D viewports, a timeline, a properties panel, a outliner panel. One of the 3D viewports is a quad view, one is a camera view and one is a default 3D viewport.

### Geometry nodes

The geometry nodes tab contains two geometry nodes editors and one 3D viewport. There is also a properties panel and a outliner panel.

### UV Editing

This tab is very similar to the default Blender UV Editing tab. 

### Shading

This tab is also very similar to the default Blender Shading tab but has two panels to the left of the 3D viewport containing a file explorer panel and a shader editor panel for world nodes.

### Shading

This tab has two shading tabs one for world and one for object, a 3D viewport, a properties panel and a outliner panel.

### Animation

This tab contains two 3D viewports (main and camera), a dope sheet, a graph editor, a properties panel and a outliner panel.

### Camera

This tab contains a 3D viewport (camera), a properties panel, a outliner panel and a timeline.

### Camera compositing

This tab contains four 3D viewports (Camera with random colors, Camera, main, quad view). There is also a properties panel, a outliner panel and timeline.

### Rendering

This tab contains a image editor, a properties panel, 3d view panel (camera), and a timeline.

### Compositing

This tab contains two image editors, a properties panel, a compositor panel, a outliner panel and a dope sheet.

### Assets and files

This tab contains a asset browser panel, two file explorer panels, a outliner panel and a properties panel. There is also a 3D viewport.

Use this tab to import assets and files.

### File management

This tab contains a 3D viewport, a file explorer panel and four outline panels.

Each outliner panel has a different display mode. Use this to delete data blocks in the blend file.

## Objects

There are six objects and three collections in the default startup file.

The objects and collections are:
- Objects
    - Subject (Empty)
        - Cube (Child of Subject)
    - Floor
- Lights
    - Area
    - Light target (empty)
- Cameras
    - Camera
    - Camera target (empty)

The Light target and Camera target are both empty objects that are used to control the point of the light and camera.

## Configuration

The file is configured to use cycles as the render engine and to use GPU compute for rendering. The world is black and the camera is set to perspective.

## Contributing

If you would like to add a feature to the default startup file, please open a pull request and state what features you added or changed.
