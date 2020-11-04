# Installation
Copy the shader files (i.e. `2dtocube.txt`) into your `%MAGICAVOXEL_DIR%/shader` folder. 


# 2dtocube shader

![](https://github.com/LunchHours/Teardown-Tools-and-else/blob/main/MagicaVoxelShaders/images/2dtocube.png)

Supports 3 types of "fill" modes (see screenshot above). Set the desired fill mode via MagicaVoxel. Modes are as follows:
- 0: randomly based on initial texture
- 1: hollow
- 2: preselected color (via palette)

### How to use

#### Note: this script will _not_ import the needed palette. 
#### Please ensure the colors needed for the image you are importing are already in the palette

1. Import any image into MagicaVoxel by dragging it into it
  ![](https://github.com/LunchHours/Teardown-Tools-and-else/blob/main/MagicaVoxelShaders/images/step-import-image.jpg)

2. Increase object size so that the pattern stays at layer 0 (z=0)
  ![](https://github.com/LunchHours/Teardown-Tools-and-else/blob/main/MagicaVoxelShaders/images/increase%20obbject%20size.jpg)
  
3. Open the shader pattern, select 2dtocube.txt and click the run button
  ![](https://github.com/LunchHours/Teardown-Tools-and-else/blob/main/MagicaVoxelShaders/images/open%20shader%20panel.jpg)
  
4. Delete initial pattern
  ![](https://github.com/LunchHours/Teardown-Tools-and-else/blob/main/MagicaVoxelShaders/images/delete-pattern.jpg)
 
5. Done!
