[Godot Transform Clusters]

Info:
Transform cluster addon used in my own projects. It allows arbitrary groups of Node3Ds to move in unison. Great for editing groups of collision shapes, which must be immediate children of physics bodies. Works in editor and/or runtime.
This addon is provided as is. There will be no support, but I may make changes to this as I develop my own project.

Usage:
Put the addon in your addons folder in your project.
You can now create TransformCluster3D nodes, which expose an array of Node3D to "cluster" together. It also exposes properties to toggle the clustering behaviour in editor and/or at runtime.
You can configure these manually through the editor or programmatically.

Notes:
Whenever you enable/disable a cluster, or in any way modify the constituent node array, it takes a snapshot of their relative spatial relations at that moment.