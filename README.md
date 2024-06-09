# cesium_issues


1] Terrain - Profile geodetic

https://bertt.github.io/cesium_issues/profile_geodetic

2] Terrain - Profile mercator

https://bertt.github.io/cesium_issues/profile_mercator

3] Dark 3D Tiles

issue: https://bertt.github.io/cesium_issues/dark

fix: https://bertt.github.io/cesium_issues/dark/fixed

4] Double sided

Double sided true: https://bertt.github.io/cesium_issues/doublesided/double_sided_true

Double sided false: https://bertt.github.io/cesium_issues/doublesided/double_sided_false

5] Compisite GPU instancing

Sample with I3dm: https://bertt.github.io/cesium_issues/composite_gpu_instances

5] I3dm versus GPU -  EXT_mesh_gpu_instancing (red boxes), i3dm (trees)

https://bertt.github.io/cesium_issues/i3dm_gpu/issue

issue: EXT_mesh_gpu_instancing (red boxes), i3dm (trees), poisiton wrong, scale wrong

https://bertt.github.io/cesium_issues/i3dm_gpu/issue

![image](https://github.com/bertt/cesium_issues/assets/538812/8a053b75-c84b-46d1-ae45-01293c3e53f6)

fix: fix code for scaling, positions

https://bertt.github.io/cesium_issues/i3dm_gpu/fix

Fixed: https://bertt.github.io/cesium_issues/i3dm_gpu/fixed


6] Metadata int64 - nodata

https://bertt.github.io/cesium_issues/int64_nodata/

Issue: CesiumJS does show the int64 value when setting it to Nodata

7] Metadata Vector3 - float32 - noData

https://bertt.github.io/cesium_issues/vector3_float32_nodata/

Issue: When clicking a triangle with vector3 attribute set to Nodata, an exception throws.

TypeError: Cannot read properties of undefined (reading '0') in unpack function

8] Long lines - Implicit and Explicit tiling

Issue: When using implicit tiling and geometries that span multiple tiles, the geometry can dissappear

issue: https://bertt.github.io/cesium_issues/long_lines/implicit

workaround use explicit tiling: https://bertt.github.io/cesium_issues/long_lines/explicit

9] Shadows

https://bertt.github.io/cesium_issues/shadows/

![image](https://github.com/bertt/cesium_issues/assets/538812/55b2bc64-dc62-48f8-ac4a-62630326b5ad)

10] Shaky GPU instances

Issue: When using Cesium ECEF positions in GPU instances, jittering occurs

https://bertt.github.io/cesium_issues/shaky_gpu_instances/issue/

11] Disappearing i3dm's

Issue: When using a tree with RTC_CENTER in i3dm, one of the trees disappears. When using a box it does not occur

Tree: https://bertt.github.io/cesium_issues/i3dm_disappearing/tree/

Box: https://bertt.github.io/cesium_issues/i3dm_disappearing/box/
