![repaiocelohc1_4](https://github.com/user-attachments/assets/b2ad1856-fa41-4d65-9608-47889f8f23a8)


# Tech Art Toolkit

![Unity Version](https://img.shields.io/badge/Unity-6000.0.27%27LTS%2B-blueviolet?logo=unity)
![Unity Pipeline Support (Built-In)](https://img.shields.io/badge/BiRP_✔️-darkgreen?logo=unity)
![Unity Pipeline Support (URP)](https://img.shields.io/badge/URP_✔️-blue?logo=unity)
![Unity Pipeline Support (HDRP)](https://img.shields.io/badge/HDRP_✔️-darkred?logo=unity)

Tech Art Toolkit is an unity editor tool specializing in dealing with matters that technical artists handle like compressing textures, animation, etc via automation scripts.
It is designed to run on the Unity URP pipeline and Unity 6, but theoretically, it could run on Unity 2022 or other versions of unity and other pipelines but it is untested.

> ***THIS REPOSITORY IS JUST A SHOWCASE OF THE TOOL[S] I DEVELOPED FOR THIS TOOLKIT FOR PORTFOLIO REASONS.***
>
> ***IN THE FUTURE, I WILL PROVIDE A SIMPLIFIED VERSION OF ONE OF THE TOOLS THAT YOU CAN USE FOR PROJECTS OR LEARNING***

<ins>Do note that the tool is still in its early stages, there is still quite a bit of things to iron out, improve, and add onto.</ins>

## Features
- Choose from a variety of tools to handle all kinds of tasks for a particular, from audio to animation files
- Ability to compress assets like audio, animation, and 3D models to save on disk space or for mobile porting
- Automate converting materials to a standard URP lit shader or a selected shader, useful for correcting pink material error in URP
- Automate texture setting setup for texture files
- An all in one GUI window interface to utilize the tool in Unity's editor

## Example[s]
<div align="center">
  <img src="https://github.com/user-attachments/assets/b2ad1856-fa41-4d65-9608-47889f8f23a8" width="450" alt="GIF"/>
</div>
<p align="center">Preview from the results of the animation compression.</p>
<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/2564d9c6-039e-4e45-8f19-20d7b806d039" width="450" alt="JPG"/>
</div>
<p align="center">A screenshot of the animation compression results.</p>
<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/869924e7-b3b0-4f3c-b6eb-de218337cbe2" width="450" alt="JPG2"/>
</div>
<p align="center">A screenshot of the audio compression results.</p>
<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/96043bbc-2423-4251-9d63-e11fb2f18e9e" width="450" alt="WINDOWJPG"/>
</div>
<p align="center">The older version of what the Tech Art Toolkit looks like in its all in one GUI window, currently selected the 
audio tab for the audio compression tool.</p>
<br>

## Installation
1. Clone repo or download the folder and load it into an unity project.
2. If installing from a Unity package, navigate to Assets > Import Packages, select the Unity package, and open it. A popup will appear showing the contents of the package. Choose to import everything from the package and click OK.
3. To use the tool, navigate to Tools > Tech Art Toolkit, and select that option.
4. If you did it right, a window popup should appear with the tabs of the tools and the settings for the tools.

## Credits/Assets used
Amane Kisora Animations and Character model (Free Version) by BLACKC Inc. Used for demonstration and testing purposes only. No changes made to the model and animation. (https://assetstore.unity.com/packages/3d/characters/amane-kisora-chan-free-ver-70581)

Tool was initially inspired by OsmYlmztrk’s UnityCompressionTool/CreativeSoda’s Compression Tool. Some of the code can be based from there. (https://github.com/OsmYlmztrk/UnityCompressionTool/tree/main)
