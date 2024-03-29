# Presentation

Trashpanda Likes Flowers is a 3D world/model built with procedural generation.

# Development

This model was made with [Unity](https://unity.com/fr) and [Shader Graph](https://unity.com/fr/features/shader-graph). The following videos were used as references :
[TPLF](https://www.youtube.com/playlist?list=PL4wvE9SgBKlfxsV1upO26FrRNoomVuikC).
It was my first time manipulating meshs, procedural generation and shaders.


# Demo

### Terrain

https://user-images.githubusercontent.com/112869026/208720348-400e7628-e449-4740-9cae-b4bf669162ec.mp4

### Water

https://user-images.githubusercontent.com/112869026/208720370-65e088af-8a52-4caa-b5d2-27a2f5a12c3c.mp4

### Skybox

https://user-images.githubusercontent.com/112869026/208720393-ca75d5f7-af6c-4e68-aa9a-6c3fb92b1011.mp4

# TDL

- [x] TERRAIN
- - [x] Preview mesh generation
- - [x] Procedural endless terrain generation
- - [x] LODS
- - [x] Flatshading
- - [x] Mesh coloration

- [x] IMPLEMENTATION AND DATA
- - [x] Optimization
- - [x] Data storage
- - [x] Refactoring
- - [x] Threading
- - - [x] Fix threads getting the wrong minHeight and maxHeight values due to multiple requests at the same time

- [x] SKYBOX
- - [x] Day shader
- - [x] Night shader
- - [x] Sun

- [x] WATER
- - [x] Planes generation
- - [x] Shader
- - [x] Foam
- - [x] Movement
- - [x] Optimization

- [x] GRASS
- - [x] Movement
- - [x] Shader

- [x] OBJECTS
- - [x] Random spawn on each chunk
