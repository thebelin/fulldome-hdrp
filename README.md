# fulldome-hdrp
Fulldome Unity Camera HDRP SRP 180, 220, and EAC
Built for Dome Lab and free use in fulldome interactive software development

# Instructions
Import this Unity Package in your project
Add a layer called output at layer 30 to your project
Go to your Player Build Settings > Other Settings and set the Rendering Color Space to Linear
Project Settings > Graphics And set the Scriptable Render Pipeline to the EACHighDefinitionRenderPipelineAsset provided in the package
Add the Unity HDRP to your project with the Unity Project Manager
There are demo scenes showing the use of each of the cameras with some basic lighting and reflection effects in HDRP_360_Camera_Dome_Lab/Scenes

# Additional Software
The Klak NDI package from Keijiro will let you output to Digistar 6, Resolume, or any other NDI enabled display system. This camera has been tested to work with that and other Klak systems.
