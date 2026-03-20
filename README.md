# Chess 2 - Modified Cburnett Pieces

This repository contains the modified chess pieces used in the Android game **Chess 2**.

## Original Source
These pieces are based on the famous "Cburnett" SVG chess set, originally created by **Colin Burnett** and hosted on Wikimedia Commons.

## Modifications Made
To fit the unique visual style of Chess 2, the following extensive modifications were made to the original files:
* **Color inversion:** Swapped black and white colors based on the original black pieces.
* **Extensive structural redesign:** The shapes and contours of the set were significantly altered and redrawn to create a distinct new design, while maintaining the core Cburnett forms.
* **Format conversion:** Converted the original SVG files into Android Vector Drawable (.xml) format for native use in the application.

## Note on Technical Implementation (Textures)
In the Chess 2 application, AI-generated textures are applied to these modified base shapes **dynamically at runtime via code**. 
The textured pieces do not exist as pre-baked or pre-rendered image files in the game's assets. Therefore, the dynamic rendering code and the separate texture files are independent components and remain proprietary, functioning as a Collection alongside these CC BY-SA 3.0 vector XML shapes.

## License
In accordance with the ShareAlike condition of the original work, these modified assets are released under the **Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)** License.

* Original Author: Colin Burnett
* License Details: [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)
