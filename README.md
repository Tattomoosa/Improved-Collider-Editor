# Improved-Collider-Editor

An asset package for Unity that allows for better manipulation of colliders on GameObjects.

## Getting Started

This repository only stores the documentation for the Improved Collider Editor.
The asset itself must be [purchased on the Unity Asset Store here](TODO ADD LINK).

Then import it into your project and all of your collider's editors will be updated automatically.

## Using the Asset

Add a BoxCollider, SphereCollider, or CapsuleCollider to a GameObject.
Select that game object, then press the 'Edit Collider' button in the Inspector for the collider you wish to edit.

Your primary tool will disappear and several new control handles will appear.
Click on a handle to activate it, or click and drag the active handle to manipulate the property that it controls.

## Handles

### Collider Center Handle

While inactive, the collider's center is shown as a small cyan cube handle.
While active, this is replaced by a cyan-colored position manipulation handle with 3 arrow handles.
These arrows point up, right, and forward, either relative to the world transform or to the object's local transform,
depending on your selected pivot rotation.
Drag these arrows to manipulate the collider's center in 3D space.

### Length & Side Manipulation Handles

These handles control the height of the CapsuleCollider and the individual faces or axes of the BoxCollider.
While inactive, they appear as white buttons surrounded by grey squares.
While active, these are replaced by an arrow handle and a small cube handle.
Clicking and dragging the arrow handle manipulates that side of the collider (recentering the center point
so that the other side remains in place).
Clicking and dragging the cube handle manipulates the scale of the collider upon that axis, manipulating
both sides of the collider at the same time.

## Changing the Location of This Asset's Files

If you wish to change the folder structure, note that all of these scripts must be inside a folder named 'Editor' inside
the 'Assets' folder or they will not work correctly.

## 2D Colliders?

This asset currently only supports 3D colliders.

## Support

Email support@mattotousa.com with any questions. Bug reports or feature requests can go right here on this GitHub repository.
