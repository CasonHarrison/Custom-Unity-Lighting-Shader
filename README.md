# Custom-Unity-Lighting-Shader
This is my custom unity standard lighting shader project. From start to finish I create the unity standard lighting shaders from scratch following catlikecoding's tutorials. There are a total of 10 scenes, each of which showcases a different feature implementation which I will briefly describe. 

## Scenes and Features
### Part 1 Scene
This scene showcases my transformation matrices work described more thoroughly in my procedurally generated content repo which you can check out [here](https://github.com/CasonHarrison/Procedural-Content-Generation-Projects).

### Complex material scene
This scene showcases my handling of creating complex materials. Showcases implementation of texture mapping, texture splatting, occusion maps, normal maps, emission maps, secondary maps, tiling and offset, and more. Importantly my material uses a metallic workflow as opposed to a specular one.

### Shadows Scene
This scene showcases the shadow-handling features of my shader. Creates shadow maps for point, directional, and spotlights and works for both forward and deferred shading.

### Multiple lights scene
This scene showcases the ability to handle multiple lights in both forward and deferred shading.

### Reflection scene
This scene showcases the ability to handle reflections using reflection probes, perform box projection cube map sampling, and blend between reflection probes, and more.

### Fog scene
This scene showcases fog implementation which again works for both forward and deferred fog.

### Deferred Lights and Deferred Rendering Scene
These two scenes showcase the ability to handle deferred rendering pipelines with multiple light types. Switch to the forward path in this scene to compare the batch number.

### LIghtmapping scene
This scene showcases the handling of generating light maps for static objects, combining dynamic and static lighting to create mixed lighting, realtime Global Illumination, utilizes light probe proxy volumes, utilize LOD groups in combination with GI, and more.

### GPU instancing scene.
This scene showcases the implementation of GPU instancing and material property blocks to reduce draw calls.
