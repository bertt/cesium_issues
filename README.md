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

Fix: Use relative instance positions

https://bertt.github.io/cesium_issues/shaky_gpu_instances/fix/

11] Disappearing i3dm's

Issue: When using a tree with RTC_CENTER in i3dm, one of the trees disappears. When using a box it does not occur

Tree: https://bertt.github.io/cesium_issues/i3dm_disappearing/tree/

Box: https://bertt.github.io/cesium_issues/i3dm_disappearing/box/

12] Disappearing i3dm's - windmills

Issue: When using a windmill it does disappear sometimes

Windmill: https://bertt.github.io/cesium_issues/i3dm_disappearing2/issue/

Repaired windmill: https://bertt.github.io/cesium_issues/i3dm_disappearing2/workaround/

ClearnodeTransform: https://bertt.github.io/cesium_issues/i3dm_disappearing2/clearnodetransform/index.html

Testing PR 12015: https://bertt.github.io/cesium_issues/i3dm_disappearing2/testing_pr_12105/

(uses CesiumJS from https://bertt.github.io/cesium_issues/i3dm_disappearing2/testing_pr_12105/cesium/Cesium.js)

Test kast with PR 12015: https://bertt.github.io/cesium_issues/i3dm_disappearing2/testing_pr_12105_kast/

Textured trees testing: https://bertt.github.io/cesium_issues/i3dm_disappearing2/issue_textured_trees

13] Animating i3dm's - windmills

Issue: How can we animate I3dm's?

Windmill: https://bertt.github.io/cesium_issues/i3dm_animating/issue/

14] I3dm with GPU instancing GLB inside

Issue: Nothing gets drawn

Windmill: https://bertt.github.io/cesium_issues/i3dm_with_gpu_instancing/issue/

15]] Instanced model with multiple meshes - only first first mesg displays attributes

https://community.cesium.com/t/show-attributes-of-gpu-instancing-model-with-multiple-meshes/35842

Demo: Only red works https://bertt.github.io/cesium_issues/gpu_metadata_multiple_meshes/issue/red_first/

Demo: Only green works https://bertt.github.io/cesium_issues/gpu_metadata_multiple_meshes/issue/green_first/

16] Issue upgrading i3dm to glb

https://github.com/CesiumGS/3d-tiles-tools/issues/153

With a simple box it works ok:

I3dm: https://bertt.github.io/cesium_issues/instance_upgrade/box/i3dm

glb: https://bertt.github.io/cesium_issues/instance_upgrade/box/glb

But with a tree model the tree (https://bertt.github.io/cesium_issues/instance_upgrade/tree/tree.glb) doesn't show up:

I3dm: https://bertt.github.io/cesium_issues/instance_upgrade/tree/i3dm

glb: https://bertt.github.io/cesium_issues/instance_upgrade/tree/glb

Only difference is in the used model. Any ideas how to show the tree in glb format after upgrade?

17] Nodata testing

https://bertt.github.io/cesium_issues/nodata_testing/

Testing Nodata for: varchar, int16, int32 ,int64, float32, float64

Demo only displays fields id,name and not fields string_with_null_value,int16_with_null_value,int32_with_null_value,int64_with_null_value,float32_with_null_value,float64_with_null_value

18] 3dtiles_Content_voxels unsupported?

Issue: https://bertt.github.io/cesium_issues/3dtiles_Content_voxels_unsupported/issue/

Fix: https://bertt.github.io/cesium_issues/3dtiles_Content_voxels_unsupported/fix/


18] Voxel_404 quadtree

Issue: Voxels are not rendered (404) https://bertt.github.io/cesium_issues/voxels_quadtree_404/issue/

Workarround: Add 0.0.0.glb https://bertt.github.io/cesium_issues/voxels_quadtree_404/workaround/



Workaround: 
