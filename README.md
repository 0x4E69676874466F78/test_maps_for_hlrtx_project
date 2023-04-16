# Test maps for HL: RTX project

The original development topic [here](https://github.com/w23/xash3d-fwgs/issues/33).

## Note
In case you want test_light2, test_light3 maps to be displayed correctly, you need to uncomment `| gl_RayFlagsCullFrontFacingTrianglesEXT` in [`ray_primary.comp`](https://github.com/w23/xash3d-fwgs/blob/cfddb75bc58974f15b3aceb03170df187cac7b2f/ref/vk/shaders/ray_primary.comp#L71) but this will create [problems with shadows](https://github.com/w23/xash3d-fwgs/issues/507) on other maps like cs_cbble, so delete comment only for the duration of the test test_light2, test_light3 maps.

