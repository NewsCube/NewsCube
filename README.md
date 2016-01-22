# NewsCube - Open Source
The NewsCube is an interactive, 3D storytelling tool that uses a cube to show multiple perspectives on a complex issue. The sides of a NewsCube can be used to hold original or aggregated content in the form of text, images, sounds, vision or documents.

## Usage
Use the NewsCube to ...

## License
You can integrate NewsCube in your website by folowing a few simple steps. NewsCube is based on the CSS 3D component of [ThreeJS](http://threejs.org) framework.
NewsCube is distributed under the Apache GNU license ?????. ThreeJS is distributed under the ... license.

# Integration

## Simple JavaScript integration
To add a NewsCube to your project, you should follow three simple steps:

### Include the NewsCube JavaScript core files
```
<script type="text/javascript" src="newscube/core/dependencies/threejs/3d.min.js"></script>
<script type="text/javascript" src="newscube/core/dependencies/threejs/OrbitControls.js"></script>
<script type="text/javascript" src="newscube/core/cube.js"></script>
```

### Create a NewsCube container
```
<div id="newscube"></div>
```

### Spin your NewsCube!
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

### Advanced guide

Find out more about what you can do with the [NewsCube API](ADVANCED.md) 

# Find out more


## Credits
The NewsCube was created by Skye Doherty, developed by Andrea Epifani, and made beautiful by David Lloyd

## Contact
Get in touch via the NewsCubed website: http://newscubed.com
Try our implementation at: http://newscube.io
