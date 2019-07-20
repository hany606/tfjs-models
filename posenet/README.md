# PoseNet [[source](https://github.com/tensorflow/tfjs-models/tree/master/posenet)]

## Contents

### Demo: Camera [[source](https://github.com/tensorflow/tfjs-models/tree/master/posenet)]

The camera demo shows how to estimate poses in real-time from a webcam video stream.

<img src="https://github.com/hany606/tfjs-posenet/blob/master/posenet/camera.gif" alt="cameraDemo" style="width: 600px;"/>

## Setup

cd into the posenet folder:

```sh
cd posenet/
```

Install dependencies and prepare the build directory:

```sh
yarn --watch
```

Start the server:
```sh
yarn watch
```
Open from the browser http://localhost:1234 to see the running server that estimate the human pose with 17 key points and using websockets to send the data in JSON serialization to a connected websocket server in the network.

You can change the websocket server addresse and port in the end of camera.js file.

The reason behind the exsitance of websocket communication that this project was part of [this](https://github.com/hany606/COEX-Internship19/tree/master/projects/Human_pose_estimation_drone_control); to control a drone clever4 from Copter Express using Human poses.
