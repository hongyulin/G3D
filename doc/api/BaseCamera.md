# BaseCamera

Base camera, extends from [Node](./Node).

## Constructor

```javascript
new G3D.BaseCamera(scene);
```

### Arguments

| name  | type      | description                                 |
| ----- | --------- | ------------------------------------------- |
| scene | G3D.Scene | the g3d scene you want to put the camera in |

## Properties

| name   | type                              | description                                                              |
| ------ | --------------------------------- | ------------------------------------------------------------------------ |
| center | {x: Number, y: Number, z: Number} | the center point the camera is looking at, default is {x: 0, y: 0, z: 0} |
| up     | {x: Number, y: Number, z: Number} | the up direction of the camera, default is {x: 0, y: 1, z: 0}            |
