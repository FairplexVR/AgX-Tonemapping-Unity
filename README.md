## AgX Color Grading for Unity

Based on the original [AgX by Troy Sobotka](https://github.com/sobotka/AgX).

### What is this?

AgX is the new color transform introduced in Blender 4.0, surpassing Filmic and ACES in many aspects. This repository contains a collection of AgX LUTs that are compatible with Unity BIRP, URP, and HDRP.

### How to use it?

If you're not familiar with external LUTs in Unity, follow these steps to set it up. Assuming your project is configured in Linear Color Space with a working Post-Process, here's how to add the external LUTs:

1. Download the package from this repository and place it in your Unity project's assets directory.
2. In your global Post-Process Volume Component, add a Color Grading effect by clicking on Add Effect... > Unity > Color Grading.
3. Change the Mode to External.
4. In the Lookup Texture field, drag and drop a LUT of your choice.

### Achieving a 1:1 Look with Blender!

With the implementation of AgX, you can now achieve a 1:1 look between Blender and Unity. This means that the view transform is identical, ensuring seamless continuity in the visual representation of your projects across both platforms.

### Why is it so great, and why you really need to use it?

Let the images speak for themselves:

#### No Color Grading:

![Screenshot_3](https://github.com/FairplexVR/AgX-Luts-Unity/assets/31825109/4ef7425d-c4df-49ac-8223-22f65d712010)

#### ACES:

![Screenshot_4](https://github.com/FairplexVR/AgX-Luts-Unity/assets/31825109/4b7ce6c3-5ef8-4ef3-b89c-338d0ece1ead)

#### AgX:

![Screenshot_5](https://github.com/FairplexVR/AgX-Luts-Unity/assets/31825109/67ff7eb0-9994-4b62-8ff0-db74d1805544)

#### Blender:

![Screenshot_6](https://github.com/FairplexVR/AgX-Luts-Unity/assets/31825109/a911c21e-b8aa-494b-82d6-0b46c8aebb28)