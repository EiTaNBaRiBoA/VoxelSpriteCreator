A simple image-to-voxel converter.

It takes a spritesheet, extracts the data and creates a 3D representation. Animation is also possible.

It's not optimized, so the draw calls count is roughly equal to amount of voxels (the bigger the sprite, the more). Maybe somebody smarter than me can fix it somehow.

I've included a simple demo scene. Because the sprite I used is not centered, the rotation will get weird if you change the X size of voxels.

Credits:
Warrior sprite by Clembod.

MIT license. Use it for whatever you want.