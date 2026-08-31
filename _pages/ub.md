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

/* Tab styles */
.tabs {
  margin-top: 1rem;
}
.tab-buttons {
  display: flex;
  gap: 10px;
  margin-bottom: 1rem;
}
.tab-buttons button {
  padding: 6px 12px;
  border: none;
  border-radius: 6px;
  background: #eee;
  cursor: pointer;
}
.tab-buttons button.active {
  background: #333;
  color: white;
}
.tab-content {
  display: none;
}
.tab-content.active {
  display: block;
}
.img-row {
  display: flex;
  gap: 10px;
  margin-top: 1rem;
}
.img-col {
  position: relative;
  flex: 1;
}
.img-col img {
  width: 100%;
}
.img-col span {
  position: absolute;
  bottom: 5px;
  left: 50%;
  transform: translateX(-50%);
  background: rgba(0,0,0,0.6);
  color: white;
  padding: 2px 6px;
  border-radius: 4px;
  font-size: 14px;
}
</style>

<h1>Example of monocular depth estimation</h1>

<div class="tabs">
  <!-- Tab buttons -->
  <div class="tab-buttons">
    <button class="active" onclick="openTab('ub')">UB Result</button>
    <button onclick="openTab('uh')">UH Result</button>
  </div>

  <!-- UB tab -->
  <div id="ub" class="tab-content active">
    <model-viewer alt="UB model" src="../assets/mesh/ub.glb"
                  auto-rotate auto-rotate-delay="0"
                  shadow-intensity="1" camera-controls touch-action="pan-y"
                  camera-orbit="0deg 75deg 0m"
                  rotation-per-second="15deg"
                  interaction-prompt="none">
    </model-viewer>

    <div class="img-row">
      <div class="img-col">
        <img src="/assets/img/ub.jpg" alt="UB Input">
        <span>Input image</span>
      </div>
      <div class="img-col">
        <img src="/assets/img/ub_depth.png" alt="UB Depth">
        <span>Depth</span>
      </div>
      <div class="img-col">
        <img src="/assets/img/ub_normal.png" alt="UB Normals">
        <span>Surface normals</span>
      </div>
    </div>
  </div>

  <!-- UH tab -->
  <div id="uh" class="tab-content">
    <model-viewer alt="UH model" src="../assets/mesh/uh.glb"
                  auto-rotate auto-rotate-delay="0"
                  shadow-intensity="1" camera-controls touch-action="pan-y"
                  camera-orbit="15deg 0deg 0m"
                  rotation-per-second="15deg"
                  interaction-prompt="none">
    </model-viewer>

    <div class="img-row">
      <div class="img-col">
        <img src="/assets/img/uh.jpg" alt="UH Input">
        <span>Input image</span>
      </div>
      <div class="img-col">
        <img src="/assets/img/uh_depth.png" alt="UH Depth">
        <span>Depth</span>
      </div>
      <div class="img-col">
        <img src="/assets/img/uh_normal.png" alt="UH Normals">
        <span>Surface normals</span>
      </div>
    </div>
  </div>
</div>

<script>
function openTab(id) {
  document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
  document.querySelectorAll('.tab-buttons button').forEach(btn => btn.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  event.target.classList.add('active');
}
</script>