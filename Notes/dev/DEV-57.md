# DEV-57, Cycles vs Eevee
#### Tags: [cycles, eevee]

    Which one is better?

    Eevee is generally quick and you get a very good result quickly. Eevee uses screen space reflections. If its not on the screen, its not getting reflected. This is an issue if there is something that has shadows or so behind the camera.
    
    Cycles is a physically based renderer. It is accurate but takes longer. It is designed for GPUs but runs fine on CPUs. Cycles is great for reflections. It sends rays out from the camera back from the lightsource and works out lots of different bounces, somewhat simulating an eye in way

    If you are making assets to ultimately end up in a game engine, you may want to focus on Eevee. But there are some scenarios where it is needed for us to use cycles, especially when we solidify textures and materials
