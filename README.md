# Unity OBJ Loader

- [Rich Logan](http://github.com/RichLogan) @ 08/11/16
    - Added support for Unity 5
    - Removed responsibility of file loading
    - Material support removed until I get round to fixing it

Project home: https://github.com/hammmm/unity-obj-loader

This project is to achieve good-enough runtime OBJ file importing for Unity3D,
based on Bartek Drozdz's OBJ library v1.2.
http://www.everyday3d.com/blog/index.php/2010/05/24/loading-3d-models-runtime-unity3d/

Many thanks to the original author, Bartek Drozdz for publishing the code under MIT license.

License: MIT

Notes:
 - please put all texture files on the same directory of . obj file.
 - please use use this form of URL for local files. ex) file:///Users/someone/somepath/model.obj
 - Bump map is not correctly working. TODO: convert hight map to normal map, make tangent data.
