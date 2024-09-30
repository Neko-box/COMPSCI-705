# Spatial Unity SDK Starter Template

A template to get you started building environments for Spatial.

Read more here: https://docs.spatial.io


This is the Spatial template you can see in Canvas and I made some improvements.

Added 7 prefabs in 7 different colors material and it is 8 in total. You can find it in Assets -> Examples -> Avatar_Spatian.
Also made couple of visual scripts(Assets -> Examples -> Avatar_Spatian -> Scripts)

## How to use:
1. Create a scene in Portal (top-right)
2. Create an empty object in the scene.
3. Drag one prefab into the object.
4. Create -> Spatial -> Interactable, create an interactable object in the object you created in step 1. Make sure that interactable object matches prefab.
5. Open Portal, Create -> Choose "Avatar" in drop-down list then click "Create" -> Drag the prefab into "Prefab" -> Click "Publish" -> Copy the SKU
6. Add new component "Script Machine" in interactable object, then use the .asset file in Assets -> Examples -> Avatar_Spatian -> Scripts. Click "Edit Graph", replace the SKU string with yours.
7. Test in Spatial.

### Structure
| Prefab        |Script           |
| ------------- |:---------------:|
| Spatian       | SpatianPicker   |
| Spatian1      | SpatianPicker2  |
| Spatian2      | SpatianPicker3  |
| Spatian3      | SpatianPicker4  |
| Spatian4      | SpatianPicker5  |
| Spatian5      | SpatianPicker6  |
| Spatian6      | SpatianPicker7  |
| Spatian7      | SpatianPicker8  |

### Brightness
In this scene, I created a "photo studio" scene, which contains 4 rooms. The "photo studio" and the rooms are set to 0 reflection to ensure the reaction between the brightness and the avatar.

### Result of Questionniare
[Scatter Plot](https://imgur.com/a/ipNRlfG) 

![Bubble Chart](img/Screenshot 2024-09-30 192502.png)
