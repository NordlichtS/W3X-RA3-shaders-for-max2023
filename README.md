# W3X-RA3-shaders-for-max2023
Rewritten RedAlert3 shaders for 3dsmax 2017-2023, so you can assign, preview and export materials when making mods just like those back in 3dsMax9

It appears the updated 2023 w3x exporter on w3dhub has one annoying flaw: cannot use shaders from the game's sdk. No preview and no parameter export can be such a hassle for modders. This repository aim to fix (or should i say bypass) this flaw.

How to use:

Download any of these FX files as you need (do NOT compile them! 3dsmax need to read the source HLSL code to show you its parameter editors) 
put them in any folder, and choose the shader you need in 3dsmax compact material editor.

Basically the same workflow as those in (outdated) 3dsmax 9
![alt text](https://github.com/NordlichtS/W3X-RA3-shaders-for-max2023/blob/main/shader%20param%20objects.png?raw=true)

ATTENTION ! Max 2017-2023 use DX11 for viewport driver by default, you need to change the driver to DX9 or LegacyD3D in " file - preferences - viewport " in order to use these shaders, as they are written in DX9's standard.

To export the model: 

you need to use the updated w3x exporter (which also need LegacyD3D driver to work properly)

https://w3dhub.com/forum/files/file/37-w3d-tools-3ds-max-2023-exporter/

it will record all your shader parameters into the w3x mesh files just like old ones 

(find "FXshader" in your W3X mesh file to check on them if you want)

![alt text](https://github.com/NordlichtS/W3X-RA3-shaders-for-max2023/blob/main/shader%20param%20infantry.png?)
