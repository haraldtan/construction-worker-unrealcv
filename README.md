# construction-worker-unrealcv

This project is a showcase of how computer vision can be used to detect objects in a picture or a scene, specifically the use of image segmentation and object masks. The Unreal Engine 5 project demonstrates the detection of a construction worker model, as well as key objects of interest (helmet, safety vest, gloves, boots). 

Segmentation of the UE5 scene is done using the plugin UnrealCV. Below is a screenshot showcasing how unrealcv is able to detect the various objects in the scene, and assign each object with a unique color.

More details of UnrealCV can be found here: https://unrealcv.org/

![Image](https://i.imgur.com/m5Az2Ci.png)

# Steps to enable plugin and segmentation view

1. The plugin is installed under plugins/UnrealCV. To check if it is enabled, go to Edit > Plugins > Search for Unreal CV > Enable
2. Under Edit > Project Settings > Platforms > Windows, check if Default RHI is set to DirectX 11
3. Press Play
4. Press the Back Quote (`) key to show console
5. In the console, enter in `vset /viewmode object_mask`, the scene shall turn similar to the above screenshot

* Note: The colors assigned by UnrealCV to the objects may not be the same as showcased in the screenshot
