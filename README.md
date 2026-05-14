# vr-tree

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple VR environment for procedurally generating and interacting with voxel-based trees, built with A-Frame.

## Demo

https://code4fukui.github.io/vr-tree/


![A VR scene showing two procedurally generated voxel trees on a grid plane. One tree is tall and angular, the other is shorter and more rounded. VR controllers are visible in the foreground.](https://user-images.githubusercontent.com/1715217/199850195-94a52e5e-3fb5-4af7-9fce-14697eaac39f.png)


## Features

-   Procedural tree generation using [voxel-trees](https://github.com/code4fukui/voxel-trees).
-   Two distinct tree algorithms: `"subspace"` (angular) and `"guybrush"` (rounded).
-   Interactive VR world where you can place and remove blocks.
-   Support for Oculus Touch controllers to manipulate four different block types: soil, dry wood, leaves, and grass.

## Getting Started

### Prerequisites

-   A VR headset with controllers (e.g., Oculus Quest/Rift).
-   A WebXR-compatible browser (e.g., Oculus Browser, Firefox Reality).

### Running Locally

1.  Clone the repository:
    ```sh
    git clone https://github.com/code4fukui/vr-tree.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd vr-tree
    ```
3.  Start a local web server. For example, using Python:
    ```sh
    python -m http.server
    ```
4