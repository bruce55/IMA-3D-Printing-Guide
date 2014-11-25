Advanced 3D Printing Guide For IMA
=====
[TOC]
##Intro
This guide is for students who have special requirements on 3D printing or want to achieve a higher printing speed and quality. For a basic tutorial, look at the Student Worker Training Manual.

##Preparation
###Modeling
In order to print with 3D printer, you need to prepare a 3D model. 
The recommended website is [__Thingiverse__](http://www.thingiverse.com/). It's a open model community where everyone can upload and download models people made.

If you want to make your own model, following softwares are recommended:

* [Tinkercad](https://tinkercad.com/) (A free easy to use online tool for beginners to easily build 3D models, a part of the 123D utilities)
	* [Other 123D Tools](http://www.123dapp.com/) (Sculpt, Catch, Make and Meshmixer are great tools for this use)
* [Blender](http://www.blender.org/) (A miracle of opensource. It's a cross platform all-in-one 3D studio that is super powerful. A bit hard to learn though. Tutorial available for NYU students on Lynda.com. Not the best when you need to deal with real precise sizes.)
* [Autodesk software](http://www.autodesk.com/education/free-software/all) (Mostly free for students!)
	* Alias (Good for designing especially when dealing with curved surfaces. Normal meshes are also supported)
	* Autocad (Professional CAD software)
 	* 3DS Max (Good for polygons, but same as Blender, not good for CAD use)
 	* Maya (Not good for CAD use)
* Rhino (A bit similar to Alias. It will be available on some IMA computers in the near future)
* Solidworks (Professional 3D CAD software. Very suitable for creating 3D printable models)

When creating the model, you have to notice one thing is that the mesh needs to be closed. A single piece of mesh is not 3D printable because it doesn't contain any thickness information. The mesh's definition is similar to the surface in math.

Here is an example:
![Example P1](https://lh5.googleusercontent.com/yIF8JgICy7oYP5w3jPDVZLFq2CdqlL25DhdUiLTrOvc=s0 "render.png")
The green one is correct and red one is a bad example.

You say you can't see the difference? OK here is the close-up:
![Example P2](https://lh3.googleusercontent.com/S2-5a3A7c4hHRZYkOBGMYfPIeSQqFtmunxuYmKE0bl0=s0 "render_compare.png")
The green one has thickness.
###Creating Support
Because of the way 3D printer works, one thing you need to care about is the supporting structure. Though Cura we use to generate G-Code has support generation, it is very hard to be removed. Use the knife in the cabinet near the printer. There is also a pair of protecting gloves.