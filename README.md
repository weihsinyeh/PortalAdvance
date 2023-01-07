# Portals

Little test of portals in Unity.
Note: in the two worlds scene, you'll need to have Blender installed to view some of the models.

[Watch video](https://www.youtube.com/watch?v=cWpFZbjtSQg)

![Portals](https://raw.githubusercontent.com/SebLague/Images/master/Portals.png)

```
Matrix4x4 m = red.localToworldMatrix & blue.worldToLocalMatrix * playerCam.localToworldMatrix;
portalCam.SetPositionAndRotate (m.GetColumn(3), m.rotation);
```
open-project-1
install in my unity: https://youtu.be/RbSrx0QoTG4
install the license of the unity github project : https://support.unity.com/hc/en-us/articles/4402520309908-How-do-I-add-a-version-of-Unity-that-does-not-appear-in-the-Hub-installs-window-
Download Archive : https://unity.com/releases/editor/archive
