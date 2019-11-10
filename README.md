# fulldome-hdrp
Fulldome Unity Camera HDRP SRP 180, 220, and EAC
Built for Dome Lab and free use in fulldome interactive software development

# Instructions
1. Import this Unity Package in your project
2. Add a layer called output at layer 30 to your project
3. Go to your Player Build Settings > Other Settings and set the Rendering Color Space to Linear
4. Project Settings > Graphics And set the Scriptable Render Pipeline to the EACHighDefinitionRenderPipelineAsset provided in the package
5. Add the Unity HDRP to your project with the Unity Project Manager
6. There are demo scenes showing the use of each of the cameras with some basic lighting and reflection effects in HDRP_360_Camera_Dome_Lab/Scenes

# Additional Software
The [Klak NDI](https://github.com/keijiro/KlakNDI) package from [Keijiro](https://github.com/keijiro/) will let you output to Digistar 6, Resolume, or any other NDI enabled display system. This camera has been tested to work with that and other Klak systems Keijiro has developed.
