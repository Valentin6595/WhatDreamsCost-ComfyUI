# Overview

This will be a collection of free resources for ComfyUI.

Hopefully it will make creating cool stuff easier.

All of my nodes are created with the help of AI, so there may or may not be redundant, messy code.

## ▶️ YouTube Video 
Placeholder


## ⚙️ How to install nodes

- Navigate to your `/ComfyUI/custom_nodes/ folder`
- Run `git clone https://github.com/WhatDreamscost/WhatDreamsCost-ComfyUI`

## 🔄 Recent Updates
*Coming Soon*

# Custom Nodes

## Multi Image Loader

A Image loader that features a built in gallery, allowing your to easily rearrange images and output them seperately or batched together. It also combines the image resize node and LTXVPreprocess node to reduce clutter in LTX workflows.

## LTX Sequencer

An overhaul of the LTXVAddGuideMulti node. It allows you to quickly create FFLF (First Frame Last Frame) videos, shot sequences, supports any number of middle frames.

Connect the Multi Image Loader node's multi_output to automatically update the node's widgets.

It also has a sync feature that syncs all LTX Sequencer nodes together in realtime, removing the need to edit every single node manually every time you want to make a change to something. 



## LTX Keyframer

An overhaul of the LTXVImgToVideoInplaceKJ node. It allows you to quickly create FFLF (First Frame Last Frame) videos, shot sequences, supports any number of middle frames.

Connect the Multi Image Loader node's multi_output to automatically update the node's widgets.

It also has a sync feature that syncs all LTX Keyframer nodes together in realtime, removing the need to edit every single node manually every time you want to make a change to something. 

**I would recommend only using the LTX Sequencer Node as it is superior to this node after further testing**


## Workflows


## Additional Info

I made these nodes knowing almost nothing about python and a beginner level knowledge of javascript. Feel free to suggest improvements, and if you run into any bugs let me know.

For those asking, I mainly used gemini to create these nodes.
