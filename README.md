# Pre-trained TensorFlow.js posenet model

This repository is originally forked from [tfjs-models repo](https://github.com/tensorflow/tfjs-models) and has been modified to have only posenet model.


The reason behind this repository that it was a part of [this project](https://github.com/hany606/COEX-Internship19/tree/master/projects/Human_pose_estimation_drone_control); to control a clever 4 drone from Copter Express comapny using Human poses.

This repository hosts a pre-trained model of posenet that has been ported to
TensorFlow.js.

## Model

<table style="max-width:100%;table-layout:auto;">
  <tr style="text-align:center;">
    <th>Type</th>
    <th>Model</th>
    <th>Demo</th>
    <th>Details</th>
    <th>Install</th>
  </tr>
  <!-- Images -->
  
  <!-- ** PoseNet -->
  <tr>
    <td rowspan="2"><b><a style="white-space:nowrap; display:inline-block;" href="./posenet"><div style='vertical-align:middle; display:inline;'>PoseNet</div></a></b></td>
    <td><a href="https://storage.googleapis.com/tfjs-models/demos/posenet/camera.html">live</a></td>
    <td rowspan="2">A machine learning model which allows for real-time human pose estimation in the browser. See a detailed description <a href="https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5">here</a>.</td>
    <td rowspan="2"><code>npm i @tensorflow-models/posenet</code></td>
  </tr>
  <tr>
    <td><a href="./posenet/demos/camera.html">source</a></td>
  </tr>
</table>
