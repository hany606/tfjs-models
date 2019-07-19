# Pre-trained TensorFlow.js posenet model

This repository is forked from (tfjs-models repo)[https://github.com/tensorflow/tfjs-models] and has been modified to have only posenet model.

This repository hosts a pre-trained model of posenet that has been ported to
TensorFlow.js.

The model is hosted on NPM and unpkg so it can be used in any project out of the box. It can be used directly or used in a transfer learning
setting with TensorFlow.js.

To find out about APIs for models, look at the README in each of the respective
directories. In general, we try to hide tensors so the API can be used by
non-machine learning experts.

For those interested in contributing a model, please file a [GitHub issue on tfjs](https://github.com/tensorflow/tfjs/issues) to gauge
interest. We are trying to add models that complement the existing set of models
and can be used as building blocks in other apps.

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
