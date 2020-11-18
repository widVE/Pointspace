---
title: "Capture"
bg: orange
color: uw-body-font
style: center
fa-icon: camera
---
# Capturing the real-world

![istandard-method](images/standardmethod.gif)
![istandard-mesh](images/standardmesh.gif)

People often turn to using capture technologies, such as LiDAR scanning to capture real world environments.  Datasets are captured as a series of points in 3D space, which is referred to as a pointcloud.  These pointclouds are often converted into triangulated meshes for visualizations.



## Advantages of Point Clouds



![Mesh example](images/mesh_example_1.png)
![Point cloud example](images/points_example_1.png)

Comparing the mesh rendering of an environment (Left) shows that many details are lost compared to the original point cloud file (Right).

## Challenges of Point Clouds



<!---

Point cloud datasets can have uneven sampling, like in the image below. Our rendering techniques fill in holes in the data for a seamless final image.

![Uneven sampling](images/uneven_sampling.png)
-->


<style type="text/css">
#wrapper {
  display: flex;
  

}

#left {
  flex: 0 0 50%;
  padding: 15px;
}

#right {
  flex: 1;
   padding: 15px;
}
</style>

<div id="wrapper">
  <div id="left">
  
  <img src="images/Screenshot.jpg">

  </div>
  <div id="right">
   <img src="images/Screenshot2.jpg">

  
  </div>
  
</div>

<div id="wrapper">
  <div id="left">
  
  <img src="images/Screenshot3.jpg">

  </div>
  <div id="right">
   <img src="images/Screenshot4.jpg">

  
  </div>
  
</div>

As points do not have volume, controlling the sampling of points when rendering can be difficult.  The figure above shows four different sampling techniques used in a standard point cloud rendering system.  As shown, the surfaces either appear blocky or see-through.


