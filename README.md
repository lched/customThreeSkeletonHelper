# CustomThreeSkeletonHelper

Custom reimplementation of Three.js SkeletonHelper that allows to edit properties such as linewidth that are [otherwise ignored by WebGL](https://threejs.org/docs/index.html#api/en/materials/LineBasicMaterial).
The interesting file here is [src/customSkeletonHelper.js](https://github.com/lched/customThreeSkeletonHelper/blob/main/src/customSkeletonHelper.js).

To use it in your project, simply copy that file and import the SkeletonHelper like:
    import {SkeletonHelper} from  './customSkeletonHelper';
Then use that version instead of the one from Three. Properties can be passed to the object when instantiating it or through one of the Set methods.

![image showing skeleton with customized linewidth](https://github.com/lched/customThreeSkeletonHelper/blob/main/example.png)


Inspired by [https://discourse.threejs.org/t/extend-skeletonhelper-to-accommodate-fat-lines-perhaps-with-linesegments2/59436](https://discourse.threejs.org/t/extend-skeletonhelper-to-accommodate-fat-lines-perhaps-with-linesegments2/59436)

