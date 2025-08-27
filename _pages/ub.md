---
layout: none
permalink: /ub/
title: ub
nav: false
nav_order: 5
description: Monodepth example
---
<!-- Import the component -->
<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/4.0.0/model-viewer.min.js"></script> 
<style>
model-viewer {
  object-fit: contain;
  width: 100%;
  height: 50%;
}
</style>

<h1>Example of monocular depth estimation</h1>
<model-viewer alt="" src="../assets/mesh/ub.glb" auto-rotate auto-rotate-delay="0" shadow-intensity="1" camera-controls touch-action="pan-y" camera-orbit="15deg 75deg 0m"></model-viewer>

<div style="display: flex; gap: 10px;">
  <div style="position: relative; width: 30%;">
    <img src="/assets/img/ub.jpg" alt="Image 1" style="width: 100%;">
    <span style="position: absolute; bottom: 5px; left: 50%; 
                 transform: translateX(-50%);
                 background: rgba(0,0,0,0.6); color: white; padding: 2px 6px;
                 border-radius: 4px; font-size: 14px;">
      Input image
    </span>
  </div>
  <div style="position: relative; width: 30%;">
    <img src="/assets/img/ub_depth.png" alt="Image 2" style="width: 100%;">
    <span style="position: absolute; bottom: 5px; left: 50%; transform: translateX(-50%);
                 background: rgba(0,0,0,0.6); color: white; padding: 2px 6px;
                 border-radius: 4px; font-size: 14px;">
      Depth
    </span>
  </div>
  <div style="position: relative; width: 30%;">
    <img src="/assets/img/ub_normal.png" alt="Image 3" style="width: 100%;">
    <span style="position: absolute; bottom: 5px; left: 50%; transform: translateX(-50%);
                 background: rgba(0,0,0,0.6); color: white; padding: 2px 6px;
                 border-radius: 4px; font-size: 14px;">
      Surface normals
    </span>
  </div>
</div>