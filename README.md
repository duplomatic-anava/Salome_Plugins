# Salome_Plugins

Collection of scripts for the Salome platform.

# Psicofil Plugins 

Original Sources: https://github.com/psicofil/Salome_Scripts

## Geom Plugins

### Filter Group

Creating Geometry groups in the GEOM module using features and properties of another group.
![ScreenShot](Previews/geom_filter_group.png)

### 3D Contact

Script to automatically detect contacts of two o more parts.
![ScreenShot](Previews/geom_contact_3d.png)

### Pass similar Group

After an operation in the geometry module the groups are lost and must be done again. 
With this script you can pass the groups (or the majority) after performing an operation to the part.
![ScreenShot](Previews/geom_pass_group.png)

### Internal Contour

Auto-selects the internal contour of a part. You have 2 options, select only the internal surface and set it as a group (for FEM), or create a new part with the control volume (for CFD).
![ScreenShot](Previews/geom_internal_contour.png)

## Mesh Plugins

### Belong to Geometry

Create mesh groups from geometry, even if the link does not exist.
![ScreenShot](Previews/geom_filter_group.png)

### Mesh whit Gmsh mesher

Macro/script to create mesh inside of Salome Platform with GMSH mesher.
![ScreenShot](Previews/smesh_gmsh_mesh.png)