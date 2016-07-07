# aframe-touch-rotation-controls

Touch rotation control component for the camera entity in A-Frame 0.2.0. 

Based on the mouse-controls component of @donmccurdy and compatible with with the universal-controls component of [aframe-extras](https://github.com/donmccurdy/aframe-extras/tree/master/src/controls)

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.2.0/aframe.min.js"></script>
  <script src="https://rawgit.com/allanweir/aframe-touch-rotation-controls/master/dist/aframe-touch-rotation-controls.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity camera universal-controls="movementControls: hmd; rotationControls: touch-rotation"></a-entity>
  </a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-touch-rotation-controls
```

Then register and use.

```js
require('aframe');
require('aframe-touch-rotation-controls');
```
