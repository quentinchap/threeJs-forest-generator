# Forest generator

Little piece of code to centralize the work around low poly forest.

## Usage
include files:
```javascript
    <script src="..tree.js"></script>
    <script src="..forest.js"></script>
```


Instantiate the forest:

```javascript
 new Forest(path of the 3D model,scene, radius, forestPosition, number of tree , minScale , maxScale, minAnimationDuration, maxAnimationDuration, ground, debug);
 ```

Example:
```javascript
 var forestPosition = { x:10, z: 20};
 new Forest("../object-lib/threeJs-forest-generator/3DModels/tree.json",scene, 200, forestPosition, 50, 2, 5, 4, 6, ground, debug);
 ```

**Note** this repo contain some 3D Model made with Blender
