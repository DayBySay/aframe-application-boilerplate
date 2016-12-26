## aframe-my-comp-component

A My Comp component for [A-Frame](https://aframe.io).

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|          |             |               |

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.2.0/aframe.min.js"></script>
  <script src="https://rawgit.com/jujunjun110/my-comp/master/dist/aframe-my-comp-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity my-comp="exampleProp: exampleVal"></a-entity>
  </a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-my-comp-component
```

Then register and use.

```js
require('aframe');
require('aframe-my-comp-component');
```
