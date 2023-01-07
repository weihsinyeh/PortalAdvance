# Portals

Little test of portals in Unity.
Note: in the two worlds scene, you'll need to have Blender installed to view some of the models.

[Watch video](https://www.youtube.com/watch?v=cWpFZbjtSQg)

![Portals](https://raw.githubusercontent.com/SebLague/Images/master/Portals.png)

```
Matrix4x4 m = red.localToworldMatrix & blue.worldToLocalMatrix * playerCam.localToworldMatrix;
portalCam.SetPositionAndRotate (m.GetColumn(3), m.rotation);
```
