# NYU Digital Art, Wk 12
11-30-2018

_Outline:_
* Intros
* p5 Homework Critique
* Intro to (Web) VR


### VR & Art Inspiration
[8 Virtual Reality Artists Who Use the World as Their Canvas – Kadenze Blog](https://blog.kadenze.com/creative-technology/8-virtual-reality-artists-who-use-the-world-as-their-canvas/?utm_source=kadenze&utm_medium=email&utm_campaign=weekly_blog_email)

### Intro to A-frame & Glitch
[A-Frame School](https://aframe.io/aframe-school/#/)


### Source Materials for Import
* Flickr album of equirectangular images
https://www.flickr.com/groups/equirectangular/

* Sources for 3D models:
thingiverse.com
[3D Warehouse](https://3dwarehouse.sketchup.com/)
sketchfab.com
turbosquid.com


### Directions for importing 3D models into A-frame:

1) find a model online and download it to your computer

2) make sure it is a .gltf or .obj or .dae or file

3) if it is not, go to a [converter site](http://www.greentoken.de/onlineconv/), upload it and change it into a .gltf or .obj or .dae file

4) upload it to your project’s asset folder on glitch.com

5) edit your web page to load the model file as an <a-asset> and give it an ID

6) use one of the tags

```
 <a-collada-model src=“#your_ID”></a-collada-model> 

<a-obj-model src=“#cabin”></a-obj-model> 

<a-entity gltf-model=“url(/path/to/tree.gltf)”></a-entity>
```


### Try it yourself, Demo
[Dropbox - wk13_custom_3D_0bjects - Simplify your life](https://www.dropbox.com/sh/ulbxr01wym1a19v/AACo8ZGBktd6eRqBo_zeHSPaa?dl=0)

### Example code (to import 3D objects)
https://glitch.com/edit/#!/wooden-porcupine?path=index.html:24:48

#Ed_F18/LectureNotes# #Ed_F18/NYU
