### NewsCube - Open Source
NewsCube is a research project that explored hypetertext interactivity by visually representing complex stories on the six faces of a cube.

### License & Usage
You can integrate NewsCube in your website by folowing a few simple steps. NewsCube is based on the CSS 3D component of [ThreeJS](http://threejs.org) framework.
NewsCube is distributed under the Apache GNU license. ThreeJS is distributed under the ... license.

## Simple JavaScript integration
To add a NewsCube to your project, you should follow three simple steps:

# Include the NewsCube JavaScript core files
```
<script type="text/javascript" src="newscube/core/dependencies/threejs/3d.min.js"></script>
<script type="text/javascript" src="newscube/core/dependencies/threejs/OrbitControls.js"></script>
<script type="text/javascript" src="newscube/core/cube.js"></script>
```

# Create a NewsCube container
```
<div id="newscube"></div>
```

# Spin your NewsCube!
```
var faces = ['faces/front.html', 
			 'faces/right.html', 
			 'faces/back.html', 
			 'faces/left.html', 
			 'faces/bottom.html', 
			 'faces/top.html'];

var callback = function(f) {
	console.log(f);
}

var newsCube = new NewsCube('newscube', callback, faces);

newsCube.start();
```

## Advanced guide

Find out more about what you can do with the [NewsCube API](ADVANCED.md) 
