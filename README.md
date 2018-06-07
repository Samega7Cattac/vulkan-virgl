# Vulkan virgl


This is the main repository for the Vulkan-virglrenderer experiment.
It will clone 3 repositories:

- virglrenderer (vulkan-wip branch)
- mesa (virgl-vulkan branch)
- vulkan-compute

## Virglrenderer

Virglrenderer is a lib desinged to bring 3D acceleration to VirtIO-gpu.
Initialy, this project was designed with OpenGL in mind.
The goal of this experiment is to redesign it to support both Vulkan and OpenGL.

## Vulkan compute

A sample vulkan compute application.


# Requirements

- cmake
- git
- vulkan-headers
- libepoxy
- libdrm
- libgbm
- libdl
- meson
- autotools
- a graphic stack which supports vulkan

# How to use

```bash
./run-demo.sh
```
