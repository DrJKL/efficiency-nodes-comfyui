Efficiency Nodes for ComfyUI
=======
### A collection of <a href="https://github.com/comfyanonymous/ComfyUI" >ComfyUI</a> custom nodes to help streamline workflows and reduce total node count.
## [Direct Download Link](https://github.com/LucianoCirino/efficiency-nodes-comfyui/releases/download/v1.1/efficiency-nodes-comfyui_v1.1.zip)

## **Currently Available Nodes:**
<details><summary>Ksampler (Efficient)</summary><ul>
• A modded KSampler with the ability to preview and output images.<br>
• Re-outputs key inputs which helps promote a cleaner and more streamlined workflow look for ComfyUI.<br>
• Can force hold all of its outputs without regenerating by setting its state to "Hold".
<blockquote>note: when using multiple instances of this node, each instance must have a unique ID for the "Hold" state to function properly.</blockquote>
</ul></details>

<details><summary>Efficient Loader</summary><ul>
• A combination of common initialization nodes.
</ul></details>

<details><summary>Image Overlay</summary><ul>
• Node that allows for flexible image overlaying.
</ul></details>

<details><summary>Evaluate Integers</summary><ul>
• 3 integer input node that gives the user ability to write their own python expression for a INT/FLOAT type output.
</ul></details>

<details><summary>Evaluate Strings</summary><ul>
• 3 string input node that gives the user ability to write their own python expression for a STRING type output.
</ul></details>

## **Examples:**
  
- HiResFix using the **Efficient Loader** & **Ksampler (Efficient)**

<img src="https://github.com/LucianoCirino/efficiency-nodes-comfyui/blob/main/workflows/HiResFix.png" width="720">

- Photobashing using the **Image Overlay** node

<img src="https://github.com/LucianoCirino/efficiency-nodes-comfyui/blob/main/workflows/ImgOverlay.png" width="720">


## **Install:**
To install, drop the "_**efficiency-nodes-comfyui**_" folder into the "_**...\ComfyUI\ComfyUI\custom_nodes**_" directory and restart UI.
